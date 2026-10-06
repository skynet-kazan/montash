# Настройка удаленного доступа

- [Удаленка TP-link (новая прошивка)](#удаленка-tp-link-новая-прошивка)
- - [Разрешаем входящий ping](#разрешаем-входящий-ping-новая-прошивка)
- [Удаленка TP-link (старая прошивка)](#удаленка-tp-link-старая-прошивка)
- - [Разрешаем входящий ping](#разрешаем-входящий-ping-старая-прошивка)
- [Удаленка DIR-300](#удаленка-dir-300)
- - [Разрешаем входящий ping](#разрешаем-входящий-ping-dir-300)
- [Удаленка DIR-615](#удаленка-dir-615)
- [Удаленка Zixel](#удаленка-zixel)
- [Удаленка Keenetic ac 750](#удаленка-keenetic-ac-750)
- [Удаленка MikroTik](#удаленка-mikrotik)
- [Удаленка ASUS](#удаленка-asus)
- [Удаленка Mercusis](#удаленка-mercusis)
- [Удаленка Mercusis ac750](#удаленка-mercusis-ac750)
- [Удаленка на Tenda as1200](#удаленка-на-tenda-as1200)
- [Удаленка на Tenda n630](#удаленка-на-tenda-n630)
- - [Открытие пингов](#открытие-пингов)
- [Удаленка на Tenda n300](#удаленка-на-tenda-n300)
- [Настройка роутера XPON ONT F670L/F680/F899](#настройка-роутера-xpon-ont-f670l-f680-f899)
- [Удаленка и пинги на ONU серии QT6000](#удаленка-и-пинги-на-onu-серии-qt6000)
- [Настройка роутера V152](#настройка-роутера-v152)



### Удаленка TP-link (новая прошивка) 
![tp_link_new](../images/routers/tp_link_new_1.png)
#### Разрешаем входящий ping новая прошивка
![tp_link_new](../images/routers/tp_link_new_2.png)

### Удаленка TP-link (старая прошивка) 
![tp_link_old](../images/routers/tp_link_old_1.png)
#### Разрешаем входящий ping старая прошивка
![tp_link_old](../images/routers/tp_link_old_2.png)

### Удаленка DIR-300
![dir_300](../images/routers/dir_300_1.png) 
![dir_300](../images/routers/dir_300_2.png)
#### Разрешаем входящий ping DIR-300
![dir_300](../images/routers/dir_300_3.png)

### Удаленка DIR-615
![dir_615](../images/routers/dir_615.png)

### Удаленка Zixel
![zixel](../images/routers/zixel_1.png)
![zixel](../images/routers/zixel_2.png)

### Удаленка Keenetic ac 750
Сетевые правила – Переадресация>Добавить правило \
![keenetic](../images/routers/keenetic_1.png) \
Сетевые правила – Межсетевой экран>Добавить правило \
![keenetic](../images/routers/keenetic_2.png) \
Управление – Пользователи и доступ \
![keenetic](../images/routers/keenetic_3.png)
![keenetic](../images/routers/keenetic_4.png)

### Удаленка MikroTik
IP – Firewall  \
![mikrotik](../images/routers/mikrotik.png)

### Удаленка ASUS
![asus](../images/routers/asus_1.png)
![asus](../images/routers/asus_2.png)
![asus](../images/routers/asus_3.png)

### Удаленка Mercusis
![mercusis](../images/routers/mercusis.png)

### Удаленка Mercusis ac750
![mercusis_ac750](../images/routers/mercusis_ac750_1.png)
![mercusis_ac750](../images/routers/mercusis_ac750_2.png)
![mercusis_ac750](../images/routers/mercusis_ac750_3.png)

### Удаленка на Tenda as1200
* Прошивку не обновляем 

![tenda_as1200](../images/routers/tenda_as1200.png)

### Удаленка на Tenda n630
![tenda_n630](../images/routers/tenda_n630_1.png)
#### Открытие пингов
![tenda_n630](../images/routers/tenda_n630_2.png)

### Удаленка на Tenda n300
![tenda_n300](../images/routers/tenda_n300.png) 

### Настройка роутера XPON ONT F670L F680 F899
перва наперво, нужно будет сменить логин и пароль для входа в лк и для пользователя user и для admin!
заходим по 192.168.1.1
логин и пароль: user
логин и пароль для админа: admin

следующие настройки делаются под user\
Настройка название вай фай сети: Network - WLAN - SSID Settings\
для сети 2.4 выбираете одну сеть Choose SSID: SSID 1-4, для сети 5 также одну из: SSID 5-8\
![XPON_ONT_F670L](../images/routers/XPON_ONT_F670L_1.png)\
Настройка пароля для вай фая: Network - WLAN - SSID Settings\
выбираем Authentication Type: WPA2-PSK\
для сети 2.4 выбираете одну сеть Choose SSID: SSID 1-4, для сети 5 также одну из: SSID 5-8\
![XPON_ONT_F670L](../images/routers/XPON_ONT_F670L_2.png)\
Для смены пароля входа в лк: Administration - User Management\
![XPON_ONT_F670L](../images/routers/XPON_ONT_F670L_3.png)\
Настройка удаленного доступа  и пингов (она должна быть по умолчанию, но проверьте)\
![XPON_ONT_F670L](../images/routers/XPON_ONT_F670L_4.png)\

### Удаленка и пинги на ONU серии QT6000
![ONU_ серии _QT6000](../images/onushki/ONU_QT6000.png)

### Настройка роутера V152
Подключаемся в LAN порт ONU с сетевой картой ноутбука или компа. На сетевой карте нужно прописать IP из подсети 192.168.100.11 как на скриншоте\
![V152_1](../images/routers/V152_1.png)\
Можно через Wifi подключиться к заводскому названию WirelessNet\
пароль от Wifi:\
``$25ST%3t".^:(`DQ(rx`03y>Gd62exT2oOl-<=i*(0$``\

Заходим на онушку по IP 192.168.100.1

Логин: telecomadmin\
Пароль: admintelecom

![V152_2](../images/routers/V152_2.png)\
![V152_3](../images/routers/V152_3.png)\
![V152_4](../images/routers/V152_4.png)

Advanced – Layer 2/3 Port\
![V152_5](../images/routers/V152_5.png)

Security – DoS Configuration\
![V152_6](../images/routers/V152_6.png)

WLAN – 2.4G Basic Network\
![V152_7](../images/routers/V152_7.png)\
![V152_8](../images/routers/V152_8.png)

WLAN – 5G Basic Network\
![V152_9](../images/routers/V152_9.png)\
![V152_10](../images/routers/V152_10.png)

Настройка WAN\
![V152_11](../images/routers/V152_11.png)\
![V152_12](../images/routers/V152_12.png)

Настройка учетной записи для доступа клиентов на Ону с возможностью замены логина и пароля от WiFi в будущем:\
System management - Account management

![V152_13](../images/routers/V152_13.png)

В поле для пароля задаем номер договора клиента + skynet\
пример: 48355skynet\
То есть будут логопасы для клиента root/48355skynet
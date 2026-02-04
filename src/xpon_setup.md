Подключаетесь к онушке по кабелею или вай-фаю (название сети и пароль на обратной стороне онушки) \
![alt text](../images/xpon_setup/xpon_setup_0.png)

Для автопропа используете XPON SN для любй из трех F670L/F680/F899 (в данном случае это RTEGC60B6BFC)


Логин и пароль по умолчанию admin \
Переходите во вкладку Network - Device information \
![alt text](../images/xpon_setup/xpon_setup_1.jpg)
![alt text](../images/xpon_setup/xpon_setup_2.jpg)

VLAN ID берем из логов в заявке (!) (Илья доделает вашего бота так, что бы вам приходил как уровень сигнала, так и влан клеинта, в ответ на ваш запуск автопропа, пока это не сделают смотреть логи. У каждого клиента СВОЙ ИНДИВИДУАЛЬНЫЙ влан, не перепутайте) \
![alt text](../images/xpon_setup/xpon_setup_3.jpg)

Где смотреть этот влан указано ниже \
![alt text](../images/xpon_setup/xpon_setup_4.jpg)
![alt text](../images/xpon_setup/xpon_setup_5.jpg)

### Настройка роутера, удаленки и пингов на XPON ONT F670L/F680/F899
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
![XPON_ONT_F670L](../images/routers/XPON_ONT_F670L_4.png)
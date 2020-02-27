# openvpn

 
TUN (сетевой туннель) работает на сетевом уровне модели OSI, оперируя IP пакетами. TAP используется для создания сетевого моста, тогда как TUN для маршрутизации.

Чтобы поверить tun необходимо выполнить команду:
        
            vagrant up office1Router
            vagrant up office1Server
            
            
   Чтобы проверить tap необходимо выполнить команду:
   
            vagrant up office2Router
            vagrant up office2Server

   Для RAS запустите скрипт на хостовой машине.

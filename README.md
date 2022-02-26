# gaid
Приняли робота А1 
задание 1.1.
ПОДКЛЮЧИЛИСЬ К РОБОТУ ssh pi@turtlebro9(Номер жеребьевки).local
pASWORD: brobro
Вставляем кардридер в ноутбук редактируем /etc/hosts и /etc/hosyname 
меняем turtlebro01 на номер указанный на роботе 
задание 1.2. 
tauch wpa_supplicant.conf
создали файл
nano wpa_supplikant.conf
открыли его редактор 
https://www.raspberrypi.org/documentation/configuration/boot_folder.md
Создайте на SD карте файл /boot/wpa_supplicant.conf
ctrl_interface=DIR=/var/run/wpa_supplicant GROUP=netdev
update_config=1
country=US

network={
    ssid="WIFI_NETWORK_NAME"
    psk="wifipassword"
}
Демонстрация
в терминале  ctrl alt t 
 через веб морду 8080
 через rospi-config
 демонстрация на /etc/hosts b /etc/hostnme
 и 5 network options
 
 A2
 название дистрибутива и кодовое имя 
 lsb_release -a или cat/etc/-release
 версия питона 
 python3 --version
 версия rospy
 rosservision rospy
температура процессора
vcgencmd mcsers_temb
 
 ![1рос](https://user-images.githubusercontent.com/100117191/155830729-88a53fff-5b3f-40a1-b366-64ff98d460e1.jpg)
![2рос](https://user-images.githubusercontent.com/100117191/155830732-354e2078-c8c3-43e3-a8a9-bd2feee5e223.jpg)
![3рос](https://user-images.githubusercontent.com/100117191/155830733-aaf61704-f54d-4dab-bd98-0ec616deb59e.jpg)
![4рос](https://user-images.githubusercontent.com/100117191/155830734-cedcef16-8a20-428b-a635-7ab03675983f.jpg)
![5рос](https://user-images.githubusercontent.com/100117191/155830735-a9465b58-c1b9-4b9f-827e-f7432b295c29.jpg)
![6рос](https://user-images.githubusercontent.com/100117191/155830736-9e89d774-43bb-4718-9f49-2f7d0fa5e6d9.jpg)
![7рос](https://user-images.githubusercontent.com/100117191/155830737-1ed73e4e-d0b7-41e9-afc4-452a7900738d.jpg)
![8рос](https://user-images.githubusercontent.com/100117191/155830738-7edb52eb-4744-4dd9-9f1c-1fae1c4c56ef.jpg)
![9рос](https://user-images.githubusercontent.com/100117191/155830739-4890354e-5818-4a55-bc2b-afacb3fefbb0.jpg)
![10рос](https://user-images.githubusercontent.com/100117191/155830740-465bafa5-a01c-402b-b0b3-a6d21de802ff.jpg)
![11рос](https://user-images.githubusercontent.com/100117191/155830741-3e194323-72f1-4b35-93f5-de6d994fc039.jpg)
![12рос](https://user-images.githubusercontent.com/100117191/155830742-ae142e98-021e-4b5d-a762-1313dba086c0.jpg)
![13рос](https://user-images.githubusercontent.com/100117191/155830743-8546dba4-812d-4234-a2f8-b0707c3df65e.jpg)
![14рос](https://user-images.githubusercontent.com/100117191/155830745-cc6be54a-3ad9-45ff-93cd-285249b70425.jpg)
![15рос](https://user-images.githubusercontent.com/100117191/155830746-340590ff-26f1-4ebf-8a2c-755cd6f69e00.jpg)
![16рос](https://user-images.githubusercontent.com/100117191/155830747-b92ed0da-5907-4d22-a8c2-06481ccfdca8.jpg)
![17рос](https://user-images.githubusercontent.com/100117191/155830748-7c9d03cb-236a-45be-ae7e-bf8a7c154e8f.jpg)
![18рос](https://user-images.githubusercontent.com/100117191/155830749-a8efdab1-6850-48ab-82ee-b6f4f8eb3b54.jpg)
![19рос](https://user-images.githubusercontent.com/100117191/155830750-9b7d3811-7d26-4033-83e3-e94ed79bf816.jpg)
![20 рос](https://user-images.githubusercontent.com/100117191/155830751-6add9604-b582-48df-9e83-3f8f5d923e3e.jpg)
![рос 21](https://user-images.githubusercontent.com/100117191/155830752-2abcc71a-003f-40cc-9e5f-4f0bc204bec2.jpg)

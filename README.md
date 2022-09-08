# kendin_yap_linux_otopilot_ardupilot


Bu yönergeler,ardupilot çalıştıran bir linux otopilot kartı edinmek içindir.Yönergeler kart yapısı olarak erle robotics üretimi ,şu an üretimi yapılmayan,pxf mini sensör karti ve linux sistem entegrasyonları içindir.

Bu projeyi yapabilmeniz için biraz el becerisine ihtiyacınız olacaktır.Lehimleme konusunda biraz hassasiyet gerekebilir eğer tecrübeniz bu konuda az ya da kendinize güvenmiyorsanız pratiği çok olan birinden yardım almanızı tavsiye ederim.



Proje için ihtiyacınız olan ekipmanlar şunlardır:

1. Raspberry Pi  3 , 3+ , Zero , Zero W
2. Tavsiye olarak minimum 8 GB SD Kart (Dikkat etmeniz gereken nokta yüksek hızlı olması gerektiğidir.) 
3. invenSense MPU9250 ivme sensör kartı
4. MS5611 barometre sensör kartı 
5. GPS modülü
6. PCA9685 PWM Servo sürücü
7. 2x40 dişi yada erkek pin
8. Prototipleme kartı
9. Çok kanallı kablo 
10. Lehim teli
11. Lehim makinasi
12. 

Mpu-9250 Prototipleme kartı

![imu](https://github.com/MFurkanATES/kendin_yap_linux_otopilot_ardupilot/blob/main/MPU-9250-Accel-Gyro-and-Mag-Module-Connections.jpg)

MS5611 Prototpileme kartı

![baro](https://github.com/MFurkanATES/kendin_yap_linux_otopilot_ardupilot/blob/main/baro_ms5611.jpg)

Raspberry Pi Zero Wireless

![pi_zero](https://github.com/MFurkanATES/kendin_yap_linux_otopilot_ardupilot/blob/main/rpizero.jpeg)

öncelikli olarak bir yerleşim planı secmelisiniz.Benim tercih ettiğim yerleşim şu şekildedir.Bu konuda çok önemli bir konu yok sadece lehimleme kolaylığndan dolayi bu şekilde seçilmiştir.

Lehimlemeyi aşağıda ki şematikleri kullanarak istediğiniz gibi yapın 


Proje aşagıdaki kaynaklar kullanılarak yapılmıştır.Araştırmalarınızda ve uçuşlarınızda başarılar dilerim.
Saygılar.

M.Furkan ATEŞ
BlackBird UAV

Ana proje 

https://spikey.si/how-raspberry-pi-zero-got-ardupilot-hopefully-flies/
https://diydrones.com/profiles/blogs/mini-zee-a-100-diy-smart-drone-with-the-pi-zero-and-apm

Gerçek zamanlı işletim sistemi için RT Preempt yamasi

http://www.frank-durr.de/?p=203

Ardupilot projesi

https://github.com/ArduPilot
https://github.com/ArduPilot/ardupilot/blob/master/BUILD.md

Linux servisleri eklemek ve linux için harici kullandığım kaynaklar

https://docs.emlid.com/navio/common/ardupilot/building-from-sources/
https://docs.emlid.com/navio/common/ardupilot/installation-and-running/
https://github.com/angelsantamaria/ardupilot_copter_bbblue
https://github.com/mirkix/ardupilotblue
https://discuss.ardupilot.org/t/beaglebone-blue-ardupilot-blue-real-time-kernel-etc/25530
https://sudonull.com/post/8513-ArduPilot-for-beginners-Installation-and-configuration-on-BeagleBone-Blue

Projenin tam olarak nasıl yapılacağı konusu kontrolsuz şekillerde üretimine sebebiyet vermemek amaçlı tam olarak anlatılmamıştır.

Active Directory Nası Kurulur?

İlk önce windows server 2008-2012R-2016-2019 gibi sürümlerinden bir tanesinin ISO dosyasını indirmeniz gerekecektir.

ISO dosyasını indirdikten sonra VMware uygulamamızı açıyoruz ve yukarıda ki pencerelerden "file" sekmesine tıklıyoruz.


![image](https://github.com/ugurcomptech/active-directory/assets/133202238/47d4cbfd-47e2-44b7-801b-1296577374d9)

Karşımıza çıkan seçeneklerden "New Virtual Machine" seçeneğine tıklıyoruz.

![image](https://github.com/ugurcomptech/active-directory/assets/133202238/eca2e6aa-fee4-4cb1-a6fb-8346c9029924)

Next diyip devam ediyoruz.

![image](https://github.com/ugurcomptech/active-directory/assets/133202238/dc853958-185f-47cb-8e7f-09054ea3586f)


Next diyip devam ediyoruz.


![image](https://github.com/ugurcomptech/active-directory/assets/133202238/c5b6dc2c-4e14-4220-82a7-acd5f6b28e54)


Windows Serverin hangi sürümünü indirdiyseniz onu seçin ve next diyip devam edin.


![image](https://github.com/ugurcomptech/active-directory/assets/133202238/c854fe79-0433-4e32-a828-871c35692838)


Sanal makinayı diskinizde hangi klasöre koyacağınızı soruyor istediğiniz bir yer seçin veya default location ile nexte tıklayıp devam edin.


![image](https://github.com/ugurcomptech/active-directory/assets/133202238/a5d29ab8-481f-41c2-9cc2-980de3800f05)

Kuracağımız sanal makinanın disk boyutunu soruyor genelde 50 GB vermeniz yeterli olacaktır. Karşımıza iki tane seçenek çıkıyor; 
Store virtual disk as a single file : sanal diski tek bir dosya olarak depolamayı sağlar
Splite virtual disk into multiple files: Sanal diskin yeri dolduğunda otomatik olarak diskin boyutunu artırmaya sağlar.


![image](https://github.com/ugurcomptech/active-directory/assets/133202238/af9dc271-295e-4c47-b629-0a13a2959b2e)

Finish deyip bitiriyoruz.



![image](https://github.com/ugurcomptech/active-directory/assets/133202238/cdb2e14e-fe52-4268-8353-38b8f0c24749)


Kurduğumuz sanal makinaya sağ tık yapıp "settings" diyoruz.


![image](https://github.com/ugurcomptech/active-directory/assets/133202238/1c576eef-e27a-4b47-9a83-bf3cf470fac9)

CD/DVD(SATA) sekmesine geliyoruz ve Use Iso İmage File seçeneğini seçip browse butonuna tıklıyoruz.


![image](https://github.com/ugurcomptech/active-directory/assets/133202238/cb777501-d0c9-491a-a40c-66820cf4c122)

İndirdiğiniz ISO dosyası hangi klasördeyse onun yolunu belirtiyoruz.






![image](https://github.com/ugurcomptech/active-directory/assets/133202238/3d2b3699-3fae-4ffa-af83-cd6cb6025707)

Sekmelerden options kısmına geliyoruz.

![image](https://github.com/ugurcomptech/active-directory/assets/133202238/09c60e85-4a0f-4756-90ba-41bb3951ae37)

Advanced seçeneğine tıklayıp Firmware type kısmında ki seçeneklerden BIOS seçeneğini seçiyoruz ve "ok" deyip çıkıyoruz.


![image](https://github.com/ugurcomptech/active-directory/assets/133202238/896245c5-25bd-417f-a96e-af973473f605)

![image](https://github.com/ugurcomptech/active-directory/assets/133202238/222990ce-82e7-4568-9deb-45cc84c7ad6c)

Keyboard or input method kısmından Turkish Q  seçeneğini seçiyoruz

![image](https://github.com/ugurcomptech/active-directory/assets/133202238/bb9d9528-cdfc-4b21-a201-85a68d728eff)
![image](https://github.com/ugurcomptech/active-directory/assets/133202238/e05f54fb-3be2-4ec4-a229-015bbdfd7787)

Install Now dedikten sonra açılmasını bekliyoruz.


![image](https://github.com/ugurcomptech/active-directory/assets/133202238/198a564d-eb2b-474a-9a34-d64383dde28c)



Seçeneklerden en alttakini seçip devam ediyoruz.



![image](https://github.com/ugurcomptech/active-directory/assets/133202238/21ad0d57-dec4-4459-822f-ec36ca2d77a6)
![image](https://github.com/ugurcomptech/active-directory/assets/133202238/c8310fdb-9e4d-4038-b92e-9b3888eea110)


Sözleşmeyi kabul edip devam ediyoruz ve bize windowsu nasıl yükleyeceğimizi soruyor biz direkt windows serverı sıfırdan kuracağımız için Custom: Install Windows Only(advanced) seçeneğini seçiyoruz.




![image](https://github.com/ugurcomptech/active-directory/assets/133202238/7a207863-6c59-441d-b0ae-91bbebdd023f)
![image](https://github.com/ugurcomptech/active-directory/assets/133202238/85d8fc9b-38c2-4bc6-ae84-04d7cc75feb1)


Yükleyeceğimiz diski seçip next diyoruz ve kurulumun tamamlanmasını bekliyoruz.





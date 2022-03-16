# FastChatApp
FastChatApp_AndroidProject

Yapacak olduğum chat uygulaması için karşılama sayfası tasarımını tamamladım.
Giriş sayfası için belirli bir yükleme sayacı oluşturdum ve bunun için çalışan arkadaslardan yardım aldım ve kodu yazdım.

![image](https://user-images.githubusercontent.com/61920968/158580774-1f7db2d6-a519-430c-bcfa-79cafa371940.png)
![image](https://user-images.githubusercontent.com/61920968/158580825-5e2a5983-e881-4a1d-a8f3-14ff7e4fc00a.png)

Adobe XD ile tasarımın resimlerini ve ikonlarını nasıl export edilip android stüdyoya aktarılacağını öğrendim ve tasarım xml dosyalarını projeme entegre ettim.

![image](https://user-images.githubusercontent.com/61920968/158580890-4999067d-8595-41c9-9f55-0f2a607c4bcf.png)
![image](https://user-images.githubusercontent.com/61920968/158580907-a8586908-8725-4abf-8876-bfb08c4edd79.png)

Tüm tasarım işleri bitti yaptığım tüm tasarımı export edip android stüdyoya ekledim ve sadece arka planda kodlarını yazmak kaldı tasarımı böylece tamamlamış olduk. 

![image](https://user-images.githubusercontent.com/61920968/158580951-813e9d8c-0401-49ab-9d31-6622f2a3ed92.png)
![image](https://user-images.githubusercontent.com/61920968/158580957-cea7fc76-0cea-4276-be77-38e07d566245.png)
![image](https://user-images.githubusercontent.com/61920968/158580969-10c9a33d-2a83-4527-be29-3309e8e1a7db.png)
![image](https://user-images.githubusercontent.com/61920968/158580981-604edfc7-cb4f-446a-8af8-48fcd3558e68.png)
![image](https://user-images.githubusercontent.com/61920968/158580991-30741956-2c4b-4b1b-85f0-c8c1f19d53b2.png)

Uygulamam için gereken veri tabanı için firebase kullandım ve kullanımını daha iyi öğrendim.
Kullanıcı bilgileri,mesajlaşma,profil fotoğrafı ve karşılıklı mesajlaşma için işimi çok kolaylaştırdı.

![image](https://user-images.githubusercontent.com/61920968/158581131-f5570e63-1f4d-458f-8161-dfa474e99c05.png)
![image](https://user-images.githubusercontent.com/61920968/158581140-07e97f29-53f9-4fe0-93d0-1f0097de1599.png)
![image](https://user-images.githubusercontent.com/61920968/158581175-3977a3c5-e309-444a-8ca4-f54bd8d6c6f9.png)
![image](https://user-images.githubusercontent.com/61920968/158581186-cfa98460-02ae-47b8-8641-754a3b5ba88a.png)
Uygulamam için Toast message ve alert diyalog uygulamam gerekti ve gerekli bilgilendirmeleri öğrendim.Bunu birkaç örnekle pekiştirdim ve uygulamama ekledim.

![image](https://user-images.githubusercontent.com/61920968/158581278-c106455e-2803-48e6-b97e-4b8b938642d7.png)

Uygulamam için parola sıfırlama için firebase mail link üzerinden parola sıfırmala seçeneği oluşturdum ve bunu uygumama ekledim. 

![image](https://user-images.githubusercontent.com/61920968/158581347-5147f65b-470c-46fa-bb71-fab5dfc78664.png)
![image](https://user-images.githubusercontent.com/61920968/158581358-3e175f02-51a1-4db5-a2f9-875354de8da3.png)

Mesajların id si ve constacturları tutulduğu message sınıfı yazıldı.Message adapter sınıfında da firebase realtime database den id lerin tutulduğu tanıtıldığı kodları yazdım. 

![image](https://user-images.githubusercontent.com/61920968/158581425-8a000995-50c3-4f40-bea4-cdaf47312733.png)
![image](https://user-images.githubusercontent.com/61920968/158581437-c329e637-c394-4bf0-8027-629f38ad69e5.png)
![image](https://user-images.githubusercontent.com/61920968/158581451-639a8759-e0b6-47db-86a7-25f17423d334.png)

Chat uygulamam için karşılıklı iletişimin kolay olması için realtime databasesi kullandım.Users ve chats diye ayırdığım verilerin karşılıklı url lerle mesajlaşmanın karşılıklı olmasını sağladım.
OOP kullanarak kodda daha sade ve anlaşılır olması için sınıflar oluşturduk.Recycview kullanarak ana ekranda kullanıcıların görünmesini ve aynı zamanda karşılıklı mesajlarda da recycview extends (Kalıtım) olarak aldım ve kullandım.



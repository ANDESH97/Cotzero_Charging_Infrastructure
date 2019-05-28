# Cotzero_Charging_Infrastructure
An android app which enables a user to charge his/her Electric Vehicle without the need of a human assitance. The app helps user to locate the best nearby charging point and charge his vehicle by simply scanning the QR code. (I cannot upload the codes as per the NDA agreement.)

Backend- Spring Boot.
Database- MySQL
HTTP Requests- Retrofit.
Architecture used- Model-View-ViewModel.
Security- Spring Security (OAuth) using JWT

Step 1: Login to your Cotzero User Account, or Register if you are not already registered.

![WhatsApp Image 2019-05-28 at 23 41 22 (1)](https://user-images.githubusercontent.com/30666140/58503741-d46d5500-81a6-11e9-97ec-d02ed59243e4.jpeg)

Step 2: At the splash screen, grant the permissions to access Location and Device Id of your phone.
Step 3: Now a map appears at your current location and displays the chargering points nearby, tap on any marker to know more about the charging point.( My current location was Faridabad, Haryana while I was taking the screenshots, hence the abnormal distance value.)

![WhatsApp Image 2019-05-28 at 23 41 22](https://user-images.githubusercontent.com/30666140/58503965-49d92580-81a7-11e9-99cd-e570367fe6fd.jpeg)

![WhatsApp Image 2019-05-28 at 23 41 21 (2)](https://user-images.githubusercontent.com/30666140/58503985-55c4e780-81a7-11e9-9df2-641ee62ba7fd.jpeg)
65-49d92580-81a7-11e9-99cd-e570367fe6fd.jpeg)

![WhatsApp Image 2019-05-28 at 23 41 21 (1)](https://user-images.githubusercontent.com/30666140/58504088-7f7e0e80-81a7-11e9-9017-d6c9a9eec2c1.jpeg)

Step 4: Tap the qr icon to start charging at the desired charging location. After successfull qr scan, you will be redirected to the start session screen. Enter the time for which you wish to charge your EV.

![WhatsApp Image 2019-05-28 at 23 41 21](https://user-images.githubusercontent.com/30666140/58504133-94f33880-81a7-11e9-8968-cef368236b99.jpeg)

Step 5: Now the charging has started, you can exit the app and wait for the charging to be finished.

![WhatsApp Image 2019-05-28 at 23 41 19](https://user-images.githubusercontent.com/30666140/58504365-07fcaf00-81a8-11e9-9399-ae23248fb97f.jpeg)

Step 6: Now you get the details of the bill (For testing purpose, it is very short as of now.)

![WhatsApp Image 2019-05-28 at 23 41 09](https://user-images.githubusercontent.com/30666140/58504405-1fd43300-81a8-11e9-9b1f-d4fdb46a4496.jpeg)



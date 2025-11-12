#  Solar Panel Problem Detection with Custom Drone
>  Real-time solar panel fault detection using a handcrafted drone and deep learning.


## Test Video

[![Test Video](https://img.youtube.com/vi/LRUYP9ZXcmY/0.jpg)](https://www.youtube.com/watch?v=LRUYP9ZXcmY)


---

## Project Video

[![Watch the video](https://img.youtube.com/vi/enpU312Wr6s/0.jpg)](https://www.youtube.com/watch?v=enpU312Wr6s&t=385s)



---


In our project, we built a custom-made quadcopter drone from scratch to detect photovoltaic (PV) panels and identify potential issues on their surfaces.
All hardware components, wiring details, and datasheets are documented in the DroneDonanım.pdf file.

The drone is equipped with an ESP32-CAM and ESP8266 module.
Initially, we used the ESP32-CAM for live video streaming, but due to power limitations, we configured it to capture an image every 5 seconds instead of continuous streaming.
(You can find the related code in CameraWebServer2.rar.)

Using the Wi-Fi capability of the ESP32-CAM, the drone establishes a local network and transmits captured images directly to the computer. These images are then processed by a YOLO-based deep learning model, which detects whether there are any defects or anomalies on the PV panels in real time.

Note: The project is still under development. Stay tuned for upcoming commits and improvements.

Feel free to reach out for any questions or collaboration ideas — I’ll be glad to help!

📧 utkuoztrkm@gmail.com 
🔗 [LinkedIn](https://www.linkedin.com/in/utku-%C3%B6zt%C3%BCrk-7bb6a3229/)
🐙 [GitHub](https://github.com/yutkuz)

---

Projemizde, sıfırdan kendi tasarladığımız el yapımı bir quadcopter drone geliştirerek fotovoltaik (PV) panelleri tespit eden ve panel yüzeyindeki olası sorunları analiz eden bir sistem oluşturduk.
Tüm donanım bileşenleri, bağlantı şemaları ve teknik detaylara DroneDonanım.pdf dosyasından ulaşabilirsiniz.

Drone üzerinde ESP32-CAM ve ESP8266 modülleri bulunmaktadır.
Başlangıçta ESP32-CAM’i canlı yayın için kullandık; ancak güç kısıtlamaları nedeniyle sistemi her 5 saniyede bir fotoğraf çekecek şekilde yeniden yapılandırdık.
(İlgili kodlara CameraWebServer2.rar dosyasında ulaşabilirsiniz.)

ESP32-CAM’in Wi-Fi özelliği sayesinde drone yerel bir ağ kurar ve çekilen görüntüleri anlık olarak bilgisayara iletir. Bu görüntüler, YOLO tabanlı derin öğrenme modelimiz tarafından işlenerek PV panel üzerinde herhangi bir arıza veya anormallik olup olmadığı gerçek zamanlı olarak tespit edilir.

Not: Proje hâlâ geliştirme aşamasındadır. Yeni commit ve iyileştirmeleri yakında paylaşacağız.

Herhangi bir sorunuz veya iş birliği fikriniz olursa, benimle iletişime geçebilirsiniz. Yardımcı olmaktan memnuniyet duyarım!

📧 utkuoztrkm@gmail.com 
🔗 [LinkedIn](https://www.linkedin.com/in/utku-%C3%B6zt%C3%BCrk-7bb6a3229/)
🐙 [GitHub](https://github.com/yutkuz)


---

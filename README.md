# BursaSAB2025_SortoBot

SortoBot este un prototip de robot autonom pentru detectarea și sortarea deșeurilor menajere (plastic, sticlă, carton). Proiectul este realizat pentru **Bursa SAB 2025**, cu accent pe **soluții inteligente pentru orașe sustenabile**, folosind **AI** pentru detecția containerelor și optimizarea traseelor.

![sortobot-fata](https://github.com/user-attachments/assets/0be4961a-94c6-4fc7-93eb-86d985d4c41f)

![sortobot-spate](https://github.com/user-attachments/assets/2305cf88-7383-4299-aec0-4dba8b875e03)

---

## Funcționalități principale

- Detectează coșurile de gunoi folosind un senzor ultrasonic, dar și o cameră **ESP32-CAM + AI**
- Sortare automată în compartimentele potrivite
- Trasee optimizate prin algoritmi AI (smart city, colectare nocturnă)
- Skip automat pentru obiecte care nu sunt containere
- Braț robotic preia și sortează obiectele
- Încărcare automată la stații solare amplasate în cartiere

---

## Portofoliu

[SortoBot_Porotofoliu.pdf](videos and images/_SortoBot - Dan Voiculescu.pdf)

---

## 3D Model Open-Source
  
[SortoBot CAD 3D](https://cad.onshape.com/documents/6dcd17111db380910306cb9f/w/09c7ec735f4629dd65699941/e/f97b531a446c7baf1dd965ba?renderMode=0&uiState=68dac0cf62d1e43322b89178)

---

## Software și integrare AI

- Procesare imagine: [YOLOv8 + OpenCV](https://github.com/Selubipu/InfoEducatie2025_SortoBot/blob/main/computer%20vision/bin_detect.py)
- Comunicarea cu robotul prin WebSocket și HTTP
- Algoritm harta: trasee optimizate pentru acoperire completă
- **Focus AI:** decizii autonome, coordonarea flotei de roboți, colectare eficientă

---

## Componente esențiale

- **ESP32-WROOM** – control general
- **ESP32-CAM** – captură și transmitere imagine
- **PCA9685** – control servomotoare
- **Braț robotic 3 DOF**
- **Baterii + convertoare buck** – alimentare stabilă
- **Senzori IR** – urmărire linie
- **AI** – detecție container, decizii traseu, coordonare flote

---

## Video YouTube

[Vizualizare demo YouTube](https://youtu.be/pKOb_VRmZ50)

---

## Imagini și video suplimentar

<details>
  <summary>Deschide pentru imagini și video</summary>

  ![Schema logică](https://github.com/user-attachments/assets/4635153e-174f-4f07-bb7c-84c2de5af619)

  [Video demo](https://github.com/user-attachments/assets/23158b6e-8c34-4196-94d6-50561dbbfcba)

  ![Robot montat](https://github.com/user-attachments/assets/a9da2578-b35f-405a-b837-394831c31751)

  ![Robot asamblat](https://github.com/user-attachments/assets/f626d822-4479-4860-8af2-110f2207b43f)

</details>

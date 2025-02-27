# Proyecto-inversor 
El proyecto trata de un variador de frecuencia trifasico controlado. Resulta que el proyecto tiene un(os) fallo(s) en el diseño de la placa y es nuestro trabajo encontrarlos y solucionarlos.  

El fallo resulta ser que hay tres componentes (C2,C9,C11) que van a GND1 cuando deberian de ir hacia el +28v.

Este es el estado actual del proyecto: 

El esquematico (Esquematico de Kash Patel):  
![3PhaseYoutube](https://github.com/user-attachments/assets/01d6a948-857c-49c4-a2fb-994fe372c709)

PCB (PCB de Kash Patel): 
![20250203_191114](https://github.com/user-attachments/assets/f7d3b614-60ef-4121-8ff1-44fc49a26e56)
![Picsart_25-02-05_15-24-44-828](https://github.com/user-attachments/assets/f3f4bc45-114d-47c1-85d3-6015cc9435ab)
(Lo circulado en rojo son los Pads que estan conectadas a GND1

Codigo (de Kash Patel): 
[Arduino_Uno3Phase Code.txt](https://github.com/user-attachments/files/18646984/Arduino_Uno3Phase.Code.txt) 

PWM (en Arduino IDE):  
[Codigo PWM Reto Kash.txt](https://github.com/user-attachments/files/18647038/Codigo.PWM.Reto.Kash.txt) 

Primero que todo, aislamos los pads que estaban conectadas a GND1 con ayuda de la Dremel.  
![20250204_204302](https://github.com/user-attachments/assets/b3d4c1ff-2179-448b-9d6f-60744d71c2ab) 

Soldamos los componentes a sus respectivos lugares. 
![20250210_201819](https://github.com/user-attachments/assets/b7e79f61-bb33-4d90-9aee-94435e5708a1)

Y unimos los componentes C2 y C11 por medio de un cable. 
![20250210_201830](https://github.com/user-attachments/assets/7f60b045-2e46-4c21-a286-933620229d84) 

Tambien cambiamos el codigo para que funcionase por medio de un ESP32: 

V1: [Codigo Reto V1.txt](https://github.com/user-attachments/files/18843814/Codigo.Reto.txt) 
V2: [RETO4.txt](https://github.com/user-attachments/files/19014334/RETO4.txt)

# Proyecto-variador 
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

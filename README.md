# Proyecto-IA

Guía Paso a Paso para Ejecutar el Prototipo del Teclado Virtual 

1. Prepara tu equipo 
Asegúrate de tener:  
•	Una cámara web funcional (integrada o externa)  
•	Python 3.8 o superior instalado  
•	Conexión a internet para descargar las dependencias  
2. Instala los requisitos
Abre tu terminal o consola y ejecuta:  
pip install opencv-python mediapipe pygame tensorflow  (Esto instalará todas las bibliotecas necesarias)  
3. Descarga los archivos 
•	detección_manos.py
•	ajustes_sistema.py
•	ejecutar.py
•	teclado.py
•	visualización_teclado.py 
5. Configura el sistema 
Sigue las instrucciones en pantalla:  
• Mantén tu mano a 50 cm de la cámara  
• Realiza los gestos que te indique el sistema  
6. Inicia el teclado virtual
Escribe en terminal:  
python ejecutar.py

7. Usa el teclado
•	Movimiento básico:  Desliza tu dedo índice para navegar por las teclas  
•	Clic: Haz un movimiento rápido hacia abajo con el dedo  
•	Cambio de modo: Toca la tecla "MAYUS" para mayúsculas/minúsculas etc. 

8. Personaliza (opcional)  
Si quieres modificar:  
•	El diseño del teclado → Edita teclado.py 
•	La sensibilidad de gestos → Ajusta los valores en config.json 
•	Los sonidos → Reemplaza los archivos en la carpeta /sounds

Consejos importantes:
•	Usa el sistema en un lugar con buena iluminación  
•	Mantén tu mano estable frente a la cámara  


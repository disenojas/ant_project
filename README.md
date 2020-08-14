# Ant Project

## REQUISITOS
### LIBRERIAS NECESARIAS
```
sudo apt-get install python3-pyqt5
sudo apt-get install python3-rpi.gpio
sudo apt install python3-smbus
```

Si se clono el repositorio entrar a la carpeta ant_project y ejecutar. De otra manera realizar la instalacion de la libreria ADAFRUIT (pasos en LINK UTILES)
```
cd Adafruit_Python_DHT  
sudo python3 setup.py install 
```

### HABILITAR I2C
```
sudo raspi-config 
INTERFACE OPTIONS ---> SPI ---> yes
```

### CLONAR REPOSITORIO
```
cd Desktop
git clone https://github.com/freischarler/ant_project
cd ant_project 
python3 main_original.py
```

*El archivo AntP es una acceso directo, por lo tanto puede moverlo al escritorio

---

## LINKS UTILES PARA DESARROLLADORES
### LIBRERIA ADAFRUIT
```
mkdir -p /home/pi/sources  
cd /home/pi/sources  
git clone https://github.com/adafruit/Adafruit_Python_DHT.git  
cd Adafruit_Python_DHT  
sudo python setup.py install 
```

---

## Contribuciones 

* Cualquier consulta o mejora es bienvenida!
⌨️ [Martin Paz](https://github.com/freischarler) (martin.paz@live.com.ar) 
---


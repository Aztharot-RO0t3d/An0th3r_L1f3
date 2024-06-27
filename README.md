# MAC Changer Tool

## Descripción

Este repositorio contiene una herramienta en Python para cambiar direcciones MAC de interfaces de red en sistemas Unix. La herramienta permite seleccionar una interfaz de red y cambiar su dirección MAC de manera manual o generar una dirección MAC aleatoria.

## Funcionalidades

- Cambio de dirección MAC de una interfaz de red específica.
- Generación aleatoria de direcciones MAC.
- Interfaz de usuario intuitiva mediante la terminal.

## Planificación

La herramienta se diseñó para facilitar la manipulación segura y eficiente de direcciones MAC, especialmente en contextos de pruebas de penetración y seguridad informática. La decisión de utilizar Python y las llamadas al sistema 'ifconfig' se basa en la necesidad de compatibilidad y flexibilidad en entornos Unix.

## Uso

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/tu_usuario/mac-changer.git
   cd mac-changer
   
2. **Ejecutar la herramienta:**
   ```bash
   sudo python mac_changer.py
  
3. **Siguientes pasos:**
* Selecciona la interfaz de red.
* Decide si quieres introducir manualmente una nueva dirección MAC o generar una aleatoria.
* Sigue las instrucciones en pantalla para completar el cambio de dirección MAC.

## Ejemplo:
  ```bash
$ python mac_changer.py
Bienvenido al cambiador de MAC.
Introduce la interfaz: wlan0
¿Quieres generar una MAC aleatoria? (s/n): s
[+] Cambiando dirección MAC para wlan0 a 00:16:3e:12:34:56
[+] Dirección MAC cambiada exitosamente a 00:16:3e:12:34:56
```
## Contribuciones
Las contribuciones son bienvenidas. Si encuentras algún error o tienes alguna mejora, no dudes en abrir un issue o enviar un pull request.

## Nota Final
¡Recuerda siempre utilizar esta herramienta de manera ética y responsable! Manipular direcciones MAC puede tener implicaciones legales y éticas dependiendo del contexto y la jurisdicción.

Hecho con ❤️ por 𝑨𝒛𝒕𝒉𝒂𝒓𝒐𝒕. ¡Diviértete hackeando!

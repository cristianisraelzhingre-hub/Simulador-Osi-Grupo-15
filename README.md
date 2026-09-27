# Simulador-Osi-Grupo-15
# Simulador de Red y Modelo OSI - UNEMI

Este proyecto es una aplicación interactiva desarrollada en **Python** con la biblioteca gráfica **Tkinter**. Permite visualizar y comprender el proceso de encapsulamiento y desencapsulamiento de datos a través de las 7 capas del **Modelo OSI** durante la transmisión entre dos hosts (*Host A - Emisor* y *Host B - Receptor*).

---

## Características del Proyecto

* **Encapsulamiento en Host A (Capas 7 a 1):** Muestra cómo un mensaje de aplicación se empaqueta añadiendo encabezados (*headers*) en cada nivel (Datos, Base64, ID de Sesión, TCP, IP, MAC y Bits).
* **Transmisión por Canal Físico:** Animación en tiempo real del paso de la PDU por el medio de red.
* **Desencapsulamiento en Host B (Capas 1 a 7):** Demuestra el procesamiento y retiro de encabezados hasta recuperar el mensaje original.
* **Consolas en Vivo:** Terminales estilo CLI que muestran logs detallados con tiempos de espera ($W_q$).
* **Interfaz Institucional:** Diseñada con la paleta de colores y formato representativo de la **Universidad Estatal de Milagro (UNEMI)**.

---

## 🛠️ Requisitos e Instalación

Para ejecutar este simulador en tu equipo local:

1. Tener instalado **Python 3.x**.
2. Clonar el repositorio o descargar el archivo `.py`:
   ```bash
   git clone [https://github.com/cristianisraelzhingre-hub/Simulador-Osi-Grupo-15.git](https://github.com/cristianisraelzhingre-hub/Simulador-Osi-Grupo-15.git)

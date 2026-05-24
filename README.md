# AAGO - Android Auto Garage Opener

**AAGO** es la solución definitiva para el control de accesos. Transforma tu teléfono móvil en un mando a distancia inteligente, integrado nativamente en tu coche mediante **Android Auto**. Olvídate de los mandos físicos tradicionales y gestiona la apertura de puertas de garaje de forma segura, privada y sin necesidad de internet.

---

## 🚗 ¿Qué es AAGO?

AAGO no es solo una app, es el software de control para un sistema de hardware embebido. La aplicación se comunica vía Bluetooth Low Energy (BLE) con un módulo físico (basado en ESP32 + transceptores CC1101) instalado en tu vehículo, permitiendo clonar y transmitir señales de radiofrecuencia (433/868 MHz) de manera local y cifrada.

## ⚙️ Características Principales

* **Integración Nativa con Android Auto:** Interfaz optimizada siguiendo las guías de diseño de Google para una conducción segura.
* **Totalmente Local:** No requiere conexión a la nube. Tu móvil y el hardware del coche son los únicos nodos de comunicación.
* **Privacidad por Diseño:** Ningún dato sale de tu dispositivo.
* **Multi-Frecuencia:** Compatible con los estándares europeos más comunes (433.89 MHz y 868 MHz).
* **Alta Seguridad:** Comunicación cifrada vía BLE con autenticación de doble capa (PIN de emparejamiento + Código de enlace interno).
* **Portabilidad:** Funcionalidad de exportación/importación de códigos para configurar varios vehículos en minutos.

---

## 🛠️ Cómo Funciona

1.  **Hardware:** Debes contar con el módulo físico AAGO instalado y alimentado en tu vehículo.
2.  **Vinculación:** Abre la app AAGO en tu móvil, activa el Bluetooth y vincula la aplicación con tu módulo siguiendo el proceso de emparejamiento.
3.  **Clonación:** Utiliza el modo de aprendizaje de la aplicación para "leer" la señal de tu mando físico original.
4.  **Uso:** Una vez conectado el móvil al coche, AAGO aparecerá automáticamente en el lanzador de **Android Auto**. Pulsa el botón correspondiente a la puerta que desees abrir y el módulo físico emitirá la señal de radiofrecuencia.

---

## 🔒 Política de Privacidad

En **AAGO**, valoramos tu privacidad por encima de todo. Nuestra filosofía de diseño es "Privacidad desde el origen" (*Privacy by Design*).

* **No recopilación de datos:** AAGO no recopila, almacena ni comparte información personal de los usuarios.
* **Almacenamiento Local:** Todos los códigos de acceso, configuraciones y datos de emparejamiento Bluetooth se almacenan exclusivamente en el almacenamiento local cifrado de tu dispositivo móvil.
* **Sin Internet:** La aplicación no requiere conexión a internet para funcionar, lo que garantiza que tus códigos nunca son transmitidos a servidores externos ni servicios en la nube.
* **Permisos:** La aplicación solo solicita los permisos estrictamente necesarios (Bluetooth y ubicación para fines de escaneo BLE según lo requerido por Android) para establecer la comunicación directa con el hardware AAGO.

---

## 🚀 Requisitos de Uso

* **Hardware:** Módulo AAGO (ESP32 + CC1101) correctamente configurado.
* **Smartphone:** Dispositivo Android con soporte para Bluetooth Low Energy (BLE).
* **Android Auto:** Versión compatible con el sistema de *Templates* de la `Car App Library`.

---

## 📜 Licencia

Este proyecto es de uso privado. Todos los derechos reservados.

---
*Desarrollado para facilitar la movilidad y la seguridad en el acceso a hogares.*

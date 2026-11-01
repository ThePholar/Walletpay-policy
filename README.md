# Política de Privacidad de Wallet Pay

**Última actualización:** 1 de noviembre de 2026

La aplicación **Wallet Pay** (en adelante, "la Aplicación") está desarrollada por **Thepholar** como una herramienta de control y gestión de finanzas personales. La privacidad y la seguridad de tus datos son nuestra máxima prioridad. Esta Política de Privacidad describe cómo se gestiona y protege tu información al utilizar la Aplicación.

---

### 1. Recopilación y almacenamiento de información
* **Almacenamiento estrictamente local:** Wallet Pay no transfiere, vende ni comparte tus datos financieros o personales con servidores externos, terceros ni servicios en la nube. Toda la información registrada permanece exclusivamente en la memoria local de tu dispositivo.
* **Cifrado de datos:** Toda la base de datos local y los registros de transacciones se almacenan mediante mecanismos de cifrado avanzados (SQLCipher / AES-256 GCM) para garantizar que nadie pueda acceder a tu información sin autorización.

---

### 2. Permisos del dispositivo y uso de los datos
Wallet Pay solicita únicamente los permisos estrictamente necesarios para brindar sus funciones de automatización y gestión:

* **Acceso a notificaciones (Notification Listener Service):** 
  * Este permiso se utiliza únicamente para detectar y procesar en tiempo real los avisos emitidos por aplicaciones financieras o bancarias autorizadas por el usuario.
  * La lectura de notificaciones se ejecuta de manera local e instantánea para autocompletar montos y conceptos de gastos/ingresos.
  * Ningún contenido de tus notificaciones ni de tus mensajes personales es almacenado fuera de la base de datos local cifrada ni se comparte con entidades externas.
* **Almacenamiento / Guardado de archivos:** 
  * Se requiere para exportar cierres mensuales y reportes en formato PDF directamente en el almacenamiento de tu dispositivo.

---

### 3. Seguridad de la interfaz (FLAG_SECURE)
Para proteger la visibilidad de tu información financiera frente a miradas no deseadas, capturas de pantalla no autorizadas o aplicaciones espía, Wallet Pay implementa protecciones a nivel de ventana (`FLAG_SECURE`), bloqueando las capturas de pantalla y ocultando la vista previa de la app en el selector de aplicaciones recientes.

---

### 4. Enlaces y servicios de terceros
La Aplicación no incluye rastreadores de publicidad (*trackers*), kits de desarrollo analítico (SDKs de análisis de comportamiento) ni servicios publicitarios de terceros que recopilen información con fines de elaboración de perfiles comerciales.

---

### 5. Retención y eliminación de datos
Tú tienes el control total de tu información en todo momento:
* Puedes editar o eliminar transacciones individuales directamente desde la interfaz.
* Si desinstalas la Aplicación o borras los datos de almacenamiento desde la configuración de Android, todos los registros y la base de datos cifrada se eliminarán de forma permanente e irreversible de tu dispositivo.

---

### 6. Contacto
Si tienes preguntas, dudas o comentarios acerca de esta Política de Privacidad o el funcionamiento de Wallet Pay, puedes contactarnos a través de:

* **Correo electrónico:** polarxd@icloud.com
* **Desarrollador:** Thepholar

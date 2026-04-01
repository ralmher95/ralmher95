<div align="center">

# María del Rocío Almeida Hernández 
### 💼 Futura Desarrolladora Web | 📊 Especialista en Finanzas
Teléfonos: 627 77 82 23 | 671 29 07 93
[ralmher95@gmail.com](mailto:ralmher95@gmail.com) | Sevilla, España

---

</div>

## 📝 Sobre mí
Futura desarrolladora de aplicaciones web con formación previa en Finanzas y Contabilidad[cite: 3]. [cite_start]Aporto una perspectiva única al desarrollo de software, entendiendo la importancia de la viabilidad económica y la eficiencia de los proyectos desde dentro[cite: 4]. [cite_start]Mi objetivo es unirme a un equipo donde pueda aplicar mi lógica financiera y mis nuevas habilidades de programación[cite: 5].

---

## 🛠️ Tecnologías y Habilidades

He combinado el desarrollo técnico con mi experiencia en gestión para crear una herramienta alineada a las necesidades reales del sector financiero:

| 💻 Desarrollo Web & BD | 📈 Gestión y Finanzas |
| :--- | :--- |
| 🌐 **HTML5 / CSS3** (Intermedio) | 📊 **Excel** (Avanzado) |
| 🐍 **Python** (Intermedio) | 📑 **MiConta** (Avanzado) |
| 🗄️ **MySQL** (Intermedio) | 📄 **Word / PPT** (Avanzado) |
| 🐘 **PHP** (Intermedio) | 💰 **Contabilidad Analítica** |

---

## 🧠 ¿Qué he aprendido con el proyecto https://github.com/ralmher95/erp-financiero?

El desarrollo de este ERP ha sido un reto integral que ha fortalecido mis capacidades en tres pilares fundamentales:

### 1. Ingeniería de Software y Automatización
* **Interoperabilidad:** Aprendí a conectar PHP con herramientas externas como **Tesseract OCR**, gestionando la ejecución de binarios desde el servidor.
* **Arquitectura Profesional:** Implementé por primera vez **Autoloading PSR-4**, lo que me permitió entender cómo se estructuran las aplicaciones empresariales modernas para ser mantenibles.
* **Automatización de Datos:** Utilicé **Python** para crear scripts de utilidad que consolidan el código del proyecto, optimizando mi flujo de trabajo.

### 2. Gestión de Datos y Seguridad
* **Integridad Contable:** Diseñé una base de datos relacional en **MySQL** capaz de mantener la consistencia en registros financieros sensibles.
* **Seguridad de Capas:** Aprendí la importancia de proteger las credenciales mediante variables de entorno y archivos de configuración excluidos del control de versiones.

### 3. Visión de Negocio (FinTech)
* **Digitalización Real:** Entendí cómo transformar un ticket físico en un asiento contable digital, reduciendo el error humano y los tiempos de gestión.
* **Reportes Profesionales:** Dominé la generación de documentos dinámicos (PDF) que cumplen con los estándares de presentación financiera.

---

## 🚀 Aprendizaje y Retos

* **El Reto OCR:** Implementar la limpieza de imágenes y gestión de permisos en el servidor para maximizar la precisión de lectura fue la curva de aprendizaje más valiosa.
* **Optimización SQL:** Crear consultas complejas que generen balances en milisegundos sin comprometer el rendimiento.
* **Namespaces:** Gestión avanzada de espacios de nombres en PHP para evitar colisiones en proyectos que integran múltiples librerías de terceros.

---

## 🎓 Formación Destacada
* **Desarrollo de aplicaciones con tecnologías web** (590h) | Core Networks 
* **Grado en Finanzas y Contabilidad** | Universidad Pablo de Olavide 
* **Aplicaciones informáticas de contabilidad** | Cámara de Comercio de Sevilla 

---

## 💡 Lógica de Programación (SQL)
```sql
-- Consulta para reporte de balances por cliente
DECLARE @consulta NVARCHAR(MAX);
SET @consulta = 'SELECT cliente, SUM(monto) AS total_facturado 
                 FROM contabilidad 
                 WHERE estado = "completado" 
                 GROUP BY cliente';
EXEC sp_executesql @consulta;


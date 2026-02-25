<div align="center">

# María del Rocío Almeida Hernández 
### 💼 Futura Desarrolladora Web | 📊 Especialista en Finanzas
Teléfonos: 627 77 82 23 | 671 29 07 93
[ralmher95@gmail.com](mailto:ralmher95@gmail.com) | Sevilla, España

---

</div>

## 📝 Sobre mí
[cite_start]Futura desarrolladora de aplicaciones web con formación previa en Finanzas y Contabilidad[cite: 3]. [cite_start]Aporto una perspectiva única al desarrollo de software, entendiendo la importancia de la viabilidad económica y la eficiencia de los proyectos desde dentro[cite: 4]. [cite_start]Mi objetivo es unirme a un equipo donde pueda aplicar mi lógica financiera y mis nuevas habilidades de programación[cite: 5].

---

## 🛠️ Tecnologías y Habilidades

| Desarrollo Web & BD | Gestión y Finanzas |
| :--- | :--- |
| 🌐 **HTML5 / CSS3** (Intermedio) | [cite_start]📈 **Excel** (Avanzado) [cite: 22] |
| 🐍 **Python** (Intermedio) | [cite_start]📑 **MiConta** (Avanzado) [cite: 24] |
| 🗄️ **MySQL** (Intermedio) | [cite_start]📄 **Word / PPT** (Avanzado) [cite: 21, 23] |
| 🐘 **PHP** (Intermedio) | 💰 **Contabilidad Analítica** |

---

## 🎓 Formación Destacada
* **Desarrollo de aplicaciones con tecnologías web** (590h) | [cite_start]Core Networks [cite: 13]
* **Grado en Finanzas y Contabilidad** | [cite_start]Universidad Pablo de Olavide [cite: 7]
* **Aplicaciones informáticas de contabilidad** | [cite_start]Cámara de Comercio de Sevilla [cite: 11, 12]

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


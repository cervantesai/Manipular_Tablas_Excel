📄 README – Manipulación de Excel y DataTables (UiPath 2025)
📌 Descripción del Proyecto

Este proyecto de UiPath muestra cómo automatizar tareas de manipulación de datos utilizando Excel y DataTables.
El robot:

Abre o crea un archivo Excel base.

Lee los datos de una hoja específica.

Manipula la información mediante DataTables:

Filtrado

Ordenamiento

Creación de nuevas columnas

Limpieza de datos

Exporta el resultado final a un nuevo archivo Excel llamado Report 1.xlsx.

El flujo es ideal como práctica de aprendizaje para cursos de RPA UiPath 2025.

🧰 Tecnologías / Paquetes utilizados
Paquetes del proyecto

UiPath.Excel.Activities — v3.3.1

UiPath.System.Activities — v25.8.1

UiPath.UIAutomation.Activities — v25.10.20

Excel File Scope usado:

Use Excel File

Read Range

Write Range

Actividades de manipulación de DataTable.

📂 Estructura del Proyecto

📁GENERAR_REPORTE_FILTRADO
📁screenshots
│──Excel filtrado
│──Worflow crea report1
│──workflow de filtrar
📁UiPath
│── Main.xaml
│── project.json
│── Ejercicio UiPath.xlsx     (archivo base leído)
│── Report 1.xlsx             (archivo generado)  
README.md


▶️ Flujo General del Proceso

Use Excel File → abre el archivo Ejercicio UiPath Base Robot.xlsx.

Read Range → convierte la hoja en un DataTable.

Assign / Filter Data Table / Add Data Column → aplica transformaciones.

Use Excel File → crea o abre Report 1.xlsx.

Write Range → escribe los datos finales.

Guarda y cierra Excel automáticamente.


📝 Requisitos para ejecución

UiPath Studio 2024.10+ o 2025

Excel instalado

Paquetes del proyecto restaurados

Archivos en la carpeta raíz del proyecto



💡 Cómo ejecutar

Abre el proyecto en UiPath Studio.

Modifica el Excel file para leer la ruta correcta del archivo si es encesario.

Corre el flujo desde Main.xaml.

Modifica el Excel file con la ruta donde quieres que se guarda Report 1.xlsx 

Revisa Report 1.xlsx con los datos manipulados.

📈 Resultado Final

Al finalizar, obtendrás un archivo Report 1.xlsx que contiene el DataTable procesado con todas las transformaciones aplicadas durante la práctica.

📚 Autor
German Sanchez Cervantes

Proyecto creado para fines educativos dentro del curso “Curso Gratis RPA UiPath 2025”.
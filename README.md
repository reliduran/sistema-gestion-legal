Sistema de Gestión de Expedientes Legales
Procuraduría de Casos Integrales (FPCI)

Este repositorio contiene el prototipo de alta fidelidad (Capa de Vista) desarrollado para la Escuela Superior de Innovación y Tecnología (ESIT), como parte del entregable de la Fase 2: Modelado del Sistema.

📋 Descripción del Proyecto
El sistema es una solución web corporativa diseñada para la gestión integral de casos judiciales, permitiendo centralizar expedientes, controlar plazos procesales y asegurar la integridad documental bajo normativas salvadoreñas.

🛠️ Arquitectura y Tecnologías
Siguiendo los lineamientos de la ESIT, el proyecto adopta una arquitectura, Modelo-Vista-Controlador (MVC):
- Vista: HTML5, CSS3 y JavaScript (Prototipo actual).
- Modelo: Base de datos relacional MySQL (Normalizada a 3FN).
- Controlador: Lógica de negocio proyectada en PHP/Python.

📦 Módulos Funcionales (SRS v1.8)
El sistema se descompone en seis ejes operativos definidos en el Diagrama de Nivel 1:
1. Administración y Seguridad: Control de acceso (RF-000) y gestión de roles con segregación de funciones.
2. Gestión de Clientes: Captura obligatoria de Consentimiento Informado conforme al Decreto N.º 144.
3. Gestión de Expedientes: Generación de Código Único de Expediente y asignación de responsables (RF-002).
4. Control de Plazos: Agenda legal con alertas preventivas SMTP y cálculo automático de días hábiles (RF-010).
5. Gestión Documental: Validador técnico de 200 DPI para cumplimiento notarial según el Decreto 555.
6. Reportes e Indicadores: Tableros de control de efectividad procesal y carga laboral (KPIs).

⚖️ Cumplimiento Normativo
El diseño de este prototipo valida visualmente los requerimientos críticos exigidos:
- RF-001: Casilla de consentimiento para Protección de Datos Personales.
- RF-004: Restricción de resolución técnica mínima para archivos PDF.
- RNF-SEG-03: Preparación de campos para la trazabilidad completa en la bitácora de auditoría.

🚀 Configuración para Visualización Local
Para ejecutar el prototipo en un entorno de desarrollo:
1. Clonar este repositorio en la carpeta `htdocs` de su servidor local (MAMP/XAMPP).
2. Asegurar que el archivo `logo.png` se encuentre en `assets/img/`.
3. Abrir el archivo `index.html` desde el navegador mediante `localhost/sistema-gestion-legal/`.

👥 Desarrolladores (TSU-DS-14)
- Rubén Elí Durán Ramiréz
- Daniel Andrés Escalante Lemus
- Ever Daniel Durán Hernández
- Isaías Alexander Erazo Martínez

---
Este proyecto es un entregable académico para la Escuela Superior de Innovación y Tecnología (ESIT), febrero 2026.

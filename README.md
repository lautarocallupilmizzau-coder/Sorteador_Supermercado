🎉 Sistema de Sorteos para Supermercados
Aplicación de escritorio desarrollada en Java + Swing que permite realizar sorteos mensuales de forma automática, generando ganadores únicos y mostrando los resultados en una interfaz gráfica clara y profesional.
🛒✨ Descripción General
Este sistema simula el sorteo mensual de un supermercado, generando números de ticket aleatorios con el formato:
DD + MM + TICKET
✔️ Controla que no se repitan  
✔️ Permite elegir el mes del sorteo  
✔️ Permite definir la cantidad de ganadores  
✔️ Muestra los resultados en una tabla dinámica  
✔️ Incluye interfaz gráfica intuitiva y moderna
🚀 Características Principales
🗓️ Selección del mes del sorteo

🎯 Ingreso de cantidad de ganadores

🔢 Generación de números aleatorios formateados

🔁 Control de repetidos

📋 Tabla de ganadores actualizada en tiempo real

🧹 Botón para reiniciar el sorteo

🎨 Interfaz gráfica construida con Swing
🧠 Cómo Funciona el Sorteo
Cada número ganador se construye así:

Día del mes (01–31 según corresponda)

Mes seleccionado

Número de ticket (0001–9999)
Ejemplo:
050309876
Esto significa:

Día: 05

Mes: 03

Ticket: 9876

El método buscarRepetido() garantiza que ningún número se repita en la tabla.
🛠️ Tecnologías Utilizadas
Tecnología	Descripción
☕ Java 8+	Lógica del sistema
🖥️ Swing (JFrame, JTable, JComboBox)	Interfaz gráfica
🧰 NetBeans	IDE y diseño visual
📊 DefaultTableModel	Manejo de tabla de ganadores
📂 Estructura del Proyecto
src/
 ├── igu/              → Interfaz gráfica (ventanas, botones, tabla)
 ├── logica/           → Lógica del sorteo
 ├── persistencia/     → Manejo de datos (si aplica)
 ├── imagenes/         → Iconos y recursos gráficos
 └── tpintegrador/     → Clases auxiliares
▶️ Cómo Ejecutarlo
1. Clonar el repositorio:
   git clone https://github.com/lautarocallupilmizzau-coder/Sorteador_Supermercado
2. Abrir NetBeans
3. Ir a File → Open Project
4. Seleccionar la carpeta del proyecto
5. Ejecutar con Run Project (F6)
📸 Capturas de Pantalla
<img width="2553" height="1080" alt="Captura de pantalla 2026-02-12 215836" src="https://github.com/user-attachments/assets/84e6cb17-c270-4b73-b9df-df5ec4a678f3" />
Aquí como puedes apreciar, estaba realizando la interfaz, todavía me quedaba arreglar un par de botones.
<img width="1032" height="635" alt="Captura de pantalla 2026-02-12 220024" src="https://github.com/user-attachments/assets/dfb72499-1a93-4c58-a156-2d79f97e5674" />
FINALMENTE AQUI EL RESULTADO FINAL DE TODA LA INTERFAZ Y DESARROLLO.
🚀 Mejoras Futuras
📄 Exportar ganadores a PDF o Excel

💾 Guardar historial de sorteos

🎨 Modo oscuro

🔧 Personalizar rango de tickets

🌐 Versión web del sistema
👨‍💻 Autor
Lautaro Callupil Mizzau  
Desarrollador Java
Proyecto académico / portfolio

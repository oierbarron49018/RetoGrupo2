<h1>Torneo de Ping Pong</h1>
<p>Aplicación en <b>Java</b> para gestionar torneos de ping-pong registro de jugadores y equipo, creación de grupos, generación de enfrentamientos, registro de resultados y cálculo de clasificaciones.</p>

<h2>Características</h2>
<ul>
  <li>Registrar jugadores y equipos.</li>
  <li>Crear torneos con varios grupos.</li>
  <li>Repartir equipos en grupos automáticamente o manualmente.</li>
  <li>Generar partidos dentro de cada grupo.</li>
  <li>Introducir resultados de cada partido.</li>
  <li>Calcular puntos, victorias, derrotas y clasificación.</li>
  <li>Determinar los equipos clasificados para la fase final.</li>
</ul>

<h2>Tecnologías</h2>
<ul>
  <li>Java 17 o superior</li>
  <li>Git</li>
</ul>

<h2>Requisitos previos</h2>
<ul>
  <li>Tener instalado <b>Java JDK 17+</b>.</li>
  <li>Git configurado.</li>
  <li>Cualquier terminal.</li>
</ul>

<h2>Instalación</h2>
<p>Clona el repositorio:</p>
<img width="500" height="22" alt="clonación del repositorio" src="https://github.com/user-attachments/assets/b922439e-e906-4fbb-b531-bcc9cdbfae78" />

<h2>Guía de uso</h2>
<p>Al ejecutar el programa principal (<code>Main.java</code>), se desplegará un menú interactivo en consola con las siguientes opciones:</p>

<h3>Opciones del Menú</h3>
<ul>
  <li><b>[1] Crear Equipo:</b> Permite registrar un equipo introduciendo su nombre, fecha de fundación y los datos de su entrenador.</li>
  <li><b>[2] Crear Jugador:</b> Registra un nuevo jugador solicitando sus datos personales, salario, rol y posición.</li>
  <li><b>[0] Salir:</b> Finaliza la ejecución del programa.</li>
</ul>

<h3>Reglas de Validación de Datos</h3>
<p>La aplicación valida automáticamente la información ingresada para garantizar la integridad de los datos:</p>

<ul>
  <li><b>Nombres, Apellidos y Nacionalidad:</b> Solo se permiten letras (incluidas tildes y ñ), espacios y guiones (<code>-</code>).</li>
  <li><b>Formato de Fechas:</b> Todas las fechas deben introducirse en el formato <code>dd/MM/yyyy</code> y no pueden ser fechas futuras.</li>
  <li><b>Creación de Equipo:</b>
    <ul>
      <li>La fecha de fundación debe ser a partir del año <b>1980</b> en adelante.</li>
      <li>El entrenador debe ser mayor de edad (mínimo <b>18 años</b>).</li>
    </ul>
  </li>
  <li><b>Creación de Jugador:</b>
    <ul>
      <li>Edad mínima requerida: <b>16 años</b>.</li>
      <li>Sueldo mensual: Debe ser estrictamente superior al Salario Mínimo Interprofesional fijado (<b>> 1300.0 €</b>).</li>
      <li>Rol permitido: <code>Cap</code> (Capitán), <code>Titu</code> (Titular) o <code>Sup</code> (Suplente).</li>
      <li>Posición permitida: <code>der</code> (Derecha) o <code>izq</code> (Izquierda).</li>
    </ul>
  </li>
</ul>

<h3>Ejemplo de flujo</h3>
<ol>
  <li>Ejecuta el menú principal y selecciona la opción <code>1</code> para crear un equipo.</li>
  <li>Rellena la fecha de fundación (ej. <code>15/05/1995</code>) y los datos del entrenador.</li>
  <li>Selecciona la opción <code>2</code> para añadir un jugador asociando su rol y posición.</li>
  <li>El sistema confirmará la creación correcta con los datos formateados.</li>
</ol>

<h2>Estructura del proyecto</h2>
<pre>
PROG/
├── fase1/PingPong/
│   └── src/
│       └── Main.java
|
└── fase2/
│  
└── fase3/
</pre>

<h2>Creadores</h2>
<p>Este proyecto ha sido creado por Oier Barron, Unai Castellano, Alejandro Cobreros, Jon Flores y Arkaitz Landa</p>

<h2>Licencia</h2>
<p>Este proyecto está bajo la licencia <a href="">MIT</a>.</p>

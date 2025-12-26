---
layout: default
title: Cierre Proyecto
nav_order: 6
has_toc: true
---

# 🏁 Cierre del Proyecto

## Índice
1. [Costes](#costes)
2. [Tiempos](#tiempos)
3. [Cumplimiento Objetivos](#objetivos)
4. [Dificultades, Desviaciones e Interés Futuro](#dificultades)

## Costes {#costes}  

En este caso nuestros costes se reducen esencialmente a los costes del personal.

<div class="fases-container">
  <style>
    .fases-container {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      max-width: 900px;
      margin: 25px auto;
      border: 1.5px solid #24292e;
      border-radius: 4px;
      overflow: hidden;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    .fases-table {
      width: 100%;
      border-collapse: collapse;
      background-color: white;
    }
    /* Estilo del encabezado basado en tu tabla de fases */
    .fases-table th {
      background-color: #fff2cc; 
      color: #000;
      padding: 12px;
      text-align: center;
      border: 1px solid #24292e;
      font-size: 1.05em;
      font-weight: bold;
      text-transform: uppercase;
    }
    .fases-table td {
      padding: 10px 15px;
      border: 1px solid #24292e;
      color: #000;
      font-size: 0.95em;
    }
    .text-center { text-align: center !important; }
    .text-right { text-align: right !important; }
    
    /* Fila de totales con el estilo dorado de tu tabla de fases */
    .total-row-label {
      background-color: #bf8f00;
      color: white !important;
      font-weight: bold;
      text-align: right;
    }
    .total-row-data {
      background-color: #bf8f00;
      color: white !important;
      font-weight: bold;
      text-align: right;
    }
    
    /* Alternancia de color suave */
    .fases-table tr:nth-child(even):not(.total-row) {
      background-color: #fdfdfd;
    }
  </style>

  <table class="fases-table">
    <thead>
      <tr>
        <th>Recurso / Rol</th>
        <th>Horas</th>
        <th>Coste/Hora</th>
        <th>Subtotal</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><strong>Azael</strong> (Project Manager)</td>
        <td class="text-center">55</td>
        <td class="text-center">22€</td>
        <td class="text-right">1.210€</td>
      </tr>
      <tr>
        <td><strong>Rafael</strong> (Git Master)</td>
        <td class="text-center">45</td>
        <td class="text-center">18€</td>
        <td class="text-right">810€</td>
      </tr>
      <tr>
        <td><strong>Francisco Javier</strong> (Lead Developer)</td>
        <td class="text-center">45</td>
        <td class="text-center">20€</td>
        <td class="text-right">900€</td>
      </tr>
      <tr>
        <td><strong>Isabel</strong> (DBA)</td>
        <td class="text-center">45</td>
        <td class="text-center">18€</td>
        <td class="text-right">810€</td>
      </tr>
      <tr class="total-row">
        <td colspan="3" class="total-row-label">TOTAL COSTES PERSONALES</td>
        <td class="total-row-data">3.730€</td>
      </tr>
    </tbody>
  </table>
</div>

<div style="text-align: justify; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; line-height: 1.6; color: #24292e; max-width: 900px; margin: auto;">
<p>
 Como todas las tecnologías empleadas son Open Source su coste es de 0€. Además, la Universidad de Valladolid ha cedido una máquina virtual para hacer el despliegue de la aplicación. Por lo tanto, su coste también es de 0€.
</p>

<p>
 No obstante, si suponemos que este proyecto se llevase a cabo por una empresa (entorno real) tendríamos que tener en cuenta algunos costes materiales. Por ejemplo, tendría que dar a los empleados ordenadores para realizar su trabajo+periféricos+monitores (unos 700€ cada equipo, luego 700*4=2800€). También había que tener en cuenta que ya no dispondríamos de la máquina virtual para desplegar la aplicación. En ese caso, necesitaríamos un Hosting VPS además de pagar por el dominio. Esto supondría unos 50€ a lo largo de este periodo de tiempo.
</p>
</div>

## Tiempos {#tiempos}

<div style="text-align: justify; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; line-height: 1.6; color: #24292e; max-width: 900px; margin: auto;">
<p>
 Respecto a los tiempos lo vamos a dividir en fases de alto nivel. De cara a calcular la duración del proyecto (camino crítico) distinguimos dos caminos principales que corresponden a la parte de planificación y a la parte de diseño. Además en la tabla también se compara la duración de la actividad con el esfuerzo dedicado. También hay que destacar que en el caso de las fases de planificación la duración, en general, coincide con el esfuerzo porque solo hay un responsable de planificación. Las fases de planificación se marcan con una P y las de diseño con una D. Las que no están marcadas son comunes.
</p>
</div>

<div class="fases-container">
  <style>
    .fases-container {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      max-width: 900px;
      margin: 25px auto;
      border: 1.5px solid #24292e;
      border-radius: 4px;
      overflow: hidden;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    .fases-table {
      width: 100%;
      border-collapse: collapse;
      background-color: white;
    }
    .fases-table th {
      background-color: #fff2cc; /* Color crema del encabezado */
      color: #000;
      padding: 12px;
      text-align: center;
      border: 1px solid #24292e;
      font-size: 1.1em;
      font-weight: bold;
    }
    .fases-table td {
      padding: 10px 15px;
      border: 1px solid #24292e;
      color: #000;
      font-size: 0.95em;
    }
    /* Estilo para las etiquetas de las fases (columna 1) */
    .fase-label {
      font-weight: bold;
      text-align: center;
      background-color: #fff2cc;
    }
    .data-cell {
      text-align: center;
    }
    /* Colores para las sumas finales */
    .suma-row-label {
      background-color: #bf8f00; /* Dorado oscuro */
      color: white !important;
      font-weight: bold;
      text-align: left;
    }
    .suma-row-data {
      background-color: #bf8f00;
      color: white !important;
      font-weight: bold;
      text-align: center;
    }
    /* Alternancia de color suave para filas */
    .fases-table tr:nth-child(even) {
      background-color: #fdfdfd;
    }
  </style>

  <table class="fases-table">
    <thead>
      <tr>
        <th>Fase</th>
        <th>Duración (horas)</th>
        <th>Esfuerzo (horas)</th>
        <th>Observaciones</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="fase-label">Inicio</td>
        <td class="data-cell">2</td>
        <td class="data-cell">8</td>
        <td>Común a todo, decisiones iniciales</td>
      </tr>
      <tr>
        <td class="fase-label">Desarrollo Web (P)</td>
        <td class="data-cell">9</td>
        <td class="data-cell">9</td>
        <td>Creación de la página Web</td>
      </tr>
      <tr>
        <td class="fase-label">Diagramas UML (D)</td>
        <td class="data-cell">10</td>
        <td class="data-cell">40</td>
        <td>Realización de los diagramas pedidos en la parte de diseño</td>
      </tr>
      <tr>
        <td class="fase-label">Planificación Detallada (P)</td>
        <td class="data-cell">23</td>
        <td class="data-cell">23</td>
        <td>PBS, PFD, WBS...</td>
      </tr>
      <tr>
        <td class="fase-label">Implementación (D)</td>
        <td class="data-cell">27</td>
        <td class="data-cell">81</td>
        <td>Desarrollo del código de la aplicación</td>
      </tr>
      <tr>
        <td class="fase-label">Cierre Planificación (P)</td>
        <td class="data-cell">11</td>
        <td class="data-cell">14</td>
        <td>Creación de documentación final y subida de archivos a la Web</td>
      </tr>
      <tr>
        <td class="fase-label">Cierre Diseño (D)</td>
        <td class="data-cell">5</td>
        <td class="data-cell">5</td>
        <td>Revisar y probar</td>
      </tr>
      <tr>
        <td class="suma-row-label">Suma Planificación</td>
        <td class="suma-row-data">45</td>
        <td colspan="2" style="border: none; background: white;"></td>
      </tr>
      <tr>
        <td class="suma-row-label">Suma Diseño</td>
        <td class="suma-row-data">44</td>
        <td colspan="2" style="border: none; background: white;"></td>
      </tr>
    </tbody>
  </table>
</div>

<div style="text-align: justify; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; line-height: 1.6; color: #24292e; max-width: 900px; margin: auto;">
<p>
 Por lo tanto, el camino crítico es el correspondiente a la parte de planificación y el proyecto dura 45h. No obstante, hay que destacar que ambos caminos están bastante balanceados. También hay que destacar la diferencia entre el esfuerzo (en total 190 horas) y la duración en reloj del proyecto (45 horas). Esto se produce porque varios miembros del equipo participan de forma simultánea en algunas tareas. Además, muchas tareas se pueden realizar de forma paralela.
</p>
</div>

## Cumplimiento Objetivos {#objetivos}  
<div style="text-align: justify; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; line-height: 1.6; color: #24292e; max-width: 900px; margin: 20px auto; padding: 0 10px;">

  <p>
    Al final del periodo permitido para realizar el proyecto hemos conseguido completar todos los objetivos que nos habíamos propuesto. Así, a grandes rasgos, estos objetivos son:
  </p>

<ul style="list-style-type: disc; margin-left: 35px; padding-left: 5px;">
<li style="margin-bottom: 8px;">Diseño de todos los diagramas UML pedidos</li>
<li style="margin-bottom: 8px;">Implementación de los casos de uso pedidos</li>
<li style="margin-bottom: 8px;">Desplegar la aplicación usando Java Sping Boot</li>
<li style="margin-bottom: 8px;">Desarrollar una interfaz gráfica para la aplicación (en lugar de línea de comandos)</li>
<li style="margin-bottom: 8px;">Desarrollar la página Web de planificación con toda la información pedida </li>
<li style="margin-bottom: 8px;">Rellenar todas las plantillas de planificación pedidas</li>
<li style="margin-bottom: 8px;">Crear todos los documentos pedidos en planificación </li>
<li>Terminar el proyecto un día antes (26/12/2025) para evitar imprevistos y tener un día de reserva.</li>
</ul>

</div>

<div style="text-align: justify; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; line-height: 1.6; color: #24292e; max-width: 900px; margin: auto;">
<p>
Con esto hemos conseguidos los principales productos: diagramas de diseño, implementación de la aplicación y web e informes de planificación.
</p>
</div>

## Dificultades, Desviaciones e Interés Futuro {#dificultades}  

<div style="text-align: justify; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; line-height: 1.6; color: #24292e; max-width: 900px; margin: auto;">
<p>
El hecho de que se hayan cumplido los objetivos propuestos no quiere decir que no haya habido dificultades durante el desarrollo del proyecto. Dentro de estas dificultades podemos destacar la falta de experiencia a la hora de afrontar el proyecto. Esto hace que sea difícil determinar desde un primer momento que tareas hace falta realizar para conseguir los objetivos marcados, por no hablar de la dificultad de estimar cuánto tiempo te puede llevar cada tarea. Esto provoca que sea difícil hacer una buena planificación en las primeras etapas del proyecto. Además, el hecho de ser la primera vez que te enfrentas a algunas tareas hace que se tenga que dedicar más tiempo en descubrir cómo se deben hacer. También fomenta la aparición de errores.
</p>
  
<p>
Otra de las principales dificultades que hemos encontrado es mantener un ritmo constante en el avance del proyecto. Como ya se ha mencionado en otras secciones, la agenda de los miembros del equipo se ve altamente afectada por factores externos. Esto ha provocado que la realización del proyecto no haya sido uniforme a lo largo del periodo de duración. Como ya se ha mencionado, el esfuerzo se ha concentrado en pocas jornadas de muchas horas. Como resultado, hemos sufrido desviaciones respecto al ritmo de trabajo ideal. De hecho, en los informes semanales se puede ver que en varias ocasiones el proyecto se encontraba retrasado o pausado. Como consecuencia en varias semanas no se ha conseguido completar prácticamente ninguna tarea y por lo tanto no se ha completado ningún producto. Concretamente, en las semanas 2,4 y 5 no se han podido cumplir los plazos previstos.
</p>
<p>
  Por último, lo aprendido en este proyecto puede ser de gran utilidad a la hora de afrontar proyectos futuros. Nos gustaría resaltar la importancia de especializar a los miembros del equipo en diferentes áreas. Esto permite realizar determinadas tareas de forma mucho más eficiente. Además, al ser un proyecto asociado al diseño software en general hay información que puede ser reutilizable o al menos servir de punto de partida para afrontar otros proyectos. Por ejemplo, la identificación de productos, las actividades a realizar… En definitiva, lo más valioso para proyectos futuros es la experiencia/información adquirida al hacer el proyecto que podría ayudar a tener una mejor planificación desde el primer momento.
</p>
</div>

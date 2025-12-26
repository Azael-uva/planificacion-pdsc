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

<div class="costes-container">
  <style>
    .costes-container {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      max-width: 900px;
      margin: 20px auto;
      border-radius: 8px;
      overflow: hidden;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      border: 1px solid #d0d7de;
    }
    .costes-header {
      background-color: #24292e;
      color: white;
      padding: 15px;
      text-align: center;
      font-weight: bold;
      font-size: 1.2em;
    }
    .costes-table {
      width: 100%;
      border-collapse: collapse;
      background-color: white;
    }
    .costes-table th {
      background-color: #f6f8fa;
      color: #57606a;
      padding: 12px;
      text-align: left;
      border-bottom: 2px solid #d0d7de;
      font-size: 0.85em;
      text-transform: uppercase;
    }
    .costes-table td {
      padding: 12px;
      border-bottom: 1px solid #eaecef;
      font-size: 0.95em;
      color: #24292e;
    }
    .costes-table tr:nth-child(even) {
      background-color: #fafbfc;
    }
    .costes-table tr:hover {
      background-color: #f1f8ff;
    }
    .costes-total-row {
      background-color: #ddf4ff !important;
      font-weight: bold;
    }
    .text-right { text-align: right; }
    .text-center { text-align: center; }
    .currency { font-weight: 600; color: #0969da; }
  </style>

  <div class="costes-header">💰 INFORME DE COSTES DEL PROYECTO</div>
  <table class="costes-table">
    <thead>
      <tr>
        <th>Recurso / Rol</th>
        <th class="text-center">Horas</th>
        <th class="text-center">Coste/Hora</th>
        <th class="text-right">Subtotal</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><strong>Azael</strong> (Project Manager)</td>
        <td class="text-center">55</td>
        <td class="text-center">22€</td>
        <td class="text-right currency">1.210€</td>
      </tr>
      <tr>
        <td><strong>Rafael</strong> (Git Master)</td>
        <td class="text-center">45</td>
        <td class="text-center">18€</td>
        <td class="text-right currency">810€</td>
      </tr>
      <tr>
        <td><strong>Francisco Javier</strong> (Lead Developer)</td>
        <td class="text-center">45</td>
        <td class="text-center">20€</td>
        <td class="text-right currency">900€</td>
      </tr>
      <tr>
        <td><strong>Isabel</strong> (DBA)</td>
        <td class="text-center">45</td>
        <td class="text-center">18€</td>
        <td class="text-right currency">810€</td>
      </tr>
      <tr class="costes-total-row">
        <td colspan="3">TOTAL COSTES PERSONALES</td>
        <td class="text-right currency">3.730€</td>
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

<div style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; max-width: 900px; margin: 20px auto; border: 1px solid #d0d7de; border-radius: 10px; overflow: hidden; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
  <div style="background-color: #24292e; color: white; padding: 15px; text-align: center; font-size: 1.1em; font-weight: bold;">
    📅 4.2 TABLA DE TIEMPOS (DURACIÓN VS ESFUERZO)
  </div>
  <table style="width: 100%; border-collapse: collapse; background-color: white; color: #24292e;">
    <thead>
      <tr style="background-color: #f6f8fa; border-bottom: 2px solid #d0d7de;">
        <th style="padding: 12px; text-align: left;">Fase del Proyecto</th>
        <th style="padding: 12px; text-align: center;">Duración (Reloj)</th>
        <th style="padding: 12px; text-align: center;">Esfuerzo (PERT)</th>
        <th style="padding: 12px; text-align: left;">Observaciones de Equipo</th>
      </tr>
    </thead>
    <tbody>
      <tr style="border-bottom: 1px solid #d0d7de;">
        <td style="padding: 12px; font-weight: bold;">1. Iniciación y Análisis</td>
        <td style="padding: 12px; text-align: center;">5 h</td>
        <td style="padding: 12px; text-align: center;">14 h</td>
        <td style="padding: 12px; font-size: 0.9em;">Revisión de enunciados y decisiones iniciales realizadas de forma conjunta.</td>
      </tr>
      <tr style="border-bottom: 1px solid #d0d7de;">
        <td style="padding: 12px; font-weight: bold;">2. Diseño de Modelos UML</td>
        <td style="padding: 12px; text-align: center;">10 h</td>
        <td style="padding: 12px; text-align: center;">28 h</td>
        <td style="padding: 12px; font-size: 0.9em;">Paralelización de diagramas de secuencia y clases por diferentes responsables.</td>
      </tr>
      <tr style="border-bottom: 1px solid #d0d7de;">
        <td style="padding: 12px; font-weight: bold;">3. Planificación Detallada</td>
        <td style="padding: 12px; text-align: center;">15 h</td>
        <td style="padding: 12px; text-align: center;">22 h</td>
        <td style="padding: 12px; font-size: 0.9em;">Elaboración de WBS, PBS y Red de Actividades (Principalmente PM).</td>
      </tr>
      <tr style="border-bottom: 1px solid #d0d7de;">
        <td style="padding: 12px; font-weight: bold;">4. Ejecución (Casos de Uso)</td>
        <td style="padding: 12px; text-align: center;">24 h</td>
        <td style="padding: 12px; text-align: center;">101 h</td>
        <td style="padding: 12px; font-size: 0.9em;">Ejemplo: El Caso Auxiliar dura 10h reales pero supone 30h de esfuerzo al trabajar 3 personas.</td>
      </tr>
      <tr>
        <td style="padding: 12px; font-weight: bold;">5. Cierre y Documentación</td>
        <td style="padding: 12px; text-align: center;">10 h</td>
        <td style="padding: 12px; text-align: center;">25 h</td>
        <td style="padding: 12px; font-size: 0.9em;">Pruebas de sistema coordinadas y agrupación de informes finales.</td>
      </tr>
      <tr style="background-color: #f0f7ff; font-weight: bold; border-top: 2px solid #0969da;">
        <td style="padding: 12px; text-align: right;">TOTALES ACUMULADOS</td>
        <td style="padding: 12px; text-align: center;">~64 h</td>
        <td style="padding: 12px; text-align: center; color: #0969da;">190 h</td>
        <td style="padding: 12px; font-size: 0.85em;">Esfuerzo total consistente con la Red PERT y el presupuesto[cite: 12].</td>
      </tr>
    </tbody>
  </table>
</div>

## Cumplimiento Objetivos {#objetivos}  
## Dificultades, Desviaciones e Interés Futuro {#dificultades}


---
layout: default
title: Residuos Informáticos
---
<style>
  /* --- CONTENEDOR DE TARJETAS --- */
  .grid-visual {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
    gap: 25px;
    margin: 30px 0;
  }

  /* --- ESTILO DE LAS TARJETAS (Variante Residuos) --- */
  .card-premium {
    background: #ffffff;
    border: 1px solid #e1e4e8;
    border-radius: 15px;
    padding: 25px;
    box-shadow: 0 10px 20px rgba(0,0,0,0.05);
    transition: all 0.3s ease;
  }

  .card-premium:hover {
    transform: translateY(-8px);
    box-shadow: 0 15px 30px rgba(0,0,0,0.12);
  }

  /* Colores temáticos para Residuos: Tonos más oscuros y de alerta */
  .border-red { border-top: 8px solid #d73a49; }
  .border-yellow { border-top: 8px solid #ffd33d; }
  .border-teal { border-top: 8px solid #2b7489; }
  .border-gray { border-top: 8px solid #586069; }

  /* --- ESTILO DE LA TABLA --- */
  .tabla-bonita {
    width: 100%;
    border-collapse: collapse;
    margin: 25px 0;
    font-size: 0.95em;
    border-radius: 10px;
    overflow: hidden; 
    box-shadow: 0 4px 15px rgba(0,0,0,0.05);
  }

  .tabla-bonita thead tr {
    background-color: #d73a49; /* Rojo para alertar sobre residuos */
    color: #ffffff;
    text-align: left;
    font-weight: bold;
  }

  .tabla-bonita th, .tabla-bonita td {
    padding: 15px 20px;
    border-bottom: 1px solid #edf2f7;
  }

  .tabla-bonita tbody tr:nth-of-type(even) {
    background-color: #fff5f5;
  }

  .tabla-bonita tbody tr:last-of-type {
    border-bottom: 3px solid #d73a49;
  }

  .card-title {
    font-size: 1.25em;
    font-weight: bold;
    color: #1a1a1a;
    margin-bottom: 12px;
    display: flex;
    align-items: center;
    gap: 10px;
  }
  
  .img-cartoon {
    max-width: 100%;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.15);
    margin: 30px auto;
    display: block;
  }

  .highlight-box {
    background-color: #f6f8fa;
    border-left: 5px solid #d73a49;
    padding: 15px;
    margin: 20px 0;
    font-style: italic;
  }
</style>

<div markdown="1">

<div style="
  text-align: center;
  padding: 20px;
  border-radius: 10px;
  background: linear-gradient(90deg, #d73a49, #586069);
  color: white;
  margin: 20px auto;
">
  <h1 style="margin: 0; font-size: 2.2em;">Residuos Informáticos (e-Waste)</h1>
</div>

<div class="highlight-box">
  "La basura tecnológica es la corriente de residuos sólidos que más rápido crece en el mundo, impulsada por un consumo voraz y ciclos de vida cada vez más cortos."
</div>

---

## 1. El Problema Invisible

<div class="card-premium border-red">
  <div class="card-title">¿Qué son los RAEE?</div>
  <p class="card-text">
    Los <strong>Residuos de Aparatos Eléctricos y Electrónicos (RAEE)</strong> comprenden desde smartphones y portátiles hasta servidores y periféricos. A diferencia de la basura común, estos contienen una mezcla peligrosa de sustancias tóxicas y metales preciosos que requieren un tratamiento especializado.
  </p>
</div>



---

## 2. Anatomía de un Desecho Tecnológico

Un solo ordenador puede contener más de 60 elementos de la tabla periódica. El problema radica en que muchos de ellos son altamente contaminantes si se liberan en el medio ambiente.

<div class="grid-visual">

  <div class="card-premium border-yellow">
    <div class="card-title">Metales Pesados</div>
    <p>Plomo en los tubos de rayos catódicos, cadmio en baterías recargables y mercurio en interruptores y pantallas LCD.</p>
  </div>

  <div class="card-premium border-teal">
    <div class="card-title">Materiales Valiosos</div>
    <p>Oro, plata, cobre y platino. La minería urbana permite recuperar estos metales, evitando nuevas excavaciones mineras.</p>
  </div>

  <div class="card-premium border-gray">
    <div class="card-title">Químicos Persistentes</div>
    <p>Retardantes de llama bromados en plásticos y carcasas, que pueden filtrarse al suelo y contaminar mantos acuíferos.</p>
  </div>

</div>

---

## 3. Impacto Global y Salud

Cuando los residuos informáticos no se gestionan correctamente, suelen acabar en vertederos de países en desarrollo (como Agbogbloshie en Ghana), donde se queman al aire libre para extraer el cobre.

<table class="tabla-bonita">
  <thead>
    <tr>
      <th>Elemento</th>
      <th>Efecto en la Salud / Ambiente</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Plomo</strong></td>
      <td>Daños en el sistema nervioso central y circulatorio.</td>
    </tr>
    <tr>
      <td><strong>Mercurio</strong></td>
      <td>Bioacumulación en peces; daños cerebrales en humanos.</td>
    </tr>
    <tr>
      <td><strong>PVC (Plásticos)</strong></td>
      <td>Al quemarse, libera dioxinas que son altamente cancerígenas.</td>
    </tr>
  </tbody>
</table>



---

## 4. La Regla de las R en la Informática

Para mitigar este desastre ambiental, la gestión de residuos debe seguir un orden jerárquico:

1.  **Reducir:** Alargar la vida útil mediante limpiezas de software y ampliaciones de hardware (más RAM, discos SSD).
2.  **Reutilizar:** Donar equipos que aún funcionan a ONGs, escuelas o centros comunitarios.
3.  **Reciclar:** Llevar los dispositivos a "Puntos Limpios" autorizados para asegurar que el 90% de sus componentes vuelvan a la cadena productiva.

---

## 5. Hacia una Economía Circular

El objetivo final es pasar de una economía lineal (extraer, fabricar, tirar) a una **economía circular**, donde el residuo informático de hoy sea la materia prima del dispositivo de mañana.

<div class="tarjeta-sergio" style="text-align: center; border: none; box-shadow: none;">
  <img src="https://via.placeholder.com/600x300?text=Economia+Circular+IT" class="img-cartoon" alt="Diagrama de economía circular en tecnología">
  <p style="font-style: italic; color: #666; font-size: 0.9em; margin-top: 10px;">
    <strong>Cerrando el ciclo: de residuo a recurso.</strong>
  </p>
</div>

---

<div style="display: flex; justify-content: space-between; margin-top: 40px; padding-top: 20px; border-top: 1px solid #eee;">
  <a href="obsolescencia.html" style="text-decoration:none; color:#d73a49; font-weight:bold;">⬅️ Obsolescencia Programada</a>
  <a href="ecologica.html" style="text-decoration:none; color:#d73a49; font-weight:bold;">Informática Ecológica ➜</a>
</div>

</div>

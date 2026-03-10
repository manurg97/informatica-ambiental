---
layout: default
title: Residuos Informáticos
---


---
layout: default
title: Residuos Informáticos - Visión Innovadora
---

<style>
  /* --- VARIABLES DE COLOR INNOVADORAS --- */
  :root {
    --neon-cyan: #00f2ff;
    --neon-lime: #adff2f;
    --dark-bg: #0a192f;
    --glass-bg: rgba(255, 255, 255, 0.03);
    --glass-border: rgba(255, 255, 255, 0.1);
  }

  .main-content-innovador {
    background-color: var(--dark-bg);
    color: #e6f1ff;
    padding: 40px;
    border-radius: 20px;
    font-family: 'Inter', sans-serif;
    overflow: hidden;
    position: relative;
  }

  /* --- TÍTULO CON GRADIENTE DINÁMICO --- */
  .titulo-glow {
    font-size: 2.8em;
    font-weight: 800;
    background: linear-gradient(90deg, var(--neon-cyan), var(--neon-lime));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    margin-bottom: 10px;
    text-transform: uppercase;
    letter-spacing: -1px;
  }

  /* --- TARJETAS DE CRISTAL (GLASSMORPHISM) --- */
  .contenedor-glass {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
    margin: 40px 0;
  }

  .card-glass {
    background: var(--glass-bg);
    backdrop-filter: blur(10px);
    border: 1px solid var(--glass-border);
    padding: 25px;
    border-radius: 15px;
    transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    position: relative;
  }

  .card-glass:hover {
    background: rgba(0, 242, 255, 0.05);
    border-color: var(--neon-cyan);
    transform: translateY(-10px) scale(1.02);
    box-shadow: 0 10px 30px rgba(0, 242, 255, 0.1);
  }

  .card-glass h3 {
    color: var(--neon-cyan);
    margin-top: 0;
    font-size: 1.2em;
  }

  /* --- SECCIÓN DE TOXICIDAD ESTILO "SCANNER" --- */
  .scanner-box {
    border-left: 2px solid var(--neon-lime);
    padding-left: 20px;
    margin: 30px 0;
    background: linear-gradient(90deg, rgba(173, 255, 47, 0.05) 0%, transparent 100%);
  }

  /* --- TABLA FUTURISTA --- */
  .tabla-futuro {
    width: 100%;
    border-collapse: separate;
    border-spacing: 0 10px;
  }

  .tabla-futuro th {
    color: var(--neon-lime);
    text-transform: uppercase;
    font-size: 0.8em;
    letter-spacing: 2px;
    padding: 15px;
    text-align: left;
  }

  .tabla-futuro td {
    background: rgba(255, 255, 255, 0.02);
    padding: 15px;
    border-top: 1px solid var(--glass-border);
    border-bottom: 1px solid var(--glass-border);
  }

  .tabla-futuro td:first-child { border-radius: 10px 0 0 10px; border-left: 1px solid var(--glass-border); color: var(--neon-cyan); font-weight: bold; }
  .tabla-futuro td:last-child { border-radius: 0 10px 10px 0; border-right: 1px solid var(--glass-border); }

  /* --- BLOQUE DE MINERÍA URBANA --- */
  .mineria-urban-block {
    background: #000;
    border-radius: 20px;
    padding: 40px;
    border: 1px dashed var(--neon-cyan);
    text-align: center;
    margin: 50px 0;
  }

  .dato-impacto {
    font-size: 3em;
    font-weight: bold;
    color: var(--neon-lime);
    display: block;
  }

  /* --- BOTONES NAVEGACIÓN --- */
  .nav-footer-innovador {
    display: flex;
    justify-content: space-between;
    margin-top: 60px;
  }

  .btn-cyber {
    padding: 15px 30px;
    border-radius: 5px;
    text-decoration: none;
    font-weight: bold;
    text-transform: uppercase;
    letter-spacing: 2px;
    transition: 0.3s;
    border: 1px solid var(--neon-cyan);
  }

  .btn-cyber.prev { color: #fff; border-color: #444; }
  .btn-cyber.next { 
    background: var(--neon-cyan); 
    color: var(--dark-bg) !important; 
    box-shadow: 0 0 15px var(--neon-cyan);
  }

  .btn-cyber:hover {
    transform: skewX(-10deg);
    filter: brightness(1.2);
  }
</style>

<div class="main-content-innovador">

  <header class="retraso-1">
    <h1 class="titulo-glow">Hardware Inmortal</h1>
    <p style="font-size: 1.2em; color: #8892b0;">
      Más allá de la pantalla, existe una crisis de silicio. El <span style="color: var(--neon-lime);">e-waste</span> no es basura, es un error de diseño global.
    </p>
  </header>

  <section class="retraso-2">
    <div class="scanner-box">
      <h2>01 // CLASIFICACIÓN DE RESIDUOS</h2>
    </div>
    
    <div class="contenedor-glass">
      <div class="card-glass">
        <h3>NÚCLEOS</h3>
        <p>CPUs, servidores y placas base. El corazón del problema químico.</p>
      </div>
      <div class="card-glass">
        <h3>ÓPTICOS</h3>
        <p>Monitores, paneles OLED y sensores. Contienen gases raros y fósforo.</p>
      </div>
      <div class="card-glass">
        <h3>ENERGÍA</h3>
        <p>Baterías de Litio y Cobalto. Bombas de tiempo químicas si no se tratan.</p>
      </div>
      <div class="card-glass">
        <h3>NODOS</h3>
        <p>Periféricos, routers y cableado. El mayor volumen de plástico y cobre.</p>
      </div>
    </div>
  </section>

  <section class="retraso-3">
    <div class="scanner-box">
      <h2>02 // ANÁLISIS DE TOXICIDAD</h2>
    </div>

    <table class="tabla-futuro">
      <thead>
        <tr>
          <th>Elemento</th>
          <th>Origen</th>
          <th>Impacto Bio</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>MERCURIO</td>
          <td>Pantallas Planas</td>
          <td>Neurotóxico persistente.</td>
        </tr>
        <tr>
          <td>CADMIO</td>
          <td>Semiconductores</td>
          <td>Fallo renal agudo.</td>
        </tr>
        <tr>
          <td>PLOMO</td>
          <td>Micro-soldaduras</td>
          <td>Deterioro cognitivo.</td>
        </tr>
      </tbody>
    </table>
  </section>

  <section class="mineria-urban-block">
    <span class="dato-impacto">+800%</span>
    <h3 style="color: white;">Más eficiente que una mina real</h3>
    <p>Extraer oro de placas de circuito desechadas es 8 veces menos contaminante que la minería de roca tradicional.</p>
    
  </section>

  <section>
    <div class="scanner-box">
      <h2>03 // PROTOCOLO DE MITIGACIÓN</h2>
    </div>
    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 30px;">
      <div class="card-glass">
        <strong style="color: var(--neon-lime);">SOFT-RESCUE</strong>
        <p>Alarga la vida útil usando Software Libre y sistemas ligeros para evitar el descarte prematuro.</p>
      </div>
      <div class="card-glass">
        <strong style="color: var(--neon-lime);">HARD-RECYCLE</strong>
        <p>Entrega de equipos en celdas RAEE certificadas para recuperación de tierras raras.</p>
      </div>
    </div>
  </section>

  <footer class="nav-footer-innovador">
    <a href="contaminacion.html" class="btn-cyber prev">Atrás</a>
    <a href="obsolescencia.html" class="btn-cyber next">Siguiente fase</a>
  </footer>

</div>

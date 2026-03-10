---
layout: default
title: Residuos Informáticos
---


<style>
  /* --- REFINAMIENTO DE ESTILOS PARA ENCAJAR CON EL NAV --- */
  .post-container {
    animation: fadeInUp 0.8s ease-out forwards;
  }

  /* --- TARJETAS CON EL VERDE DEL MENÚ --- */
  .grid-residuos {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    margin: 30px 0;
  }

  .tarjeta-raee {
    background: #ffffff;
    border-radius: 12px;
    padding: 20px;
    border-bottom: 4px solid #00695c; /* Color a juego con el Nav */
    box-shadow: 0 4px 12px rgba(0,0,0,0.08);
    transition: transform 0.3s ease;
  }

  .tarjeta-raee:hover {
    transform: translateY(-8px);
    background-color: #e0f2f1;
  }

  .tarjeta-raee strong {
    color: #004d40;
    display: block;
    font-size: 1.1em;
    margin-bottom: 10px;
  }

  /* --- SECCIÓN DE RIESGOS (TABLA MODERNA) --- */
  .tabla-contenedor {
    overflow-x: auto;
    margin: 25px 0;
    border-radius: 8px;
    box-shadow: 0 0 20px rgba(0,0,0,0.05);
  }

  table {
    width: 100%;
    border-collapse: collapse;
    background: white;
  }

  th {
    background-color: #00695c;
    color: white;
    padding: 15px;
    text-align: left;
  }

  td {
    padding: 12px 15px;
    border-bottom: 1px solid #e0e0e0;
  }

  tr:hover { background-color: #f1f8e9; }

  /* --- CAJA DE IMPACTO (MINERÍA URBANA) --- */
  .info-box {
    background: linear-gradient(135deg, #004d40 0%, #00796b 100%);
    color: white;
    padding: 30px;
    border-radius: 15px;
    margin: 40px 0;
    position: relative;
    overflow: hidden;
  }

  .info-box h3 { color: #80cbc4; margin-top: 0; }

  .info-box::after {
    content: "♻️";
    position: absolute;
    right: -10px;
    bottom: -10px;
    font-size: 8rem;
    opacity: 0.1;
  }

  /* --- LISTA DE ACCIONES --- */
  .lista-acciones {
    list-style: none;
    padding: 0;
  }

  .lista-acciones li {
    background: #fff;
    margin-bottom: 10px;
    padding: 15px 20px;
    border-radius: 8px;
    display: flex;
    align-items: center;
    box-shadow: 0 2px 4px rgba(0,0,0,0.05);
  }

  .lista-acciones li::before {
    content: "✅";
    margin-right: 15px;
  }

  /* --- BOTONES DE NAVEGACIÓN --- */
  .footer-nav {
    display: flex;
    justify-content: space-between;
    margin-top: 50px;
    padding-top: 20px;
    border-top: 2px solid #e0e0e0;
  }

  .btn-action {
    padding: 12px 25px;
    border-radius: 50px;
    text-decoration: none;
    font-weight: bold;
    transition: all 0.3s;
  }

  .btn-volver { background: #cfd8dc; color: #455a64; }
  .btn-siguiente { background: #00695c; color: white; }
  .btn-action:hover { opacity: 0.8; transform: scale(1.05); }

</style>

<div class="post-container">

  <header class="retraso-1">
    <h1>Residuos Informáticos: El Lado Oscuro de la Era Digital</h1>
    <p class="caja-azul" style="background: #e0f2f1; border-left-color: #00695c; color: #004d40;">
      La revolución tecnológica ha transformado nuestra forma de vivir, trabajar y comunicarnos. Sin embargo, este progreso genera un "precio invisible": la acumulación masiva de <strong>e-waste</strong>.
    </p>
  </header>

  <section id="definicion" class="retraso-2">
    <h2>1. ¿Qué son los RAEE?</h2>
    <p>Los <strong>Residuos de Aparatos Eléctricos y Electrónicos</strong> (RAEE) son todos aquellos dispositivos que funcionan con baterías o corriente eléctrica y que han alcanzado el final de su vida útil.</p>
    
    <div class="grid-residuos">
      <div class="tarjeta-raee">
        <strong>Escritorio</strong>
        CPUs, monitores antiguos, teclados y ratones.
      </div>
      <div class="tarjeta-raee">
        <strong>Movilidad</strong>
        Smartphones, tablets y ordenadores portátiles.
      </div>
      <div class="tarjeta-raee">
        <strong>Infraestructura</strong>
        Routers, modems, servidores y cableado.
      </div>
      <div class="tarjeta-raee">
        <strong>Memorias</strong>
        Discos duros, pendrives y unidades SSD.
      </div>
    </div>
  </section>

  <section id="peligros" class="retraso-3">
    <h2>2. El Peligro Químico</h2>
    <p>Un ordenador no es solo plástico; es un ecosistema de sustancias que, fuera de control, resultan letales para el medio ambiente.</p>
    
    <div class="tabla-contenedor">
      <table>
        <thead>
          <tr>
            <th>Elemento</th>
            <th>Ubicación</th>
            <th>Riesgo para la Salud</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td><strong>Plomo</strong></td>
            <td>Soldaduras y monitores.</td>
            <td>Daños al sistema nervioso central.</td>
          </tr>
          <tr>
            <td><strong>Mercurio</strong></td>
            <td>Pantallas LCD.</td>
            <td>Afecta al cerebro y sistema renal.</td>
          </tr>
          <tr>
            <td><strong>Cadmio</strong></td>
            <td>Chips y baterías.</td>
            <td>Altamente cancerígeno.</td>
          </tr>
          <tr>
            <td><strong>Bario</strong></td>
            <td>Carcasas frontales.</td>
            <td>Debilidad muscular.</td>
          </tr>
        </tbody>
      </table>
    </div>
  </section>

  <section id="mineria" class="info-box">
    <h3>3. La Minería Urbana: Una Gran Oportunidad</h3>
    <p>¿Sabías que hay más oro en una tonelada de teléfonos móviles que en una tonelada de mineral extraído directamente de una mina?</p>
    <ul>
      <li><strong>Recuperación de Tierras Raras:</strong> Esenciales para las baterías modernas.</li>
      <li><strong>Ahorro Energético:</strong> Reciclar aluminio gasta un 95% menos energía que fabricarlo de cero.</li>
      <li><strong>Economía Circular:</strong> Menos minería tradicional significa salvar bosques vírgenes.</li>
    </ul>
  </section>

  <section id="soluciones">
    <h2>4. ¿Cómo podemos actuar?</h2>
    <p>Como futuros informáticos, nuestra responsabilidad es liderar el cambio hacia una gestión ética:</p>
    <ul class="lista-acciones">
      <li><strong>Reducir:</strong> No caigas en el consumismo de hardware cada año.</li>
      <li><strong>Reutilizar:</strong> Instala sistemas operativos ligeros (como Linux) para revivir PCs antiguos.</li>
      <li><strong>Reciclar:</strong> Usa exclusivamente los "Puntos Limpios" autorizados.</li>
      <li><strong>Reparar:</strong> Apoya el derecho a la reparación antes de comprar un equipo nuevo.</li>
    </ul>
  </section>

  <footer class="footer-nav">
    <a href="contaminacion.html" class="btn-action btn-volver">← Anterior: Contaminación</a>
    <a href="obsolescencia.html" class="btn-action btn-siguiente">Siguiente: Obsolescencia →</a>
  </footer>

</div>

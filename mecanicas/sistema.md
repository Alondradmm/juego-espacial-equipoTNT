<h1><span>?</span> Cómo jugar</h1>

<p>Descripción de los controles, habilidades y bonificaciones</p>

<h2>Controles</h2>

<ul>
    <li><b>W</b> - Arriba</li>
    <li><b>A</b> - Izquierda</li>
    <li><b>S</b> - Abajo</li>
    <li><b>D</b> - Derecha</li>
    <li><b>Espacio</b> - Disparo</li>
    <li><b> ✨ E</b> - Habilidad Especial</li>
</ul>

<h2> 🎯 Objetivo de Juego</h2>
<p>
    Destruye todas las naves enemigas para salvar a los planetas de su conquista. Esquiva disparos, utiliza las habilidades de los personajes y monta tu mejor estrategia en cada nivel.
</p>

<h2> 🚀 Mecánicas de Nave</h2>

<h3>ShipX0 (Default) - Nave LvL. 1</h3>
<div class="stat-data">Velocidad Movimiento<span>40</span></div>
<div class="bar"><div class="velocidad" style="--valor: 40"></div></div><br>
<div class="stat-data">Frecuencia Disparo<span>30</span></div>
<div class="bar"><div class="velocidad" style="--valor: 30"></div></div><br>
<div class="stat-data">Daño<span>40</span></div>
<div class="bar"><div class="velocidad" style="--valor: 40"></div></div><br>

<h3>TnTShip - Nave LvL. 2</h3>
<div class="stat-data">Velocidad Movimiento<span>30</span></div>
<div class="bar"><div class="velocidad" style="--valor: 30"></div></div><br>
<div class="stat-data">Frecuencia Disparo<span>70</span></div>
<div class="bar"><div class="velocidad" style="--valor: 70"></div></div><br>
<div class="stat-data">Daño<span>60</span></div>
<div class="bar"><div class="velocidad" style="--valor: 60"></div></div><br>
<h3>ShipTP - Nave LvL. 3</h3>
<div class="stat-data">Velocidad Movimiento<span>90</span></div>
<div class="bar"><div class="velocidad" style="--valor: 90"></div></div><br>
<div class="stat-data">Frecuencia Disparo<span>30</span></div>
<div class="bar"><div class="velocidad" style="--valor: 30"></div></div><br>
<div class="stat-data">Daño<span>40</span></div>
<div class="bar"><div class="velocidad" style="--valor: 40"></div></div><br>


<h2> ⭐ Habilidades</h2>
<div>
    <b class="habilidad">Teletransporte:</b>
    Habilidad de teletransporte (TP) aleatorio con unos segundos de invulnerabilidad
    <div class="tag">+100% Movimiento</div>
    <br>
    <b class="habilidad">Dash:</b>
    Habilidad para acelerar rapidamente por 2 segungos con la nave 
    <div class="tag">+50% Movimiento</div>
    <br>
    <b class="habilidad">Fuego:</b>
    Habilidad de disparo de fuego durante 5 segundos cubriendo un área triangular al frente de la nave 
    <div class="tag">+40% Daño de Área</div>
    <br>
    <b class="habilidad">Electroshock:</b>
    Habilidad para disparar un rayo que encadena a naves cercanas entre sí dejandolas inmóviles por un instante (5 segundos)
    <div class="tag">+0% Movimiento de Enemigos</div>
    <br>
</div>

<h2> 🌌🔫 Star Wars Event</h2>

<h3>v2.0.0</h3>
<p>
    Llegaron los laseres!<br>
    Las naves han sido equipadas con armamento de laser, y perteneces al ejercito <b style="color:cyan">Jedi</b>, tendrás que derrotar al <b style="color:red">Lado Oscuro</b>. <br><br>
    Mucha suerte y que la fuerza te acompañe...
    <div class="tag">+50% Velocidad de Disparo </div>
</p>

<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap" rel="stylesheet">

<style>
    body {
        background: #000000;
        font-family: Orbitron;
        padding: 50px;
    }

    span {
        color: #FFFFFF;
    }

    h1, h2, h3 {
        color: cyan
    }

    .habilidad {
        color: cyan
    }

    .bar {
        background: gray;
        height: 5px;
    }

    .velocidad{
        background: cyan;
        height: 5px;
        width: calc(var(--valor) * 1%)
    }

    .stat-data {
        display: flex;
        justify-content: space-between;
    }

    .tag {
        background: cyan;
        text-align: right;
        width: fit-content;
        padding: 5px;
        color: #000000;
        margin-left: auto;
        margin-top: 5px;
    }

</style>
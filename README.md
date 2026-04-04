<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Psicología Deportiva | Proyecto K</title>
    <style>
        /* VARIABLES: Edita los colores aquí fácilmente */
        :root {
            --bg-color: #e0e5ec;
            --main-title: #2d3436;
            --accent-blue: #448aff;
            --accent-red: #ff5252;
            --shadow-dark: #a3b1c6;
            --shadow-light: #ffffff;
            --text-color: #4a4a4a;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            font-family: 'Segoe UI', system-ui, sans-serif;
            margin: 0;
            padding: 40px 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .container {
            max-width: 850px;
            width: 100%;
        }

        /* Estilo Neumórfico para las tarjetas */
        .neu-card {
            background: var(--bg-color);
            border-radius: 30px;
            box-shadow: 9px 9px 16px var(--shadow-dark), 
                       -9px -9px 16px var(--shadow-light);
            padding: 30px;
            margin-bottom: 40px;
        }

        h1 { color: var(--main-title); font-size: 2.5rem; text-align: center; }
        h2 { color: var(--accent-blue); }
        h3 { color: var(--accent-red); margin-bottom: 10px; }

        /* Narrativa Visual */
        .narrative-item {
            border-left: 4px solid var(--accent-blue);
            padding-left: 20px;
            margin: 25px 0;
        }

        .highlight-red { border-left-color: var(--accent-red); }

        /* Pestaña Interactiva (Acordeón Moderno) */
        .tab-section {
            width: 100%;
        }

        details {
            background: var(--bg-color);
            border-radius: 15px;
            box-shadow: 5px 5px 10px var(--shadow-dark), 
                       -5px -5px 10px var(--shadow-light);
            margin-bottom: 15px;
            transition: all 0.3s ease;
        }

        summary {
            padding: 20px;
            font-weight: bold;
            font-size: 1.2rem;
            cursor: pointer;
            list-style: none;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        summary::after {
            content: "▼";
            font-size: 0.8rem;
            color: var(--accent-blue);
        }

        details[open] summary::after { content: "▲"; }

        .tab-content {
            padding: 0 20px 20px 20px;
            font-size: 1rem;
            color: var(--text-color);
            line-height: 1.6;
        }

        .tag {
            display: inline-block;
            padding: 4px 12px;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: bold;
            text-transform: uppercase;
            margin-bottom: 10px;
            background: var(--bg-color);
            box-shadow: inset 2px 2px 5px var(--shadow-dark), 
                        inset -2px -2px 5px var(--shadow-light);
        }

    </style>
</head>
<body>

<div class="container">

    <header class="neu-card">
        <h1>Pérdida de motivación por adversidades externas</h1>
        <p>La motivación deportiva es un equilibrio frágil. A menudo, el muro más alto no es nuestra propia capacidad física, sino los factores externos —presión social, problemas familiares o climas tóxicos de entrenamiento— que terminan por apagar la chispa del atleta.</p>
    </header>

    <section class="neu-card">
        <h2>Impacto en el Atleta</h2>

        <div class="narrative-item highlight-red">
            <span class="tag" style="color: var(--accent-red);">Alerta Crónica</span>
            <h3>BURNOUT</h3>
            <p>El síndrome de desgaste profesional es un estado de agotamiento físico, emocional y mental crónico. Es el resultado de un estrés prolongado donde el deportista siente que ya no tiene nada más que dar.</p>
        </div>

        <div class="narrative-item">
            <span class="tag" style="color: var(--accent-blue);">Consecuencia Directa</span>
            <h3>Bajo Rendimiento</h3>
            <p>Un deportista desmotivado rinde menos, lo que afecta no solo su progreso individual sino también la dinámica de equipos, creando un ciclo de frustración difícil de romper.</p>
        </div>

        <div class="narrative-item">
            <span class="tag" style="color: #6c5ce7;">Factor Social</span>
            <h3>Entorno y Presión</h3>
            <p>La presión excesiva de padres y entrenadores por ganar, ignorando el disfrute o saltándose etapas de formación, es una causa directa de frustración y abandono en jóvenes.</p>
        </div>
    </section>

    <div class="tab-section">
        <details>
            <summary>Cómo canalizar la desmotivación deportiva</summary>
            <div class="tab-content">
                <p>Canalizar la desmotivación requiere transformar la energía negativa en una estrategia de recuperación activa. Aquí te explicamos cómo:</p>
                <ul>
                    <li><strong>Redefinición de metas:</strong> Deja de mirar el trofeo y empieza a mirar el gesto técnico del día.</li>
                    <li><strong>Comunicación Asertiva:</strong> Aprender a poner límites a la presión externa de padres y entrenadores.</li>
                    <li><strong>Autocompasión:</strong> Entender que el descanso mental es tan importante como el entrenamiento físico para evitar el burnout.</li>
                </ul>
                <p>Al final, canalizar no es ignorar el problema, es usar esa incomodidad para rediseñar un entorno que sea sostenible para tu salud mental.</p>
            </div>
        </details>
    </div>

    <footer style="text-align: center; margin-top: 40px; opacity: 0.6;">
        <p>Proyecto K - 2026 | Psicología del Deporte</p>
    </footer>

</div>

</body>
</html>

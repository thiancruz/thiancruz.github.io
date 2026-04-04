<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>K | Psicología Deportiva y Rendimiento</title>
    <style>
        :root {
            --bg: #e0e5ec;
            --text: #31344b;
            --accent: #448aff;
            --warning: #ff5252;
            --shadow-dark: #b8bec5;
            --shadow-light: #ffffff;
        }

        body {
            background-color: var(--bg);
            color: var(--text);
            font-family: 'Segoe UI', Roboto, sans-serif;
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
        }

        .container {
            max-width: 900px;
            width: 100%;
        }

        /* Estilo de Tarjetas Neumórficas */
        .card {
            background: var(--bg);
            border-radius: 20px;
            box-shadow: 10px 10px 20px var(--shadow-dark), 
                       -10px -10px 20px var(--shadow-light);
            padding: 30px;
            margin-bottom: 30px;
        }

        h1 { font-size: 2.2rem; text-align: center; color: var(--accent); }
        h2 { border-bottom: 2px solid var(--accent); display: inline-block; padding-bottom: 5px; }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        /* Narrativa Visual */
        .item {
            padding: 15px;
            border-radius: 15px;
            box-shadow: inset 4px 4px 8px var(--shadow-dark), 
                        inset -4px -4px 8px var(--shadow-light);
        }

        .burnout-alert { color: var(--warning); font-weight: bold; }

        /* Pestaña Interactiva */
        details {
            margin-top: 20px;
            cursor: pointer;
        }

        summary {
            padding: 15px;
            background: var(--accent);
            color: white;
            border-radius: 10px;
            font-weight: bold;
            list-style: none;
            text-align: center;
        }

        .content-tab {
            padding: 20px;
            margin-top: 10px;
            border-radius: 10px;
            box-shadow: inset 2px 2px 5px var(--shadow-dark);
        }

        footer {
            text-align: center;
            margin-top: 50px;
            font-size: 0.9rem;
            opacity: 0.7;
        }
    </style>
</head>
<body>

<div class="container">

    <header class="card">
        <h1>Pérdida de Motivación por Adversidades Externas</h1>
        <p>La psicología deportiva define este fenómeno como una desconexión entre el atleta y su entorno. Cuando las presiones externas superan los recursos internos, la pasión se convierte en carga.</p>
    </header>

    <section class="card">
        <h2>Factores que conducen al desinterés</h2>
        <div class="grid">
            <div class="item">
                <p class="burnout-alert">BURNOUT</p>
                <p>Estado de agotamiento físico y mental crónico provocado por el estrés prolongado. No es cansancio, es vacío emocional.</p>
            </div>
            <div class="item">
                <p><strong>Bajo Rendimiento</strong></p>
                <p>La desmotivación afecta la ejecución técnica y la dinámica de equipo, creando un ciclo de frustración difícil de romper.</p>
            </div>
            <div class="item">
                <p><strong>Entorno y Presión</strong></p>
                <p>La exigencia excesiva de padres y entrenadores por ganar, ignorando el disfrute, es la causa principal del abandono juvenil.</p>
            </div>
        </div>
    </section>

    <section class="card">
        <details>
            <summary>Cómo canalizar la desmotivación deportiva</summary>
            <div class="content-tab">
                <h3>Estrategias de Recalibración</h3>
                <ul>
                    <li><strong>Redefinir el Éxito:</strong> Cambiar el foco del resultado (ganar) al proceso (mejorar la técnica).</li>
                    <li><strong>Límites Saludables:</strong> Aprender a comunicar a entrenadores y padres la necesidad de espacios de disfrute.</li>
                    <li><strong>Descanso Cognitivo:</strong> No todo es entrenar; el cerebro necesita novedad y ocio fuera del deporte para evitar el estancamiento.</li>
                </ul>
            </div>
        </details>
    </section>

    <footer>
        <p>Proyecto K &copy; 2026 | Salud Mental en el Deporte</p>
    </footer>

</div>

</body>
</html>

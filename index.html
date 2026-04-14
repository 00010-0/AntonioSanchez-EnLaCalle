<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi historia - Antonio Sánchez</title>
    <link href="https://fonts.googleapis.com/css2?family=Crimson+Text:ital,wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
        :root {
            --cream: #F7F3EC;
            --ink: #1C1A17;
            --accent: #C4773B;
            --light: #E8DDD0;
            --muted: #6B6259;
        }

        body {
            background: var(--cream);
            color: var(--ink);
            font-family: 'Crimson Text', Georgia, serif;
            overflow-x: hidden;
            overflow-y: hidden; /* Solo scroll horizontal */
            height: 100vh;
        }

        header {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            background: linear-gradient(to bottom, #1C1A17, #2A2722);
            color: white;
            position: relative;
        }

        .header-label {
            font-size: 0.75rem;
            letter-spacing: 0.3em;
            text-transform: uppercase;
            color: var(--accent);
            margin-bottom: 1.5rem;
        }

        header h1 {
            font-size: clamp(2.8rem, 9vw, 5.5rem);
            line-height: 1.05;
            margin-bottom: 1.2rem;
        }

        header h1 em {
            font-style: italic;
            color: var(--accent);
        }

        .typed-line {
            font-size: clamp(1rem, 3vw, 1.25rem);
            color: rgba(255,255,255,0.65);
            max-width: 520px;
        }

        .cursor {
            display: inline-block;
            width: 3px;
            height: 1.1em;
            background: var(--accent);
            vertical-align: middle;
            animation: blink 0.8s infinite;
        }

        /* SCROLL HORIZONTAL PRINCIPAL */
        .horizontal-container {
            display: flex;
            height: 100vh;
            overflow-x: auto;
            overflow-y: hidden;
            scroll-snap-type: x mandatory;
            scroll-behavior: smooth;
            -webkit-overflow-scrolling: touch;
            perspective: 1500px;
            gap: 4rem;
            padding: 0 8vw;
            align-items: center;
        }

        .card {
            min-width: 82vw;
            max-width: 720px;
            height: 78vh;
            background: white;
            border-radius: 20px;
            padding: 3.5rem 2.8rem;
            box-shadow: 0 30px 70px rgba(28, 26, 23, 0.25);
            scroll-snap-align: center;
            transition: all 0.8s cubic-bezier(0.23, 1, 0.32, 1);
            transform: rotateY(-12deg) scale(0.88) translateZ(-80px);
            opacity: 0.85;
            position: relative;
        }

        .card:hover,
        .card:active {
            transform: rotateY(0deg) scale(1) translateZ(0);
            opacity: 1;
            box-shadow: 0 40px 90px rgba(28, 26, 23, 0.35);
        }

        .card.active {
            transform: rotateY(0deg) scale(1.02) translateZ(50px);
        }

        .label {
            font-size: 0.68rem;
            letter-spacing: 0.25em;
            text-transform: uppercase;
            color: var(--accent);
            margin-bottom: 1.8rem;
            display: block;
        }

        .card h2 {
            font-size: clamp(1.85rem, 5vw, 2.6rem);
            line-height: 1.2;
            margin-bottom: 1.8rem;
            font-weight: 400;
        }

        .card p {
            font-size: 1.08rem;
            color: var(--muted);
            margin-bottom: 1.4rem;
        }

        .card strong {
            color: var(--ink);
        }

        blockquote {
            border-left: 4px solid var(--accent);
            padding-left: 1.8rem;
            margin: 2rem 0;
            font-style: italic;
            color: #3f3a32;
        }

        /* Sección de necesidades */
        .needs-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
            gap: 1.4rem;
            margin-top: 2rem;
        }

        .need-card {
            background: #F7F3EC;
            padding: 1.6rem 1.3rem;
            border-radius: 12px;
            text-align: center;
        }

        .need-card h3 {
            font-size: 1.15rem;
            margin-bottom: 0.6rem;
            color: var(--ink);
        }

        /* Donación */
        .donate-card {
            background: #1C1A17;
            color: #F7F3EC;
        }

        .iban-box {
            background: rgba(255,255,255,0.08);
            border: 1px solid rgba(255,255,255,0.15);
            border-radius: 12px;
            padding: 2rem;
            margin: 2rem 0;
        }

        .val {
            font-family: 'Courier New', monospace;
            font-size: 1.15rem;
            font-weight: bold;
            word-break: break-all;
            margin: 0.6rem 0;
        }

        .copy-btn {
            background: transparent;
            border: 1px solid rgba(255,255,255,0.4);
            color: white;
            padding: 0.85rem 2rem;
            border-radius: 50px;
            font-size: 1rem;
            cursor: pointer;
            transition: all 0.3s;
        }

        .copy-btn:hover {
            background: var(--accent);
            border-color: var(--accent);
        }

        .qr-area img {
            max-width: 240px;
            border: 12px solid white;
            border-radius: 16px;
            box-shadow: 0 15px 40px rgba(0,0,0,0.4);
        }

        footer {
            position: fixed;
            bottom: 0;
            left: 0;
            right: 0;
            background: rgba(15,14,12,0.95);
            color: rgba(247,243,236,0.5);
            text-align: center;
            padding: 1.2rem;
            font-size: 0.82rem;
            z-index: 100;
        }

        @keyframes blink {
            50% { opacity: 0; }
        }

        /* Scroll indicator */
        .scroll-hint {
            position: absolute;
            bottom: 40px;
            left: 50%;
            transform: translateX(-50%);
            color: rgba(255,255,255,0.4);
            font-size: 0.75rem;
            letter-spacing: 0.2em;
            animation: fadeUp 2s infinite;
        }
    </style>
</head>
<body>

<header>
    <p class="header-label">Zaragoza • Abril 2026</p>
    <h1>Hola,<br>soy <em>Antonio</em></h1>
    <p class="typed-line"><span id="typed"></span><span class="cursor"></span></p>
    <div class="scroll-hint">Desliza → para conocer mi historia</div>
</header>

<div class="horizontal-container" id="horizontalScroll">

    <!-- Tarjeta 1: Mi historia -->
    <div class="card">
        <span class="label">Te hablo desde el corazón</span>
        <h2>Todo cambió cuando perdí a mi madre</h2>
        <p>Me llamo Antonio Sánchez, tengo 47 años y vivo en Zaragoza.</p>
        <p>Cuando mi madre falleció, la relación con mi padre se rompió por completo. Las discusiones fueron constantes hasta que una noche me denunció por algo que no hice.</p>
        <blockquote>"Fui a juicio y gané, pero me pusieron una orden de alejamiento de mi propia casa."</blockquote>
        <p>Ahora no puedo volver al piso que compartía con ella, aunque por herencia me corresponde una parte. Llevo varias semanas sin un techo fijo y el subsidio no alcanza para cubrir lo básico.</p>
        <p><strong>Gracias por pararte a leer mi historia.</strong> Para mí ya es mucho que alguien me escuche.</p>
    </div>

    <!-- Tarjeta 2: En qué ayuda -->
    <div class="card">
        <span class="label">Cómo puedes ayudarme</span>
        <h2>Tu ayuda puede marcar la diferencia</h2>
        <div class="needs-grid">
            <div class="need-card">
                <h3>Un techo temporal</h3>
                <p>Pagar noches en un hostal o albergue mientras busco estabilidad.</p>
            </div>
            <div class="need-card">
                <h3>Comida diaria</h3>
                <p>Poder comer caliente todos los días.</p>
            </div>
            <div class="need-card">
                <h3>Tramitar la herencia</h3>
                <p>Dinero para un abogado que me ayude a reclamar mi parte del piso.</p>
            </div>
            <div class="need-card">
                <h3>Empezar de cero</h3>
                <p>Un pequeño colchón para buscar trabajo con menos angustia.</p>
            </div>
        </div>
    </div>

    <!-- Tarjeta 3: Donación -->
    <div class="card donate-card">
        <span class="label">Donación directa</span>
        <h2 style="color:#F7F3EC;">Una transferencia tuya<br><em>puede cambiarlo todo</em></h2>
        <p style="color:rgba(247,243,236,0.75);">Sin intermediarios. Todo llega directamente a mí.</p>

        <div class="iban-box">
            <span style="font-size:0.7rem;letter-spacing:0.2em;color:#C4773B;">TITULAR</span>
            <div class="val">Antonio Sánchez García</div>
            
            <span style="font-size:0.7rem;letter-spacing:0.2em;color:#C4773B;">IBAN</span>
            <div class="val" id="iban-val">ES00 0000 0000 0000 0000 0000</div>

            <button class="copy-btn" id="copyBtn" onclick="copyIBAN()">Copiar IBAN</button>
        </div>

        <div class="qr-area" style="text-align:center; margin-top:2rem;">
            <p style="margin-bottom:1rem; color:rgba(247,243,236,0.7);">O escanea aquí</p>
            <img id="qr-image" src="https://api.qrserver.com/v1/create-qr-code/?size=300x300&data=ES0000000000000000000000" alt="QR Donación">
        </div>
    </div>

</div>

<footer>
    Mi historia · Antonio Sánchez · Zaragoza 2026<br>
    <span style="opacity:0.6;">Compartir esta página también ayuda mucho. Gracias de corazón.</span>
</footer>

<script>
    // Typed effect
    const phrases = [
        "Llevo semanas sin un lugar donde dormir...",
        "Solo quiero poder descansar tranquilo.",
        "Nunca imaginé que acabaría así.",
        "Con tu ayuda puedo empezar a salir adelante.",
        "Gracias por escucharme."
    ];
    let i = 0, j = 0, deleting = false;
    const typed = document.getElementById('typed');

    function type() {
        const current = phrases[i];
        if (!deleting) {
            typed.textContent = current.substring(0, ++j);
            if (j === current.length) {
                deleting = true;
                setTimeout(type, 1800);
                return;
            }
            setTimeout(type, 55);
        } else {
            typed.textContent = current.substring(0, --j);
            if (j === 0) {
                deleting = false;
                i = (i + 1) % phrases.length;
                setTimeout(type, 400);
                return;
            }
            setTimeout(type, 30);
        }
    }
    setTimeout(type, 1200);

    // Copy IBAN
    function copyIBAN() {
        const iban = document.getElementById('iban-val').textContent;
        navigator.clipboard.writeText(iban).then(() => {
            const btn = document.getElementById('copyBtn');
            const original = btn.textContent;
            btn.textContent = "✓ Copiado";
            setTimeout(() => btn.textContent = original, 2200);
        });
    }

    // Efecto visual al hacer scroll horizontal
    const container = document.getElementById('horizontalScroll');
    container.addEventListener('scroll', () => {
        const cards = document.querySelectorAll('.card');
        cards.forEach(card => {
            const rect = card.getBoundingClientRect();
            const center = window.innerWidth / 2;
            const distance = Math.abs(rect.left + rect.width/2 - center);
            if (distance < 150) {
                card.classList.add('active');
            } else {
                card.classList.remove('active');
            }
        });
    });
</script>
</body>
</html>

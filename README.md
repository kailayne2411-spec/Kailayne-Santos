<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formatura Kailayne Santos</title>
    <!-- Importando Fontes Elegantes do Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;700&family=Great+Vibes&family=Montserrat:wght@300;400;600&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --bg-color: #1a2e25; /* Verde escuro profundo */
            --gold-light: #f5dba6;
            --gold-main: #cfab66;
            --gold-dark: #8f6f36;
            --text-color: #e0e0e0;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            font-family: 'Montserrat', sans-serif;
            line-height: 1.6;
            overflow-x: hidden;
            border: 10px solid var(--bg-color);
        }

        /* Moldura Dourada Geral */
        .page-border {
            border: 1px solid var(--gold-dark);
            padding: 20px;
            max-width: 600px;
            margin: 0 auto;
            position: relative;
        }

        .corner-decoration {
            position: absolute;
            width: 40px;
            height: 40px;
            border: 2px solid var(--gold-main);
            transition: all 0.5s ease;
        }

        .top-left { top: 10px; left: 10px; border-right: none; border-bottom: none; }
        .bottom-right { bottom: 10px; right: 10px; border-left: none; border-top: none; }

        /* Header */
        header {
            text-align: center;
            padding: 40px 0;
        }

        .icon-top {
            width: 50px;
            height: 50px;
            border: 1px solid var(--gold-main);
            border-radius: 50%;
            margin: 0 auto 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--gold-main);
        }

        h1 {
            font-family: 'Cinzel', serif;
            letter-spacing: 3px;
            font-size: 0.9rem;
            color: var(--gold-main);
            margin-bottom: 20px;
            text-transform: uppercase;
        }

        /* Nome em Destaque */
        .name-banner {
            background: linear-gradient(90deg, var(--gold-dark), var(--gold-light), var(--gold-dark));
            padding: 20px 0;
            margin: 20px 0;
            box-shadow: 0 4px 15px rgba(0,0,0,0.3);
        }

        .graduate-name {
            font-family: 'Great Vibes', cursive;
            font-size: 3.5rem;
            color: #fff;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.3);
            line-height: 1.2;
            text-align: center;
        }

        /* Detalhes */
        .details {
            text-align: center;
            margin: 40px 0;
        }

        .subtitle {
            font-style: italic;
            font-family: 'Cinzel', serif;
            font-size: 0.8rem;
            color: #ccc;
            letter-spacing: 1px;
            margin-bottom: 30px;
            position: relative;
            display: inline-block;
        }
        
        .subtitle::before, .subtitle::after {
            content: "";
            position: absolute;
            top: 50%;
            width: 30px;
            height: 1px;
            background-color: var(--gold-dark);
        }
        .subtitle::before { left: -40px; }
        .subtitle::after { right: -40px; }

        .date {
            font-family: 'Cinzel', serif;
            font-size: 2rem;
            color: #fff;
            margin-bottom: 5px;
        }

        .time {
            font-size: 0.9rem;
            letter-spacing: 2px;
            color: var(--gold-main);
            margin-bottom: 30px;
            text-transform: uppercase;
        }

        .location h3 {
            font-family: 'Cinzel', serif;
            font-size: 1.2rem;
            color: #fff;
            font-weight: 400;
        }
        .location p {
            font-size: 0.8rem;
            letter-spacing: 2px;
            color: #aaa;
            text-transform: uppercase;
        }

        /* Contagem Regressiva */
        .countdown-container {
            margin: 50px 0;
            text-align: center;
        }
        .countdown-title {
            font-family: 'Cinzel', serif;
            font-size: 0.8rem;
            letter-spacing: 2px;
            color: var(--gold-dark);
            margin-bottom: 15px;
        }
        .timer {
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        .time-box {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .time-box span {
            font-family: 'Cinzel', serif;
            font-size: 2.5rem;
            color: #fff;
        }
        .time-box small {
            font-size: 0.7rem;
            color: var(--gold-main);
            text-transform: uppercase;
        }

        /* Mensagem */
        .message-box {
            border-top: 1px solid var(--gold-dark);
            border-bottom: 1px solid var(--gold-dark);
            padding: 40px 20px;
            text-align: center;
            margin: 40px 0;
            position: relative;
        }
        
        .drop-cap {
            font-family: 'Cinzel', serif;
            font-size: 3rem;
            color: var(--gold-main);
            float: left;
            line-height: 0.8;
            margin-right: 10px;
        }

        .message-text {
            font-size: 0.95rem;
            color: #ddd;
            margin-bottom: 20px;
        }

        .signature {
            font-family: 'Great Vibes', cursive;
            font-size: 2.5rem;
            color: var(--gold-main);
            margin-top: 30px;
        }

        /* Dress Code */
        .dress-code {
            text-align: center;
            margin: 50px 0;
            border: 1px solid rgba(255,255,255,0.05);
            background: rgba(0,0,0,0.1);
            padding: 30px;
        }

        .section-title {
            font-family: 'Cinzel', serif;
            font-size: 1.5rem;
            letter-spacing: 3px;
            margin-bottom: 30px;
            color: #fff;
            display: inline-block;
            border-bottom: 1px solid var(--gold-dark);
            padding-bottom: 10px;
        }

        .dc-group {
            margin-bottom: 30px;
        }
        .dc-group h4 {
            font-family: 'Cinzel', serif;
            color: var(--gold-main);
            font-size: 1.2rem;
            margin-bottom: 10px;
        }
        .dc-label {
            font-size: 0.8rem;
            color: #aaa;
            margin-bottom: 15px;
            text-transform: uppercase;
        }
        
        .color-circles {
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        
        .circle {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            flex-direction: column;
            align-items: center;
            position: relative;
        }
        
        .circle span {
            position: absolute;
            bottom: -25px;
            font-size: 0.6rem;
            color: #888;
            white-space: nowrap;
            text-transform: uppercase;
        }

        /* Cores Específicas */
        .c-marsala { background-color: #800020; }
        .c-olive { background-color: #556B2F; }
        .c-blue { background-color: #0000FF; }
        .c-grey { background-color: #d3d3d3; }

        /* Mural de Recados */
        .guestbook {
            margin-top: 60px;
            text-align: center;
        }

        .guestbook input, .guestbook textarea {
            width: 100%;
            background: transparent;
            border: none;
            border-bottom: 1px solid #555;
            color: #fff;
            padding: 10px;
            margin-bottom: 20px;
            font-family: 'Montserrat', sans-serif;
            outline: none;
            transition: border 0.3s;
        }

        .guestbook input:focus, .guestbook textarea:focus {
            border-bottom: 1px solid var(--gold-main);
        }

        .btn-send {
            background-color: transparent;
            border: 1px solid var(--gold-main);
            color: var(--gold-main);
            padding: 10px 30px;
            font-family: 'Cinzel', serif;
            cursor: pointer;
            transition: all 0.3s;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .btn-send:hover {
            background-color: var(--gold-main);
            color: var(--bg-color);
        }

        .messages-list {
            margin-top: 30px;
            text-align: left;
            max-height: 300px;
            overflow-y: auto;
        }

        .message-item {
            background: rgba(255,255,255,0.05);
            padding: 15px;
            margin-bottom: 10px;
            border-left: 3px solid var(--gold-main);
            animation: fadeIn 0.5s;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        footer {
            text-align: center;
            font-size: 0.7rem;
            color: #555;
            margin-top: 50px;
            padding-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        /* Responsividade */
        @media (max-width: 480px) {
            .graduate-name { font-size: 2.5rem; }
            .date { font-size: 1.5rem; }
            .time-box span { font-size: 1.8rem; }
            .page-border { border: none; padding: 10px; }
        }
    </style>
</head>
<body>

    <div class="page-border">
        <div class="corner-decoration top-left"></div>
        <div class="corner-decoration bottom-right"></div>

        <header>
            <div class="icon-top">KS</div>
            <h1>Solenidade de Formatura</h1>
        </header>

        <div class="name-banner">
            <div class="graduate-name">Kailayne<br>Santos</div>
        </div>

        <div class="details">
            <span class="subtitle">CONVIDA PARA CELEBRAR</span>
            
            <div style="margin-top: 30px;">
                <div class="date">19 . 12 . 2025</div>
                <div class="time">Sexta-feira às 19:00H</div>
            </div>

            <div class="location" style="margin-top: 40px;">
                <h3>Castelo Reis Recepções</h3>
                <p>Itapecerica da Serra - SP</p>
            </div>
        </div>

        <!-- Contagem Regressiva Interativa -->
        <div class="countdown-container">
            <div class="countdown-title">CONTAGEM REGRESSIVA</div>
            <div class="timer" id="timer">
                <div class="time-box"><span id="days">00</span><small>Dias</small></div>
                <div class="time-box"><span id="hours">00</span><small>Horas</small></div>
                <div class="time-box"><span id="min">00</span><small>Min</small></div>
                <div class="time-box"><span id="sec">00</span><small>Seg</small></div>
            </div>
        </div>

        <div class="message-box">
            <p class="message-text">
                <span class="drop-cap">E</span>ii, está chegando uma data muito esperada e especial.
                <br><br>
                Daqui a uns dias, encerro um ciclo que me transformou, me ensinou e me fez crescer. 
                Cada passo que dei até aqui carrega histórias, desafios e conquistas que moldaram quem eu sou.
                <br><br>
                E, por isso, neste momento tão especial da minha vida, eu gostaria muito de ter você comigo. 
                Sua presença tornará essa conquista ainda mais significativa.
            </p>
            <div class="signature">Te espero lá!!</div>
        </div>

        <!-- Dress Code Section -->
        <div class="dress-code">
            <h2 class="section-title">DRESS CODE</h2>
            
            <div class="dc-group">
                <h4>ELAS</h4>
                <p class="dc-label">EVITAR CORES:</p>
                <div class="color-circles">
                    <div class="circle c-marsala"><span>Marsala</span></div>
                    <div class="circle c-olive"><span>Verde Oliva</span></div>
                    <div class="circle c-blue"><span>Azul</span></div>
                </div>
            </div>

            <div class="dc-group">
                <h4>ELES</h4>
                <p class="dc-label">EVITAR CORES:</p>
                <div class="color-circles">
                    <div class="circle c-grey"><span>Cinza</span></div>
                    <div class="circle c-blue"><span>Azul</span></div>
                </div>
            </div>
        </div>

        <!-- Mural Interativo -->
        <div class="guestbook">
            <h2 class="graduate-name" style="font-size: 2.5rem; color: #fff; text-shadow: none;">Mural de Recados</h2>
            <p style="color:#aaa; font-size: 0.8rem; margin-bottom: 20px;">Deixe uma mensagem especial para a formanda</p>

            <input type="text" id="guestName" placeholder="Seu Nome">
            <textarea id="guestMessage" rows="3" placeholder="Sua Mensagem"></textarea>
            <button class="btn-send" onclick="addMessage()">Enviar Mensagem</button>

            <div class="messages-list" id="messageContainer">
                <!-- Mensagens aparecerão aqui -->
                <div class="message-item" style="opacity: 0.5;">
                    <strong>Site:</strong> Seja o primeiro a deixar uma mensagem...
                </div>
            </div>
        </div>

        <footer>
            Formal Invite • 2025
        </footer>
    </div>

    <script>
        // Lógica da Contagem Regressiva
        const countDate = new Date('Dec 19, 2025 19:00:00').getTime();

        function updateCountdown() {
            const now = new Date().getTime();
            const gap = countDate - now;

            const second = 1000;
            const minute = second * 60;
            const hour = minute * 60;
            const day = hour * 24;

            const d = Math.floor(gap / day);
            const h = Math.floor((gap % day) / hour);
            const m = Math.floor((gap % hour) / minute);
            const s = Math.floor((gap % minute) / second);

            document.getElementById('days').innerText = d < 10 ? '0' + d : d;
            document.getElementById('hours').innerText = h < 10 ? '0' + h : h;
            document.getElementById('min').innerText = m < 10 ? '0' + m : m;
            document.getElementById('sec').innerText = s < 10 ? '0' + s : s;
        }

        setInterval(updateCountdown, 1000);

        // Lógica do Mural de Recados
        function addMessage() {
            const nameInput = document.getElementById('guestName');
            const msgInput = document.getElementById('guestMessage');
            const container = document.getElementById('messageContainer');

            if(nameInput.value === '' || msgInput.value === '') {
                alert('Por favor, preencha seu nome e a mensagem!');
                return;
            }

            // Remove a mensagem de placeholder se for a primeira
            if(container.children[0].innerText.includes("Seja o primeiro")) {
                container.innerHTML = '';
            }

            const newMessage = document.createElement('div');
            newMessage.classList.add('message-item');
            newMessage.innerHTML = `<strong>${nameInput.value}:</strong> ${msgInput.value}`;

            container.prepend(newMessage); // Adiciona no topo

            // Limpa os campos
            nameInput.value = '';
            msgInput.value = '';
            
            // Efeito visual
            newMessage.scrollIntoView({ behavior: 'smooth' });
        }
    </script>
</body>
</html>

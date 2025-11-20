<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CPS Telecomunicazioni S.r.l. | Progettazione e Installazione Reti Fibra Ottica - Roma</title>
    <meta name="description" content="CPS Telecomunicazioni S.r.l., società italiana con sede a Roma, specializzata in progettazione, installazione, manutenzione e giunzione di reti in fibra ottica. System partner di Fastweb da oltre 20 anni.">
    <meta name="keywords" content="fibra ottica Roma, CPS Telecomunicazioni, partner Fastweb, giunzioni ottiche, FTTH, manutenzione reti">
    <style>
        body { 
            font-family: Arial, sans-serif; 
            margin: 0; 
            background: linear-gradient(135deg, #007BFF, #28A745); /* Blu-verde dal logo */
            color: #333; 
            line-height: 1.6; 
            overflow-x: hidden; 
        }
        header { 
            background: rgba(0,0,0,0.1); 
            padding: 20px; 
            text-align: center; 
            animation: fadeInDown 1.2s ease-out; 
        }
        @keyframes fadeInDown { 
            from { opacity: 0; transform: translateY(-40px); } 
            to { opacity: 1; transform: translateY(0); } 
        }
        .logo { 
            max-width: 250px; 
            height: auto; 
            transition: transform 0.6s ease-in-out; 
            border-radius: 12px; 
            filter: drop-shadow(0 5px 10px rgba(0,0,0,0.3)); 
        }
        .logo:hover { 
            transform: scale(1.15) rotate(360deg); /* Rotazione completa animata */
        }
        nav { 
            background: #DC3545; /* Rosso dal logo */
            padding: 12px; 
            text-align: center; 
            box-shadow: 0 2px 10px rgba(0,0,0,0.2); 
        }
        nav a { 
            color: white; 
            margin: 0 18px; 
            text-decoration: none; 
            transition: all 0.4s ease; 
            position: relative; 
        }
        nav a::after { 
            content: ''; 
            position: absolute; 
            bottom: -5px; 
            left: 50%; 
            width: 0; 
            height: 2px; 
            background: #FFD700; 
            transition: width 0.3s ease, left 0.3s ease; 
        }
        nav a:hover { 
            color: #FFD700; 
            transform: translateY(-2px); 
        }
        nav a:hover::after { 
            width: 100%; 
            left: 0; /* Linea animata sotto */
        }
        section { 
            padding: 60px 20px; 
            max-width: 1200px; 
            margin: auto; 
        }
        .hero { 
            text-align: center; 
            background: rgba(255,255,255,0.95); 
            color: #333; 
            padding: 70px 20px; 
            border-radius: 20px; 
            margin: 20px; 
            animation: slideInUp 1.8s ease-out; 
            box-shadow: 0 10px 30px rgba(0,0,0,0.2); 
        }
        @keyframes slideInUp { 
            from { opacity: 0; transform: translateY(60px); } 
            to { opacity: 1; transform: translateY(0); } 
        }
        .slogan { 
            font-style: italic; 
            font-size: 2em; 
            color: #DC3545; 
            animation: pulseGlow 3s infinite alternate; 
            margin-bottom: 20px; 
        }
        @keyframes pulseGlow { 
            0% { transform: scale(1); text-shadow: 0 0 10px #DC3545; } 
            100% { transform: scale(1.08); text-shadow: 0 0 30px #DC3545, 0 0 40px #DC3545; } 
        }
        .services { 
            display: grid; 
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); 
            gap: 25px; 
        }
        .service-card { 
            background: white; 
            padding: 30px; 
            border-radius: 15px; 
            box-shadow: 0 5px 20px rgba(0,0,0,0.1); 
            transition: all 0.5s cubic-bezier(0.68, -0.55, 0.265, 1.55); 
            cursor: pointer; 
            position: relative; 
            overflow: hidden; 
        }
        .service-card::before { 
            content: ''; 
            position: absolute; 
            top: 0; 
            left: -100%; 
            width: 100%; 
            height: 100%; 
            background: linear-gradient(90deg, transparent, rgba(220,53,69,0.2), transparent); 
            transition: left 0.6s; 
            z-index: 1; 
        }
        .service-card:hover::before { 
            left: 100%; /* Shimmer effect animato */
        }
        .service-card:hover { 
            transform: translateY(-15px) scale(1.02); 
            box-shadow: 0 15px 40px rgba(220,53,69,0.4); 
        }
        .service-card h3 { 
            color: #DC3545; 
            transition: color 0.3s; 
        }
        .service-card:hover h3 { 
            color: #007BFF; 
        }
        footer { 
            background: #333; 
            color: white; 
            text-align: center; 
            padding: 25px; 
            animation: fadeIn 2.5s ease-in; 
        }
        form { 
            max-width: 450px; 
            margin: auto; 
        }
        input, textarea, button { 
            width: 100%; 
            padding: 15px; 
            margin: 10px 0; 
            border: 2px solid #ddd; 
            border-radius: 8px; 
            transition: all 0.3s ease; 
            font-size: 16px; 
        }
        input:focus, textarea:focus { 
            border-color: #DC3545; 
            box-shadow: 0 0 10px rgba(220,53,69,0.3); 
            transform: scale(1.01); 
        }
        button { 
            background: #DC3545; 
            color: white; 
            border: none; 
            cursor: pointer; 
            transition: all 0.4s ease; 
            font-weight: bold; 
        }
        button:hover { 
            background: #C82333; 
            transform: translateY(-2px); 
            box-shadow: 0 5px 15px rgba(220,53,69,0.4); 
        }
        @media (max-width: 768px) { 
            .slogan { font-size: 1.5em; } 
            section { padding: 40px 15px; } 
            .services { grid-template-columns: 1fr; } 
        }
    </style>
</head>
<body>
    <header>
        <img src="cps-logo.png" alt="Logo CPS Telecomunicazioni S.r.l." class="logo"> <!-- Placeholder per il logo allegato -->
        <h1>CPS Telecomunicazioni S.r.l.</h1>
        <p class="slogan">Fili di stelle, connessi all'eterno.</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#chi-siamo">Chi Siamo</a>
        <a href="#servizi">Servizi</a>
        <a href="#partnership">Partnership</a>
        <a href="#contatti">Contatti</a>
    </nav>

    <section id="home" class="hero">
        <h2>Connettiamo l'Italia con Reti del Futuro</h2>
        <p>Specializzati in telecomunicazioni digitali, progettiamo e realizziamo infrastrutture fibra ottica affidabili. Sede a Roma, partner strategici per un'Italia connessa.</p>
    </section>

    <section id="chi-siamo">
        <h2>Chi Siamo</h2>
        <p>CPS Telecomunicazioni S.r.l. è una società italiana con sede a Roma, specializzata nel settore delle telecomunicazioni, in particolare nei lavori di progettazione, installazione, manutenzione e giunzione di reti in fibra ottica. Opera principalmente come partner di grandi operatori delle telecomunicazioni, con un focus su interventi edili e infrastrutturali legati alle comunicazioni digitali. Con un team di 13 esperti e un fatturato in costante crescita, garantiamo soluzioni innovative e reperibilità 24/7.</p>
    </section>

    <section id="servizi">
        <h2>I Nostri Servizi</h2>
        <div class="services">
            <div class="service-card" onclick="alert('Contattaci per una consulenza su progettazione reti!')">
                <h3>Progettazione Reti</h3>
                <p>Pianificazione avanzata di infrastrutture fibra ottica, ottimizzate per performance e scalabilità in contesti urbani e rurali.</p>
            </div>
            <div class="service-card" onclick="alert('Installazione su misura per i tuoi progetti!')">
                <h3>Installazione e Posa</h3>
                <p>Realizzazione precisa di reti FTTH, con interventi edili efficienti e conformi alle normative, minimizzando impatti.</p>
            </div>
            <div class="service-card" onclick="alert('Manutenzione proattiva per continuità totale!')">
                <h3>Manutenzione e Giunzione</h3>
                <p>Servizi di splicing, riparazioni e troubleshooting per mantenere le tue reti ottiche al massimo dell'efficienza.</p>
            </div>
        </div>
    </section>

    <section id="partnership">
        <h2>Le Nostre Partnership</h2>
        <p>System partner di Fastweb da oltre 20 anni, collaboriamo per l'espansione di reti ultraveloci e sostenibili. Il nostro ruolo chiave include progettazione e manutenzione per grandi operatori, garantendo innovazione e affidabilità nelle comunicazioni digitali.</p>
        <ul>
            <li><strong>Fastweb:</strong> Oltre 20 anni di partnership esclusiva – dalla posa cavi alla gestione emergenze.</li>
            <li><strong>Grandi Operatori:</strong> Focus su infrastrutture condivise per banda ultralarga e aree critiche.</li>
        </ul>
    </section>

    <section id="contatti">
        <h2>Contattaci</h2>
        <p>Via Maso Finiguerra 31, 00173 Roma | Tel: +39 06 1234567 | Email: <a href="mailto:info@cpsbianchi.it" style="color: #DC3545; font-weight: bold;">info@cpsbianchi.it</a></p>
        <p>PEC: <a href="mailto:cpstelecomunicazioni@legalmail.it" style="color: #DC3545; font-weight: bold;">cpstelecomunicazioni@legalmail.it</a> | Reperibilità 24/7</p>
        <form id="contactForm">
            <input type="text" id="name" placeholder="Il tuo Nome e Cognome" required>
            <input type="email" id="email" placeholder="La tua Email Aziendale" required>
            <textarea id="message" placeholder="Descrivi il tuo progetto o esigenza..." rows="5" required></textarea>
            <button type="submit">Invia Messaggio</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 CPS Telecomunicazioni S.r.l. | P.IVA 09539361007 | Tutti i diritti riservati. | <a href="#" style="color: #FFD700;">Privacy Policy</a></p>
        <p>Seguici su <a href="https://linkedin.com/company/cps-telecom" style="color: #FFD700;">LinkedIn</a> | Connettiamo visioni, un cavo alla volta.</p>
    </footer>

    <script>
        // Scroll suave con animazione extra
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                target.scrollIntoView({ behavior: 'smooth' });
                target.style.animation = 'slideInUp 1s ease-out'; // Riavvia animazione
            });
        });

        // Form con validazione e animazione feedback
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const message = document.getElementById('message').value;
            if (name && email && message) {
                this.style.animation = 'pulseGlow 0.5s'; // Feedback animato
                setTimeout(() => {
                    alert(`Grazie, ${name}! La tua richiesta è stata inviata con successo. Ti contatteremo entro 24 ore.`);
                    this.reset();
                }, 500);
            } else {
                alert('Si prega di compilare tutti i campi per procedere!');
            }
        });
    </script>
</body>
</html>

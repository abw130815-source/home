<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Aaronia System Bot | Das System für Discord</title>

    <meta
        name="description"
        content="Aaronia System Bot – das moderne System mit hilfreichen Funktionen für deinen Discord-Server."
    >

    <link
        href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap"
        rel="stylesheet"
    >

    <style>

        /* =========================================================
           VARIABLES
        ========================================================= */

        :root {
            --blue: #3b82f6;
            --blue-light: #60a5fa;
            --blue-bright: #93c5fd;
            --blue-dark: #1d4ed8;

            --green: #22c55e;
            --green-light: #4ade80;

            --discord: #5865f2;

            --bg: #02050c;

            --card: rgba(9, 16, 29, 0.78);

            --border: rgba(255, 255, 255, 0.09);

            --text: #f8fafc;
            --muted: #94a3b8;
        }


        /* =========================================================
           RESET
        ========================================================= */

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }


        html {
            scroll-behavior: smooth;
        }


        body {
            min-height: 100vh;

            color: var(--text);

            font-family: "Inter", sans-serif;

            background:
                radial-gradient(
                    circle at 50% -10%,
                    rgba(37, 99, 235, 0.22),
                    transparent 35%
                ),
                radial-gradient(
                    circle at 0% 50%,
                    rgba(59, 130, 246, 0.08),
                    transparent 30%
                ),
                radial-gradient(
                    circle at 100% 80%,
                    rgba(88, 101, 242, 0.10),
                    transparent 30%
                ),
                var(--bg);

            overflow-x: hidden;
        }


        /* =========================================================
           BACKGROUND GRID
        ========================================================= */

        body::before {
            content: "";

            position: fixed;
            inset: 0;

            z-index: -10;

            pointer-events: none;

            background-image:
                linear-gradient(
                    rgba(255,255,255,0.025) 1px,
                    transparent 1px
                ),
                linear-gradient(
                    90deg,
                    rgba(255,255,255,0.025) 1px,
                    transparent 1px
                );

            background-size: 55px 55px;

            mask-image:
                linear-gradient(
                    to bottom,
                    black,
                    rgba(0,0,0,0.5),
                    transparent
                );
        }


        /* =========================================================
           STATIC BLUE GLOWS
        ========================================================= */

        .glow {
            position: fixed;

            border-radius: 50%;

            pointer-events: none;

            z-index: -6;

            filter: blur(120px);
        }


        .glow-one {
            width: 450px;
            height: 450px;

            top: -200px;
            left: -150px;

            background:
                rgba(37,99,235,0.18);
        }


        .glow-two {
            width: 400px;
            height: 400px;

            right: -180px;
            bottom: 5%;

            background:
                rgba(88,101,242,0.12);
        }


        .glow-three {
            width: 300px;
            height: 300px;

            top: 45%;
            left: 45%;

            background:
                rgba(59,130,246,0.055);

            filter: blur(100px);
        }


        /* =========================================================
           LIGHT RAYS
           Langsam + unabhängig von Maus
        ========================================================= */

        .light-rays {
            position: fixed;

            inset: 0;

            pointer-events: none;

            overflow: hidden;

            z-index: -5;
        }


        .ray {
            position: absolute;

            width: 2px;
            height: 150vh;

            top: -25vh;

            background:
                linear-gradient(
                    to bottom,
                    transparent,
                    rgba(96,165,250,0.07),
                    transparent
                );

            transform:
                rotate(25deg);

            opacity: 0.35;

            animation:
                rayMove 14s linear infinite;
        }


        .ray:nth-child(1) {
            left: 15%;
        }


        .ray:nth-child(2) {
            left: 38%;

            animation-delay: -5s;

            opacity: 0.25;
        }


        .ray:nth-child(3) {
            left: 68%;

            animation-delay: -9s;

            opacity: 0.18;
        }


        .ray:nth-child(4) {
            left: 85%;

            animation-delay: -3s;

            opacity: 0.15;
        }


        /* =========================================================
           PARTICLES
           Nur CSS – kein JavaScript
        ========================================================= */

        .particles {
            position: fixed;

            inset: 0;

            pointer-events: none;

            overflow: hidden;

            z-index: -2;
        }


        .particle {
            position: absolute;

            bottom: -10px;

            width: 3px;
            height: 3px;

            border-radius: 50%;

            background:
                var(--blue-light);

            box-shadow:
                0 0 7px
                rgba(59,130,246,0.7);

            opacity: 0;

            animation:
                particleFloat 18s linear infinite;
        }


        .particle:nth-child(1) {
            left: 5%;
            animation-delay: -4s;
        }


        .particle:nth-child(2) {
            left: 14%;
            animation-delay: -8s;
            animation-duration: 22s;
        }


        .particle:nth-child(3) {
            left: 24%;
            animation-delay: -2s;
            animation-duration: 17s;
        }


        .particle:nth-child(4) {
            left: 36%;
            animation-delay: -11s;
            animation-duration: 24s;
        }


        .particle:nth-child(5) {
            left: 48%;
            animation-delay: -5s;
            animation-duration: 19s;
        }


        .particle:nth-child(6) {
            left: 59%;
            animation-delay: -13s;
            animation-duration: 23s;
        }


        .particle:nth-child(7) {
            left: 70%;
            animation-delay: -7s;
            animation-duration: 18s;
        }


        .particle:nth-child(8) {
            left: 82%;
            animation-delay: -15s;
            animation-duration: 21s;
        }


        .particle:nth-child(9) {
            left: 94%;
            animation-delay: -3s;
            animation-duration: 20s;
        }


        /* =========================================================
           HERO
        ========================================================= */

        header {
            min-height: 78vh;

            display: flex;

            align-items: center;
            justify-content: center;

            padding:
                90px 20px 60px;

            text-align: center;

            position: relative;
        }


        .hero {
            max-width: 900px;

            animation:
                heroEnter 0.8s
                cubic-bezier(.16,1,.3,1);
        }


        .badge {
            display: inline-flex;

            align-items: center;

            gap: 9px;

            padding:
                9px 17px;

            margin-bottom:
                28px;

            border:
                1px solid
                rgba(96,165,250,0.28);

            border-radius:
                999px;

            background:
                rgba(59,130,246,0.07);

            color:
                #bfdbfe;

            font-size:
                0.78rem;

            font-weight:
                700;

            letter-spacing:
                1.5px;
        }


        .status-dot {
            width: 8px;
            height: 8px;

            border-radius: 50%;

            background:
                var(--blue-light);

            box-shadow:
                0 0 10px var(--blue);
        }


        h1 {
            font-size:
                clamp(3.4rem, 9vw, 7.5rem);

            line-height:
                0.87;

            font-weight:
                800;

            letter-spacing:
                -7px;

            margin-bottom:
                32px;

            background:
                linear-gradient(
                    135deg,
                    #ffffff 5%,
                    #dbeafe 35%,
                    #60a5fa 65%,
                    #2563eb 100%
                );

            -webkit-background-clip:
                text;

            background-clip:
                text;

            color:
                transparent;

            text-shadow:
                0 0 80px
                rgba(59,130,246,0.13);
        }


        .hero p {
            max-width:
                660px;

            margin:
                auto;

            color:
                var(--muted);

            font-size:
                1.12rem;

            line-height:
                1.85;
        }


        .hero-highlight {
            color:
                white;

            font-weight:
                700;
        }


        /* =========================================================
           SCROLL INDICATOR
           Nur dezentes CSS-Bouncing
        ========================================================= */

        .scroll-indicator {
            position: absolute;

            bottom: 35px;
            left: 50%;

            transform:
                translateX(-50%);

            color:
                rgba(148,163,184,0.55);

            font-size:
                0.72rem;

            letter-spacing:
                2px;

            text-transform:
                uppercase;

            animation:
                scrollFade 3s ease-in-out infinite;
        }


        .scroll-arrow {
            width: 10px;
            height: 10px;

            margin:
                10px auto 0;

            border-right:
                1px solid
                var(--blue-light);

            border-bottom:
                1px solid
                var(--blue-light);

            transform:
                rotate(45deg);

            animation:
                arrowBounce 2s ease-in-out infinite;
        }


        /* =========================================================
           MAIN
        ========================================================= */

        main {
            max-width:
                1050px;

            margin:
                auto;

            padding:
                0 20px 100px;
        }


        .section-header {
            text-align:
                center;

            margin-bottom:
                38px;
        }


        .section-header span {
            color:
                var(--blue-light);

            font-size:
                0.76rem;

            font-weight:
                800;

            letter-spacing:
                2.5px;

            text-transform:
                uppercase;
        }


        .section-header h2 {
            margin-top:
                11px;

            font-size:
                2rem;

            letter-spacing:
                -1px;
        }


        /* =========================================================
           CARDS
           Kein Maus-Tracking
        ========================================================= */

        .hub-grid {
            display:
                grid;

            grid-template-columns:
                repeat(2, 1fr);

            gap:
                22px;
        }


        .hub-card {
            position:
                relative;

            padding:
                31px;

            border:
                1px solid
                var(--border);

            border-radius:
                23px;

            background:
                linear-gradient(
                    145deg,
                    rgba(255,255,255,0.045),
                    rgba(255,255,255,0.008)
                ),
                var(--card);

            backdrop-filter:
                blur(18px);

            -webkit-backdrop-filter:
                blur(18px);

            overflow:
                hidden;

            box-shadow:
                0 15px 50px
                rgba(0,0,0,0.18);

            transition:
                transform 0.25s ease,
                border-color 0.25s ease,
                box-shadow 0.25s ease;
        }


        .hub-card::before {
            content:
                "";

            position:
                absolute;

            width:
                220px;

            height:
                220px;

            top:
                -130px;

            right:
                -130px;

            border-radius:
                50%;

            background:
                var(--blue);

            filter:
                blur(80px);

            opacity:
                0.10;

            transition:
                opacity 0.25s ease;
        }


        .hub-card:hover {
            transform:
                translateY(-7px);

            border-color:
                rgba(59,130,246,0.40);

            box-shadow:
                0 25px 65px
                rgba(0,0,0,0.35);
        }


        .hub-card:hover::before {
            opacity:
                0.20;
        }


        /* =========================================================
           ICON
        ========================================================= */

        .icon {
            width:
                58px;

            height:
                58px;

            display:
                flex;

            align-items:
                center;

            justify-content:
                center;

            margin-bottom:
                22px;

            border-radius:
                17px;

            font-size:
                1.7rem;

            background:
                rgba(59,130,246,0.10);

            border:
                1px solid
                rgba(96,165,250,0.20);
        }


        .card-title {
            font-size:
                1.45rem;

            font-weight:
                700;

            margin-bottom:
                10px;
        }


        .card-desc {
            color:
                var(--muted);

            line-height:
                1.7;

            font-size:
                0.95rem;

            margin-bottom:
                24px;
        }


        /* =========================================================
           SERVER IP
        ========================================================= */

        .ip-box {
            display:
                flex;

            align-items:
                center;

            justify-content:
                space-between;

            gap:
                15px;

            padding:
                13px 15px;

            background:
                rgba(0,0,0,0.30);

            border:
                1px solid
                rgba(255,255,255,0.07);

            border-radius:
                12px;
        }


        .ip {
            color:
                #bfdbfe;

            font-family:
                monospace;

            font-size:
                0.95rem;
        }


        .copy-button {
            border:
                none;

            background:
                linear-gradient(
                    135deg,
                    #60a5fa,
                    #2563eb
                );

            color:
                white;

            padding:
                9px 14px;

            border-radius:
                8px;

            font-weight:
                700;

            cursor:
                pointer;

            transition:
                transform 0.2s ease,
                box-shadow 0.2s ease;
        }


        .copy-button:hover {
            transform:
                scale(1.04);

            box-shadow:
                0 0 25px
                rgba(59,130,246,0.35);
        }


        /* =========================================================
           DISCORD
        ========================================================= */

        .hub-btn {
            display:
                flex;

            align-items:
                center;

            justify-content:
                center;

            gap:
                9px;

            width:
                100%;

            padding:
                14px 18px;

            border-radius:
                11px;

            text-decoration:
                none;

            font-weight:
                700;

            transition:
                transform 0.2s ease,
                box-shadow 0.2s ease;
        }


        .discord-btn {
            background:
                linear-gradient(
                    135deg,
                    #6875ff,
                    #5865f2
                );

            color:
                white;

            box-shadow:
                0 10px 30px
                rgba(88,101,242,0.16);
        }


        .discord-btn:hover {
            transform:
                translateY(-2px);

            box-shadow:
                0 14px 38px
                rgba(88,101,242,0.30);
        }


        /* =========================================================
           INFO
        ========================================================= */

        .info-strip {
            margin-top:
                22px;

            padding:
                20px;

            display:
                flex;

            align-items:
                center;

            justify-content:
                center;

            gap:
                10px;

            text-align:
                center;

            color:
                var(--muted);

            border:
                1px solid
                var(--border);

            border-radius:
                16px;

            background:
                rgba(255,255,255,0.025);

            backdrop-filter:
                blur(12px);

            font-size:
                0.9rem;
        }


        .info-strip strong {
            color:
                white;
        }


        /* =========================================================
           FOOTER
        ========================================================= */

        footer {
            border-top:
                1px solid
                rgba(255,255,255,0.07);

            padding:
                32px 20px;

            text-align:
                center;

            color:
                #64748b;

            font-size:
                0.8rem;
        }


        footer span {
            color:
                #94a3b8;
        }


        /* =========================================================
           ANIMATIONS
        ========================================================= */

        @keyframes heroEnter {

            from {
                opacity:
                    0;

                transform:
                    translateY(25px);
            }

            to {
                opacity:
                    1;

                transform:
                    translateY(0);
            }
        }


        @keyframes rayMove {

            from {
                transform:
                    translateY(-15%)
                    rotate(25deg);
            }

            to {
                transform:
                    translateY(15%)
                    rotate(25deg);
            }
        }


        @keyframes particleFloat {

            0% {
                bottom:
                    -10px;

                opacity:
                    0;

                transform:
                    translateX(0);
            }

            10% {
                opacity:
                    0.55;
            }

            50% {
                opacity:
                    0.25;
            }

            90% {
                opacity:
                    0.55;
            }

            100% {
                bottom:
                    110%;

                opacity:
                    0;

                transform:
                    translateX(60px);
            }
        }


        @keyframes scrollFade {

            0%, 100% {
                opacity:
                    0.45;
            }

            50% {
                opacity:
                    0.8;
            }
        }


        @keyframes arrowBounce {

            0%, 100% {
                transform:
                    rotate(45deg)
                    translate(0,0);
            }

            50% {
                transform:
                    rotate(45deg)
                    translate(3px,3px);
            }
        }


        /* =========================================================
           MOBILE
        ========================================================= */

        @media (max-width: 700px) {

            header {
                min-height:
                    68vh;

                padding:
                    70px 20px 50px;
            }


            h1 {
                letter-spacing:
                    -4px;
            }


            .hero p {
                font-size:
                    1rem;
            }


            .hub-grid {
                grid-template-columns:
                    1fr;
            }


            .hub-card {
                padding:
                    25px;
            }


            .info-strip {
                flex-direction:
                    column;
            }


            .ray {
                opacity:
                    0.2;
            }


            .particle {
                display:
                    none;
            }
        }


        @media (max-width: 430px) {

            .ip-box {
                flex-direction:
                    column;

                align-items:
                    stretch;
            }


            .copy-button {
                width:
                    100%;
            }


            h1 {
                font-size:
                    3.3rem;
            }
        }


        /* =========================================================
           REDUCED MOTION
        ========================================================= */

        @media (prefers-reduced-motion: reduce) {

            *,
            *::before,
            *::after {
                animation:
                    none !important;

                transition:
                    none !important;

                scroll-behavior:
                    auto !important;
            }
        }

    
        
        .top-nav {
            position: absolute; top: 0; left: 0; right: 0; z-index: 20;
            display: flex; align-items: center; justify-content: space-between;
            max-width: 1180px; margin: 0 auto; padding: 24px 26px;
        }
        .brand-mark {
            display: inline-flex; align-items: center; gap: 11px;
            color: #eef2ff; text-decoration: none; font-size: .78rem;
            font-weight: 800; letter-spacing: 2px;
        }
        .brand-symbol {
            display: grid; place-items: center; width: 34px; height: 34px;
            border-radius: 11px; color: white; font-size: 1rem;
            background: linear-gradient(135deg,#8b5cf6,#0891b2);
            box-shadow: 0 6px 22px rgba(124,58,237,.32);
        }
        .nav-cta {
            padding: 10px 16px; border: 1px solid rgba(167,139,250,.24);
            border-radius: 999px; color: #e0e7ff; text-decoration: none;
            font-size: .82rem; font-weight: 700; background: rgba(255,255,255,.045);
            backdrop-filter: blur(12px); transition: .2s ease;
        }
        .nav-cta:hover { border-color: rgba(103,232,249,.55); transform: translateY(-2px); }
        .nav-cta span { color: #67e8f9; margin-left: 5px; }
        @media (max-width: 700px) { .top-nav { padding: 17px 18px; } }

        /* =========================================================
           AARONIA SYSTEM BOT — MODERN VISUAL UPGRADE
        ========================================================= */
        :root {
            --blue: #7c3aed;
            --blue-light: #60a5fa;
            --blue-bright: #c084fc;
            --blue-dark: #4f46e5;
            --card: rgba(13, 16, 35, 0.78);
            --border: rgba(167, 139, 250, 0.17);
            --muted: #a7b0c8;
        }

        body {
            background:
                radial-gradient(ellipse at 50% -15%, rgba(124,58,237,.27), transparent 42%),
                radial-gradient(ellipse at 5% 45%, rgba(6,182,212,.12), transparent 34%),
                radial-gradient(ellipse at 100% 75%, rgba(236,72,153,.11), transparent 32%),
                #050611;
        }

        body::before {
            opacity: .55;
            background-size: 42px 42px;
            mask-image: linear-gradient(to bottom, black, transparent 85%);
        }

        .hero { max-width: 1040px; }
        .badge {
            border-color: rgba(192,132,252,.35);
            background: rgba(124,58,237,.12);
            box-shadow: 0 0 35px rgba(124,58,237,.10), inset 0 0 18px rgba(96,165,250,.05);
            backdrop-filter: blur(14px);
        }
        .status-dot {
            background: #a78bfa;
            box-shadow: 0 0 12px #a78bfa, 0 0 24px rgba(34,211,238,.55);
        }
        h1 {
            font-size: clamp(3.2rem, 9vw, 7.2rem);
            line-height: .94;
            letter-spacing: -5px;
            text-shadow: 0 0 70px rgba(124,58,237,.18);
        }
        .rgb-text {
            display: inline-block;
            background: linear-gradient(90deg, #ff4fd8, #8b5cf6, #38bdf8, #34d399, #facc15, #ff4fd8);
            background-size: 300% 100%;
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            animation: rgbFlow 8s linear infinite;
            filter: drop-shadow(0 0 25px rgba(139,92,246,.22));
        }
        .hero p { max-width: 760px; font-size: 1.12rem; }
        .hero-highlight {
            background: linear-gradient(90deg, #fff, #c4b5fd, #67e8f9, #fff);
            background-size: 220% auto;
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            animation: rgbFlow 10s linear infinite;
        }
        .section-header span {
            background: linear-gradient(90deg, #c084fc, #67e8f9, #f0abfc);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        .section-header h2 {
            font-size: clamp(1.8rem, 4vw, 2.6rem);
            letter-spacing: -1.5px;
        }
        .hub-grid { gap: 24px; }
        .hub-card {
            border-radius: 26px;
            border-color: rgba(167,139,250,.16);
            background:
                linear-gradient(145deg, rgba(255,255,255,.065), rgba(255,255,255,.012)),
                rgba(10,12,29,.82);
            box-shadow: 0 22px 70px rgba(0,0,0,.28), inset 0 1px 0 rgba(255,255,255,.045);
        }
        .hub-card:hover {
            border-color: rgba(103,232,249,.42);
            box-shadow: 0 28px 80px rgba(0,0,0,.4), 0 0 38px rgba(124,58,237,.12);
        }
        .hub-card::before {
            background: linear-gradient(135deg, #8b5cf6, #06b6d4, #ec4899);
            opacity: .14;
        }
        .icon {
            border-radius: 19px;
            background: linear-gradient(145deg, rgba(139,92,246,.2), rgba(6,182,212,.09));
            border-color: rgba(167,139,250,.25);
            box-shadow: inset 0 1px 0 rgba(255,255,255,.08), 0 10px 30px rgba(124,58,237,.08);
        }
        .card-title { letter-spacing: -.4px; }
        .hub-btn {
            border: 1px solid rgba(255,255,255,.12);
            border-radius: 13px;
            box-shadow: 0 12px 32px rgba(88,65,190,.2);
        }
        .discord-btn {
            background: linear-gradient(105deg, #7c3aed, #4f46e5 45%, #0891b2);
            background-size: 180% 100%;
            transition: background-position .35s ease, transform .2s ease, box-shadow .2s ease;
        }
        .discord-btn:hover {
            background-position: 100% 0;
            box-shadow: 0 16px 42px rgba(99,102,241,.32);
        }
        .info-strip {
            border-radius: 18px;
            border-color: rgba(167,139,250,.17);
            background: linear-gradient(110deg, rgba(124,58,237,.09), rgba(6,182,212,.05), rgba(236,72,153,.06));
        }
        .info-strip strong {
            background: linear-gradient(90deg, #fff, #c4b5fd, #67e8f9);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        footer { border-color: rgba(167,139,250,.12); }
        footer a {
            color: #a5b4fc;
            text-decoration: none;
            transition: color .2s ease;
        }
        footer a:hover { color: #67e8f9; }

        @keyframes rgbFlow {
            from { background-position: 0% 50%; }
            to { background-position: 300% 50%; }
        }
        @media (max-width: 700px) {
            h1 { letter-spacing: -3px; }
        }
        @media (prefers-reduced-motion: reduce) {
            .rgb-text, .hero-highlight { animation: none; }
        }

    </style>
</head>


<body>

    <nav class="top-nav" aria-label="Hauptnavigation">
        <a class="brand-mark" href="#top"><span class="brand-symbol">A</span><span>AARONIA</span></a>
        <a class="nav-cta" href="https://sybot.aaroniamc.de/" target="_blank" rel="noopener noreferrer">System öffnen <span>↗</span></a>
    </nav>



    <!-- =========================================================
         BACKGROUND
    ========================================================= -->

    <div class="glow glow-one"></div>

    <div class="glow glow-two"></div>

    <div class="glow glow-three"></div>


    <div class="light-rays">

        <div class="ray"></div>
        <div class="ray"></div>
        <div class="ray"></div>
        <div class="ray"></div>

    </div>


    <div class="particles">

        <div class="particle"></div>
        <div class="particle"></div>
        <div class="particle"></div>
        <div class="particle"></div>
        <div class="particle"></div>
        <div class="particle"></div>
        <div class="particle"></div>
        <div class="particle"></div>
        <div class="particle"></div>

    </div>


    <!-- =========================================================
         HERO
    ========================================================= -->

    <div id="top"></div>
    <header>

        <div class="hero">

            <div class="badge"><span class="status-dot"></span> DAS SYSTEM FÜR DEINEN DISCORD</div>
            <h1>AARONIA<br><span class="rgb-text">SYSTEM BOT</span></h1>
            <p>Mehr Überblick. Mehr Möglichkeiten. Weniger Aufwand.<br>
            <span class="hero-highlight">Aaronia System Bot</span> unterstützt deinen Discord-Server mit durchdachten Funktionen und einem modernen System – entwickelt für Communities, die mehr erwarten.</p>

        </div>


        <div class="scroll-indicator">

            ENTDECKEN

            <div class="scroll-arrow"></div>

        </div>

    </header>


    <!-- =========================================================
         MAIN
    ========================================================= -->

    <main>


        <div class="section-header">

            <span>
                SMART. MODERN. AARONIA.
            </span>

            <h2>
                Alles für deinen Discord
            </h2>

        </div>


        <div class="hub-grid">


            <!-- SERVER -->

            <div class="hub-card">

                <div class="icon">
                    🤖
                </div>


                <div class="card-title">
                    Dein Server. Ein starkes System.
                </div>


                <div class="card-desc">

                    Bring Struktur und praktische Funktionen auf deinen Discord-Server.
                    Aaronia System Bot verbindet ein modernes Auftreten
                    mit hilfreichen Möglichkeiten für deinen Alltag
                    als Community- oder Server-Team.

                </div>


                <a class="hub-btn discord-btn" href="https://sybot.aaroniamc.de/" target="_blank" rel="noopener noreferrer">Aaronia System Bot jetzt entdecken <span>→</span></a>

            </div>


            <!-- DISCORD -->

            <div class="hub-card">

                <div class="icon">
                    💬
                </div>


                <div class="card-title">
                    Die System-Website öffnen
                </div>


                <div class="card-desc">

                    Entdecke das System, informiere dich über die
                    verfügbaren Funktionen und finde heraus,
                    wie Aaronia System Bot zu deiner Community passt.

                </div>


                <a
                    href="https://sybot.aaroniamc.de/"
                    target="_blank"
                    rel="noopener noreferrer"
                    class="hub-btn discord-btn"
                >

                    Zur Aaronia System Bot-Webseite

                    <span>
                        →
                    </span>

                </a>

            </div>


        </div>


        <div class="info-strip">

            ✦

            <span>

                <strong>
                    Aaronia System Bot
                </strong>

                — Dein Discord. Dein System. Aaronia.

            </span>

        </div>


    </main>


    <!-- =========================================================
         FOOTER
    ========================================================= -->

    <footer>
        &copy; 2026 <span>Aaronia System Bot</span> · Alle Rechte vorbehalten.
        <span class="footer-separator">·</span>
        <a href="https://impressum.aaroniamc.de/" target="_blank" rel="noopener noreferrer">Impressum</a>
    </footer>


    <!-- =========================================================
         JAVASCRIPT
         WEITERLEITUNG ZUR SYBOT-WEBSEITE
    ========================================================= -->
</body>
</html>

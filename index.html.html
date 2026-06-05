<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Roleta da Pizza — Bella Napoli</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Playfair+Display:ital,wght@0,700;0,900;1,700&family=DM+Sans:wght@400;500;700&display=swap" rel="stylesheet">
<style>
  :root {
    --tomato: #c1272d;
    --tomato-deep: #8b1a1f;
    --tomato-bright: #e63946;
    --cheese: #f4c430;
    --cheese-dark: #d4a017;
    --basil: #4a7c3a;
    --basil-dark: #2d4f23;
    --italy-green: #008c45;
    --crust: #c19a5b;
    --crust-dark: #8b5a2b;
    --crust-burnt: #5c3317;
    --dough: #f5e6c8;
    --wood: #6b4423;
    --wood-light: #8b5a3c;
    --cream: #fff8e7;
  }

  * { box-sizing: border-box; margin: 0; padding: 0; }

  html, body {
    min-height: 100vh;
    font-family: 'DM Sans', sans-serif;
    color: var(--cream);
    overflow-x: hidden;
  }

  /* MESA DE MADEIRA + TOALHA XADREZ */
  body {
    background-color: var(--wood);
    background-image:
      /* Toalha xadrez vermelha e branca (parcial nas bordas) */
      repeating-linear-gradient(0deg,
        transparent 0px, transparent 40px,
        rgba(193, 39, 45, 0.2) 40px, rgba(193, 39, 45, 0.2) 80px),
      repeating-linear-gradient(90deg,
        transparent 0px, transparent 40px,
        rgba(193, 39, 45, 0.2) 40px, rgba(193, 39, 45, 0.2) 80px),
      /* Grãos de madeira */
      repeating-linear-gradient(90deg,
        rgba(0, 0, 0, 0.1) 0px, transparent 2px, transparent 8px, rgba(0, 0, 0, 0.1) 10px),
      radial-gradient(ellipse at center, var(--wood-light) 0%, var(--wood) 60%, var(--crust-burnt) 100%);
    background-attachment: fixed;
    padding: 30px 20px 60px;
    position: relative;
  }

  /* Grão sobreposto */
  body::after {
    content: '';
    position: fixed;
    inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.5'/%3E%3C/svg%3E");
    opacity: 0.15;
    pointer-events: none;
    z-index: 1;
    mix-blend-mode: multiply;
  }

  .container {
    position: relative;
    z-index: 5;
    max-width: 1100px;
    margin: 0 auto;
    text-align: center;
  }

  /* ============ INGREDIENTES FLUTUANTES 3D ============ */
  .floating-ingredients {
    position: fixed;
    inset: 0;
    pointer-events: none;
    z-index: 2;
    overflow: hidden;
  }

  .float-item {
    position: absolute;
    font-size: 40px;
    filter: drop-shadow(0 8px 12px rgba(0, 0, 0, 0.4));
    animation: float3d 8s ease-in-out infinite;
  }

  @keyframes float3d {
    0%, 100% { transform: translateY(0) rotateZ(0) rotateY(0); }
    25% { transform: translateY(-30px) rotateZ(15deg) rotateY(180deg); }
    50% { transform: translateY(-10px) rotateZ(-10deg) rotateY(360deg); }
    75% { transform: translateY(-40px) rotateZ(8deg) rotateY(180deg); }
  }

  /* ============ CABEÇALHO PIZZARIA ============ */
  header { 
    margin-bottom: 20px;
    position: relative;
  }

  .logo-wrap {
    display: inline-flex;
    align-items: center;
    gap: 20px;
    padding: 18px 36px;
    background: linear-gradient(135deg, #fff8e7, #f5e6c8);
    border: 4px solid var(--crust-dark);
    border-radius: 50px;
    box-shadow:
      0 12px 0 var(--crust-burnt),
      0 20px 40px rgba(0, 0, 0, 0.5),
      inset 0 -4px 8px rgba(139, 90, 43, 0.2);
    transform: perspective(800px) rotateX(5deg);
    position: relative;
  }

  /* Listras da bandeira italiana */
  .logo-wrap::before {
    content: '';
    position: absolute;
    top: -4px;
    left: -4px;
    width: 12px;
    height: calc(100% + 8px);
    background: linear-gradient(to bottom, var(--italy-green), var(--cream), var(--tomato));
    border-radius: 50px 0 0 50px;
  }

  .logo-wrap::after {
    content: '';
    position: absolute;
    top: -4px;
    right: -4px;
    width: 12px;
    height: calc(100% + 8px);
    background: linear-gradient(to bottom, var(--italy-green), var(--cream), var(--tomato));
    border-radius: 0 50px 50px 0;
  }

  .logo-icon {
    width: 64px;
    height: 64px;
    flex-shrink: 0;
  }

  .logo-text {
    text-align: left;
  }

  .logo-text .tagline-top {
    font-family: 'Pacifico', cursive;
    font-size: 14px;
    color: var(--italy-green);
    margin-bottom: -2px;
  }

  .logo-text .brand {
    font-family: 'Playfair Display', serif;
    font-size: 32px;
    font-weight: 900;
    font-style: italic;
    color: var(--tomato-deep);
    letter-spacing: 1px;
    line-height: 1;
  }

  .logo-text .tagline-bottom {
    font-size: 10px;
    font-weight: 700;
    color: var(--crust-burnt);
    letter-spacing: 3px;
    text-transform: uppercase;
    margin-top: 4px;
  }

  h1 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(40px, 6vw, 64px);
    font-weight: 900;
    margin-top: 24px;
    color: var(--cream);
    text-shadow:
      3px 3px 0 var(--tomato-deep),
      6px 6px 0 var(--crust-burnt),
      6px 6px 20px rgba(0, 0, 0, 0.5);
    letter-spacing: 1px;
    line-height: 1;
  }

  h1 .accent {
    font-family: 'Pacifico', cursive;
    color: var(--cheese);
    font-weight: 400;
    font-style: normal;
    text-shadow:
      3px 3px 0 var(--tomato-deep),
      6px 6px 0 var(--crust-burnt);
    display: inline-block;
    transform: rotate(-5deg);
  }

  .subtitle {
    font-family: 'Pacifico', cursive;
    font-size: 22px;
    color: var(--cheese);
    margin-top: 8px;
    text-shadow: 2px 2px 0 var(--tomato-deep), 4px 4px 8px rgba(0, 0, 0, 0.5);
  }

  .italian-tag {
    display: inline-block;
    margin-top: 8px;
    padding: 4px 16px;
    background: var(--cream);
    color: var(--tomato-deep);
    font-family: 'Pacifico', cursive;
    font-size: 14px;
    border-radius: 20px;
    transform: rotate(-2deg);
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
  }

  /* ============ ROLETA 3D PIZZA ============ */
  .roulette-stage {
    position: relative;
    width: 100%;
    max-width: 580px;
    aspect-ratio: 1;
    margin: 40px auto;
    perspective: 1500px;
  }

  /* Sombra de pizza projetada na mesa */
  .pizza-shadow {
    position: absolute;
    bottom: -30px;
    left: 50%;
    transform: translateX(-50%);
    width: 90%;
    height: 40px;
    background: radial-gradient(ellipse, rgba(0, 0, 0, 0.6) 0%, transparent 70%);
    filter: blur(15px);
    z-index: 0;
  }

  /* Forma de pizza (a "tábua" embaixo) */
  .pizza-board {
    position: absolute;
    inset: -25px;
    border-radius: 50%;
    background:
      radial-gradient(circle at 30% 30%, #d4a574, #a87b4a 50%, #6b4423 100%);
    box-shadow:
      0 20px 40px rgba(0, 0, 0, 0.6),
      inset 0 0 30px rgba(0, 0, 0, 0.4),
      inset 6px 6px 12px rgba(255, 255, 255, 0.15);
    transform: rotateX(8deg);
  }

  /* Anéis da tábua de madeira */
  .pizza-board::before {
    content: '';
    position: absolute;
    inset: 8px;
    border-radius: 50%;
    border: 2px dashed rgba(0, 0, 0, 0.15);
  }

  .pizza-board::after {
    content: '';
    position: absolute;
    inset: 16px;
    border-radius: 50%;
    border: 1px solid rgba(0, 0, 0, 0.1);
  }

  /* Crosta da pizza (3D com volume) */
  .pizza-crust {
    position: absolute;
    inset: 5px;
    border-radius: 50%;
    background:
      radial-gradient(circle at 35% 35%, 
        #e8b87c 0%, 
        var(--crust) 20%, 
        var(--crust-dark) 65%, 
        var(--crust-burnt) 100%);
    box-shadow:
      inset 0 0 0 4px var(--crust-burnt),
      inset 0 -10px 20px rgba(0, 0, 0, 0.3),
      inset 6px 6px 16px rgba(255, 220, 150, 0.3),
      0 8px 20px rgba(0, 0, 0, 0.4);
    transform: rotateX(8deg);
  }

  /* Bolhas/manchas queimadas na crosta */
  .pizza-crust::before {
    content: '';
    position: absolute;
    inset: 0;
    border-radius: 50%;
    background-image:
      radial-gradient(circle at 15% 50%, rgba(92, 51, 23, 0.6) 0%, transparent 3%),
      radial-gradient(circle at 85% 30%, rgba(92, 51, 23, 0.6) 0%, transparent 2%),
      radial-gradient(circle at 50% 90%, rgba(92, 51, 23, 0.6) 0%, transparent 3%),
      radial-gradient(circle at 20% 20%, rgba(92, 51, 23, 0.4) 0%, transparent 2%),
      radial-gradient(circle at 80% 75%, rgba(92, 51, 23, 0.4) 0%, transparent 2%);
  }

  /* A roleta giratória (pizza real) */
  .wheel-wrap {
    position: absolute;
    inset: 35px;
    border-radius: 50%;
    overflow: hidden;
    box-shadow:
      inset 0 0 0 3px var(--crust-burnt),
      inset 0 0 30px rgba(0, 0, 0, 0.4),
      0 10px 30px rgba(0, 0, 0, 0.5);
    transform: rotateX(8deg);
  }

  #wheel {
    width: 100%;
    height: 100%;
    display: block;
    transition: transform 6.5s cubic-bezier(0.17, 0.67, 0.21, 1);
  }

  /* CENTRO: queijo derretido + vapor */
  .wheel-center {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 100px;
    height: 100px;
    border-radius: 50%;
    background: 
      radial-gradient(circle at 35% 35%, #fff5cc, var(--cheese) 40%, var(--cheese-dark) 90%);
    display: flex;
    align-items: center;
    justify-content: center;
    box-shadow:
      0 0 0 4px var(--crust-burnt),
      0 0 0 8px var(--cheese),
      0 0 0 11px var(--crust-burnt),
      0 12px 25px rgba(0, 0, 0, 0.5),
      inset 4px 4px 10px rgba(255, 255, 255, 0.5),
      inset -4px -4px 10px rgba(139, 90, 43, 0.4);
    z-index: 6;
    font-size: 42px;
  }

  /* Vapor saindo do centro */
  .steam {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 100px;
    height: 100px;
    z-index: 5;
    pointer-events: none;
  }

  .steam-puff {
    position: absolute;
    bottom: 50%;
    left: 50%;
    width: 20px;
    height: 20px;
    background: radial-gradient(circle, rgba(255, 255, 255, 0.7), transparent 70%);
    border-radius: 50%;
    animation: steam-rise 3s ease-in infinite;
    opacity: 0;
  }

  .steam-puff:nth-child(1) { animation-delay: 0s; left: 30%; }
  .steam-puff:nth-child(2) { animation-delay: 1s; left: 50%; }
  .steam-puff:nth-child(3) { animation-delay: 2s; left: 70%; }

  @keyframes steam-rise {
    0% { transform: translate(-50%, 0) scale(0.5); opacity: 0; }
    30% { opacity: 0.8; }
    100% { transform: translate(-50%, -150px) scale(2.5); opacity: 0; }
  }

  /* PONTEIRO: Cortador de pizza */
  .pointer {
    position: absolute;
    top: -25px;
    left: 50%;
    transform: translateX(-50%);
    width: 80px;
    height: 110px;
    z-index: 10;
    filter: drop-shadow(0 10px 15px rgba(0, 0, 0, 0.7));
    animation: pointer-bob 2s ease-in-out infinite;
  }

  @keyframes pointer-bob {
    0%, 100% { transform: translateX(-50%) translateY(0); }
    50% { transform: translateX(-50%) translateY(-4px); }
  }

  .pointer svg {
    width: 100%;
    height: 100%;
  }

  /* ============ BOTÃO GIRAR ============ */
  .spin-btn {
    margin-top: 50px;
    background: linear-gradient(180deg, var(--tomato-bright) 0%, var(--tomato) 50%, var(--tomato-deep) 100%);
    color: var(--cream);
    border: 4px solid var(--crust-burnt);
    padding: 22px 70px;
    font-family: 'Playfair Display', serif;
    font-size: 22px;
    font-weight: 900;
    font-style: italic;
    letter-spacing: 2px;
    text-transform: uppercase;
    border-radius: 60px;
    cursor: pointer;
    position: relative;
    transition: all 0.3s;
    box-shadow:
      0 8px 0 var(--crust-burnt),
      0 12px 30px rgba(0, 0, 0, 0.5),
      inset 0 4px 8px rgba(255, 255, 255, 0.3),
      inset 0 -4px 8px rgba(0, 0, 0, 0.3);
    text-shadow: 2px 2px 0 var(--tomato-deep), 0 0 12px rgba(0, 0, 0, 0.5);
  }

  .spin-btn:hover:not(:disabled) {
    transform: translateY(-2px);
    box-shadow:
      0 10px 0 var(--crust-burnt),
      0 16px 40px rgba(0, 0, 0, 0.6),
      inset 0 4px 8px rgba(255, 255, 255, 0.3),
      inset 0 -4px 8px rgba(0, 0, 0, 0.3);
  }

  .spin-btn:active:not(:disabled) {
    transform: translateY(6px);
    box-shadow:
      0 2px 0 var(--crust-burnt),
      0 6px 15px rgba(0, 0, 0, 0.4),
      inset 0 4px 8px rgba(255, 255, 255, 0.3),
      inset 0 -4px 8px rgba(0, 0, 0, 0.3);
  }

  .spin-btn:disabled { opacity: 0.6; cursor: not-allowed; }

  .spin-btn .pizza-emoji {
    display: inline-block;
    animation: spin-emoji 1s linear infinite;
    margin-right: 8px;
  }

  @keyframes spin-emoji {
    to { transform: rotate(360deg); }
  }

  /* ============ MENU DE PRÊMIOS (estilo cardápio) ============ */
  .prizes-menu {
    max-width: 720px;
    margin: 60px auto 0;
    padding: 36px 28px 28px;
    background: 
      repeating-linear-gradient(0deg,
        var(--cream) 0px, var(--cream) 30px,
        rgba(193, 39, 45, 0.05) 30px, rgba(193, 39, 45, 0.05) 31px);
    border: 6px double var(--tomato-deep);
    border-radius: 4px;
    color: var(--crust-burnt);
    text-align: left;
    box-shadow: 0 20px 50px rgba(0, 0, 0, 0.5);
    transform: rotate(-1deg);
    position: relative;
  }

  .prizes-menu::before {
    content: 'CARDÁPIO DE PRÊMIOS';
    position: absolute;
    top: -16px;
    left: 50%;
    transform: translateX(-50%);
    background: var(--tomato-deep);
    color: var(--cream);
    padding: 6px 24px;
    font-family: 'Playfair Display', serif;
    font-weight: 900;
    letter-spacing: 4px;
    font-size: 13px;
    border-radius: 20px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
  }

  .menu-title {
    font-family: 'Pacifico', cursive;
    font-size: 28px;
    color: var(--tomato-deep);
    text-align: center;
    margin: 8px 0 24px;
  }

  .prize-row {
    display: flex;
    align-items: center;
    gap: 14px;
    padding: 10px 0;
    font-family: 'Playfair Display', serif;
    border-bottom: 2px dotted rgba(139, 51, 23, 0.3);
  }

  .prize-row:last-child { border-bottom: none; }

  .prize-row .emoji {
    font-size: 26px;
    width: 40px;
    text-align: center;
  }

  .prize-row .nome {
    font-weight: 700;
    font-size: 16px;
    flex: 1;
  }

  .prize-row .dots {
    flex: 1;
    border-bottom: 2px dotted var(--crust-dark);
    margin: 0 8px;
    height: 12px;
  }

  .prize-row .chance {
    font-weight: 900;
    color: var(--tomato-deep);
    font-size: 15px;
  }

  .prize-row.special {
    background: linear-gradient(90deg, transparent, rgba(244, 196, 48, 0.3), transparent);
    border-radius: 4px;
    padding: 12px 8px;
    margin: 8px 0;
  }

  .prize-row.special .nome {
    color: var(--tomato-deep);
    font-style: italic;
  }

  /* ============ MODAL DE VITÓRIA ============ */
  .modal-overlay {
    position: fixed;
    inset: 0;
    background: rgba(91, 51, 23, 0.7);
    backdrop-filter: blur(10px);
    display: none;
    align-items: center;
    justify-content: center;
    z-index: 1000;
    opacity: 0;
    transition: opacity 0.4s;
  }

  .modal-overlay.active { display: flex; opacity: 1; }

  .modal-content {
    position: relative;
    background: 
      repeating-linear-gradient(0deg,
        var(--cream) 0px, var(--cream) 25px,
        rgba(193, 39, 45, 0.04) 25px, rgba(193, 39, 45, 0.04) 26px);
    border: 8px double var(--tomato-deep);
    border-radius: 8px;
    padding: 50px 60px;
    text-align: center;
    max-width: 520px;
    width: 90%;
    transform: scale(0.5) rotate(-15deg);
    transition: transform 0.6s cubic-bezier(0.17, 0.84, 0.44, 1);
    box-shadow: 0 30px 80px rgba(0, 0, 0, 0.7);
    color: var(--crust-burnt);
    overflow: hidden;
  }

  .modal-overlay.active .modal-content {
    transform: scale(1) rotate(0);
  }

  /* Tomate na quina */
  .modal-content::before {
    content: '🍅';
    position: absolute;
    top: -25px;
    left: -25px;
    font-size: 60px;
    transform: rotate(-20deg);
    filter: drop-shadow(0 8px 12px rgba(0, 0, 0, 0.4));
  }

  .modal-content::after {
    content: '🌿';
    position: absolute;
    bottom: -10px;
    right: -10px;
    font-size: 50px;
    transform: rotate(20deg);
    filter: drop-shadow(0 8px 12px rgba(0, 0, 0, 0.4));
  }

  .modal-content.loss {
    background: linear-gradient(135deg, #e8d5b7, #d4b896);
    border-color: var(--crust-burnt);
  }

  .modal-content.loss::before { content: '🥺'; }
  .modal-content.loss::after { content: ''; }

  /* MEGA: fundo dourado brilhante */
  .modal-content.mega {
    background: 
      radial-gradient(circle at 30% 30%, #fff5cc, var(--cheese) 60%, var(--cheese-dark) 100%);
    border-color: var(--tomato-deep);
    animation: mega-shine 1.2s ease-in-out infinite;
  }

  @keyframes mega-shine {
    0%, 100% { box-shadow: 0 30px 80px rgba(0,0,0,0.7), 0 0 80px var(--cheese); }
    50% { box-shadow: 0 30px 80px rgba(0,0,0,0.7), 0 0 150px var(--cheese), 0 0 200px var(--tomato); }
  }

  .win-label {
    font-family: 'Pacifico', cursive;
    font-size: 22px;
    color: var(--italy-green);
    margin-bottom: 8px;
  }

  .win-icon {
    font-size: 110px;
    margin: 16px 0 8px;
    display: inline-block;
    animation: bounce-icon 0.8s ease infinite alternate;
    filter: drop-shadow(0 12px 20px rgba(0, 0, 0, 0.4));
  }

  @keyframes bounce-icon {
    from { transform: translateY(0) rotate(-10deg) scale(1); }
    to { transform: translateY(-20px) rotate(10deg) scale(1.15); }
  }

  .win-title {
    font-family: 'Playfair Display', serif;
    font-size: 38px;
    font-weight: 900;
    font-style: italic;
    color: var(--tomato-deep);
    margin-bottom: 12px;
    line-height: 1.1;
  }

  .modal-content.mega .win-title {
    font-size: 44px;
    background: linear-gradient(90deg, var(--tomato-deep), var(--italy-green), var(--tomato-deep));
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
    background-size: 200% 100%;
    animation: text-shimmer 2s linear infinite;
  }

  @keyframes text-shimmer { to { background-position: 200% 0; } }

  .win-message {
    font-size: 17px;
    color: var(--crust-burnt);
    margin-bottom: 28px;
    font-family: 'DM Sans', sans-serif;
  }

  .modal-btn {
    background: linear-gradient(180deg, var(--tomato-bright), var(--tomato-deep));
    color: var(--cream);
    border: 3px solid var(--crust-burnt);
    padding: 14px 44px;
    font-family: 'Playfair Display', serif;
    font-size: 16px;
    font-weight: 900;
    font-style: italic;
    letter-spacing: 2px;
    text-transform: uppercase;
    border-radius: 40px;
    cursor: pointer;
    transition: all 0.2s;
    box-shadow: 0 6px 0 var(--crust-burnt), 0 10px 20px rgba(0, 0, 0, 0.4);
  }

  .modal-btn:hover {
    transform: translateY(-2px);
    box-shadow: 0 8px 0 var(--crust-burnt), 0 14px 25px rgba(0, 0, 0, 0.5);
  }
  .modal-btn:active {
    transform: translateY(4px);
    box-shadow: 0 2px 0 var(--crust-burnt), 0 4px 10px rgba(0, 0, 0, 0.4);
  }

  /* ============ CONFETE / INGREDIENTES CAINDO ============ */
  .confetti {
    position: fixed;
    top: -40px;
    z-index: 999;
    pointer-events: none;
    will-change: transform;
    font-size: 26px;
    filter: drop-shadow(0 4px 6px rgba(0, 0, 0, 0.4));
  }

  .firework {
    position: fixed;
    pointer-events: none;
    z-index: 998;
  }

  footer {
    margin-top: 60px;
    font-family: 'Pacifico', cursive;
    font-size: 16px;
    color: var(--cream);
    text-shadow: 2px 2px 0 var(--tomato-deep), 4px 4px 8px rgba(0, 0, 0, 0.5);
  }

  @media (max-width: 600px) {
    .roulette-stage { max-width: 92vw; }
    .modal-content { padding: 40px 30px; }
    .win-title { font-size: 30px; }
    .modal-content.mega .win-title { font-size: 32px; }
    .spin-btn { padding: 18px 50px; font-size: 18px; letter-spacing: 1px; }
    .prizes-menu { padding: 30px 18px 22px; }
    .prize-row .nome { font-size: 14px; }
    .float-item { font-size: 30px; }
  }
</style>
</head>
<body>

<!-- INGREDIENTES FLUTUANDO -->
<div class="floating-ingredients" id="floaters"></div>

<div class="container">

  <header>
    <div class="logo-wrap">
      <!-- Logo Pizza estilizada -->
      <svg class="logo-icon" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <radialGradient id="pizzaG" cx="35%" cy="35%">
            <stop offset="0%" stop-color="#fff5cc"/>
            <stop offset="50%" stop-color="#f4c430"/>
            <stop offset="100%" stop-color="#d4a017"/>
          </radialGradient>
          <radialGradient id="crustG" cx="35%" cy="35%">
            <stop offset="0%" stop-color="#e8b87c"/>
            <stop offset="100%" stop-color="#8b5a2b"/>
          </radialGradient>
        </defs>
        <!-- Crosta -->
        <circle cx="50" cy="50" r="45" fill="url(#crustG)" stroke="#5c3317" stroke-width="2"/>
        <!-- Queijo -->
        <circle cx="50" cy="50" r="36" fill="url(#pizzaG)"/>
        <!-- Pepperoni -->
        <circle cx="38" cy="40" r="6" fill="#c1272d" stroke="#8b1a1f" stroke-width="0.5"/>
        <circle cx="62" cy="42" r="6" fill="#c1272d" stroke="#8b1a1f" stroke-width="0.5"/>
        <circle cx="45" cy="62" r="6" fill="#c1272d" stroke="#8b1a1f" stroke-width="0.5"/>
        <circle cx="64" cy="64" r="5" fill="#c1272d" stroke="#8b1a1f" stroke-width="0.5"/>
        <!-- Manjericão -->
        <ellipse cx="50" cy="50" rx="3" ry="6" fill="#4a7c3a" transform="rotate(45 50 50)"/>
        <ellipse cx="55" cy="35" rx="2" ry="4" fill="#2d4f23" transform="rotate(-30 55 35)"/>
        <!-- Azeitona -->
        <circle cx="35" cy="55" r="2.5" fill="#2d2d2d"/>
        <circle cx="55" cy="70" r="2.5" fill="#2d2d2d"/>
      </svg>
      <div class="logo-text">
        <div class="tagline-top">Pizzaria</div>
        <div class="brand">Bella Napoli</div>
        <div class="tagline-bottom">Forno a lenha • Desde sempre</div>
      </div>
    </div>

    <h1>Roleta da <span class="accent">Pizza</span></h1>
    <p class="subtitle">Mamma mia, que sorte!</p>
    <div class="italian-tag">Buona fortuna! 🇮🇹</div>
  </header>

  <div class="roulette-stage" id="stage">
    <div class="pizza-shadow"></div>
    <div class="pizza-board"></div>
    <div class="pizza-crust"></div>

    <div class="pointer">
      <!-- Cortador de pizza -->
      <svg viewBox="0 0 80 110" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <linearGradient id="handleG" x1="0%" y1="0%" x2="0%" y2="100%">
            <stop offset="0%" stop-color="#8b5a2b"/>
            <stop offset="100%" stop-color="#5c3317"/>
          </linearGradient>
          <radialGradient id="bladeG" cx="40%" cy="40%">
            <stop offset="0%" stop-color="#f5f5f5"/>
            <stop offset="60%" stop-color="#c0c0c0"/>
            <stop offset="100%" stop-color="#707070"/>
          </radialGradient>
        </defs>
        <!-- Cabo do cortador -->
        <rect x="35" y="0" width="10" height="55" rx="3" fill="url(#handleG)" stroke="#3a1f0d" stroke-width="1.5"/>
        <rect x="32" y="0" width="16" height="8" rx="2" fill="#5c3317" stroke="#3a1f0d" stroke-width="1.5"/>
        <!-- Suporte -->
        <line x1="40" y1="55" x2="40" y2="70" stroke="#3a1f0d" stroke-width="3"/>
        <!-- Lâmina circular -->
        <circle cx="40" cy="85" r="22" fill="url(#bladeG)" stroke="#3a1f0d" stroke-width="2"/>
        <circle cx="40" cy="85" r="4" fill="#3a1f0d"/>
        <!-- Brilho -->
        <ellipse cx="32" cy="78" rx="4" ry="6" fill="#ffffff" opacity="0.7"/>
      </svg>
    </div>

    <div class="wheel-wrap">
      <canvas id="wheel" width="600" height="600"></canvas>
    </div>

    <div class="steam">
      <div class="steam-puff"></div>
      <div class="steam-puff"></div>
      <div class="steam-puff"></div>
    </div>

    <div class="wheel-center">🍕</div>
  </div>

  <button class="spin-btn" id="spinBtn">
    <span class="pizza-emoji">🍕</span>Girar a Pizza!
  </button>

  <div class="prizes-menu">
    <h2 class="menu-title">~ Os prêmios da casa ~</h2>
    <div class="prize-row"><span class="emoji">🍕</span><span class="nome">Pizza Margherita Grátis</span><span class="dots"></span><span class="chance">10%</span></div>
    <div class="prize-row"><span class="emoji">🥤</span><span class="nome">Refrigerante 2L</span><span class="dots"></span><span class="chance">10%</span></div>
    <div class="prize-row"><span class="emoji">🧀</span><span class="nome">Borda Recheada Grátis</span><span class="dots"></span><span class="chance">10%</span></div>
    <div class="prize-row"><span class="emoji">💸</span><span class="nome">50% OFF na próxima</span><span class="dots"></span><span class="chance">10%</span></div>
    <div class="prize-row"><span class="emoji">🍰</span><span class="nome">Sobremesa Grátis</span><span class="dots"></span><span class="chance">10%</span></div>
    <div class="prize-row"><span class="emoji">🍕</span><span class="nome">Combo Família Premium</span><span class="dots"></span><span class="chance">9%</span></div>
    <div class="prize-row"><span class="emoji">😢</span><span class="nome">Tente outra vez (×3)</span><span class="dots"></span><span class="chance">30%</span></div>
    <div class="prize-row special"><span class="emoji">👑</span><span class="nome">Pizza Grátis por 1 ANO!</span><span class="dots"></span><span class="chance">1%</span></div>
  </div>

  <footer>~ Buon appetito ~</footer>
</div>

<!-- Modal de Vitória -->
<div class="modal-overlay" id="modal">
  <div class="modal-content" id="modalContent">
    <div class="modal-inner">
      <div class="win-label" id="winLabel">Complimenti!</div>
      <div class="win-icon" id="winIcon">🍕</div>
      <h2 class="win-title" id="winTitle">Prêmio</h2>
      <p class="win-message" id="winMessage">Você ganhou!</p>
      <button class="modal-btn" id="closeModal">Girar de novo!</button>
    </div>
  </div>
</div>

<script>
// =====================================================
// PRÊMIOS DA PIZZARIA
// =====================================================
const prizes = [
  { name: 'Pizza Margherita',  icon: '🍕', prob: 10, slice: 'margherita',  message: 'Uma Margherita fresquinha no forno a lenha é sua!' },
  { name: 'Refrigerante 2L',   icon: '🥤', prob: 10, slice: 'soda',        message: 'Refri 2L geladinho pra acompanhar!' },
  { name: 'Borda Recheada',    icon: '🧀', prob: 10, slice: 'cheese',      message: 'Borda recheada de catupiry grátis na sua próxima pizza!' },
  { name: '50% OFF',           icon: '💸', prob: 10, slice: 'discount',    message: 'Metade do preço na sua próxima pizza. Mamma mia!' },
  { name: 'Sobremesa Grátis',  icon: '🍰', prob: 10, slice: 'dessert',     message: 'Doce dolce vita: sobremesa por nossa conta!' },
  { name: 'Tente Outra Vez',   icon: '😢', prob: 10, slice: 'burnt',       isLoss: true, message: 'Quase! A pizza queimou um pouquinho. Tente de novo!' },
  { name: 'Combo Família',     icon: '👨‍👩‍👧', prob: 9,  slice: 'family',      message: 'Pizza grande + refri + sobremesa pra família toda!' },
  { name: 'Tente Outra Vez',   icon: '😢', prob: 10, slice: 'burnt',       isLoss: true, message: 'Faltou só um pouquinho de queijo. Tente de novo!' },
  { name: 'Pizza Grátis 1 ANO',icon: '👑', prob: 1,  slice: 'mega',        isMega: true, message: 'Você desbloqueou o prêmio máximo da casa! Uma pizza por mês, durante 12 meses!' },
  { name: 'Tente Outra Vez',   icon: '😢', prob: 10, slice: 'burnt',       isLoss: true, message: 'A massa caiu no chão... Tente de novo!' },
];

// =====================================================
// CANVAS - DESENHA A PIZZA COMO ROLETA
// =====================================================
const canvas = document.getElementById('wheel');
const ctx = canvas.getContext('2d');
const size = canvas.width;
const cx = size / 2;
const cy = size / 2;
const R = cx - 5;

const sliceAngle = (Math.PI * 2) / prizes.length;

function drawWheel() {
  ctx.clearRect(0, 0, size, size);

  prizes.forEach((prize, i) => {
    const startAngle = i * sliceAngle - Math.PI / 2;
    const endAngle = startAngle + sliceAngle;

    // BASE DA FATIA (cor depende do sabor)
    drawSliceBase(startAngle, endAngle, prize.slice);

    // INGREDIENTES (depende do sabor)
    drawSliceToppings(startAngle, endAngle, prize.slice, i);

    // BORDA ENTRE FATIAS (linha de corte)
    ctx.beginPath();
    ctx.moveTo(cx, cy);
    ctx.lineTo(cx + Math.cos(startAngle) * R, cy + Math.sin(startAngle) * R);
    ctx.strokeStyle = 'rgba(0, 0, 0, 0.2)';
    ctx.lineWidth = 1;
    ctx.stroke();

    // TEXTO DO PRÊMIO
    drawSliceText(startAngle, prize);
  });

  // BRILHO no centro
  const grad = ctx.createRadialGradient(cx, cy, 0, cx, cy, 60);
  grad.addColorStop(0, 'rgba(255, 255, 255, 0.5)');
  grad.addColorStop(1, 'rgba(255, 255, 255, 0)');
  ctx.fillStyle = grad;
  ctx.beginPath();
  ctx.arc(cx, cy, 60, 0, Math.PI * 2);
  ctx.fill();

  // Manchas de queijo derretido no fundo geral
  for (let i = 0; i < 12; i++) {
    const ang = Math.random() * Math.PI * 2;
    const rr = 60 + Math.random() * (R - 100);
    const x = cx + Math.cos(ang) * rr;
    const y = cy + Math.sin(ang) * rr;
    ctx.fillStyle = `rgba(255, 220, 100, ${0.1 + Math.random() * 0.15})`;
    ctx.beginPath();
    ctx.arc(x, y, 8 + Math.random() * 12, 0, Math.PI * 2);
    ctx.fill();
  }
}

function drawSliceBase(start, end, type) {
  // Cores diferentes para cada tipo de sabor/fatia
  const slicePalettes = {
    margherita: { base: '#e63946', accent: '#c1272d' },
    soda:       { base: '#2a4d6e', accent: '#1a3a5c' },
    cheese:     { base: '#f4c430', accent: '#d4a017' },
    discount:   { base: '#7a3e9d', accent: '#5e2d7a' },
    dessert:    { base: '#d4738f', accent: '#a85370' },
    family:     { base: '#e8843f', accent: '#c66b2a' },
    burnt:      { base: '#4a3a2a', accent: '#2d2418' },
    mega:       { base: '#d4a017', accent: '#8b6914' },
  };
  const palette = slicePalettes[type] || slicePalettes.margherita;

  // Gradiente radial para dar sensação 3D
  const grad = ctx.createRadialGradient(cx, cy, 50, cx, cy, R);
  grad.addColorStop(0, palette.base);
  grad.addColorStop(0.7, palette.base);
  grad.addColorStop(1, palette.accent);

  ctx.beginPath();
  ctx.moveTo(cx, cy);
  ctx.arc(cx, cy, R, start, end);
  ctx.closePath();
  ctx.fillStyle = grad;
  ctx.fill();

  // MEGA: brilho dourado especial
  if (type === 'mega') {
    const shineGrad = ctx.createRadialGradient(cx, cy, 50, cx, cy, R);
    shineGrad.addColorStop(0, 'rgba(255, 245, 200, 0.8)');
    shineGrad.addColorStop(0.5, 'rgba(244, 196, 48, 0.3)');
    shineGrad.addColorStop(1, 'rgba(212, 160, 23, 0)');
    ctx.fillStyle = shineGrad;
    ctx.beginPath();
    ctx.moveTo(cx, cy);
    ctx.arc(cx, cy, R, start, end);
    ctx.closePath();
    ctx.fill();
  }
}

function drawSliceToppings(start, end, type, seedIdx) {
  // Cada fatia recebe ingredientes específicos
  const midAng = (start + end) / 2;
  
  // Função para pontos dentro da fatia
  function pointsInSlice(count, minR, maxR) {
    const points = [];
    // Usar seed determinístico para que a posição seja consistente
    let seed = seedIdx * 1000;
    function rand() { 
      seed = (seed * 9301 + 49297) % 233280;
      return seed / 233280;
    }
    for (let i = 0; i < count; i++) {
      const ang = start + 0.15 + rand() * (sliceAngle - 0.3);
      const rr = minR + rand() * (maxR - minR);
      points.push({ x: cx + Math.cos(ang) * rr, y: cy + Math.sin(ang) * rr });
    }
    return points;
  }

  if (type === 'margherita') {
    // Pepperoni vermelho
    pointsInSlice(6, 80, R - 50).forEach(p => drawPepperoni(p.x, p.y));
    // Manjericão
    pointsInSlice(3, 90, R - 60).forEach(p => drawBasil(p.x, p.y));
  } else if (type === 'cheese') {
    // Quatro queijos - bolhas de queijo
    pointsInSlice(8, 80, R - 50).forEach(p => drawCheeseBubble(p.x, p.y));
  } else if (type === 'soda') {
    // Bolhas de refrigerante
    pointsInSlice(10, 80, R - 50).forEach(p => drawSodaBubble(p.x, p.y));
  } else if (type === 'family') {
    // Mix de tudo
    pointsInSlice(3, 90, R - 60).forEach(p => drawPepperoni(p.x, p.y));
    pointsInSlice(2, 90, R - 60).forEach(p => drawBasil(p.x, p.y));
    pointsInSlice(3, 90, R - 60).forEach(p => drawOlive(p.x, p.y));
  } else if (type === 'dessert') {
    // Confeitos / morangos
    pointsInSlice(6, 80, R - 50).forEach(p => drawStrawberry(p.x, p.y));
  } else if (type === 'discount') {
    // Estrelas / moedas
    pointsInSlice(5, 80, R - 50).forEach(p => drawCoin(p.x, p.y));
  } else if (type === 'burnt') {
    // Manchas de queimado
    pointsInSlice(8, 80, R - 50).forEach(p => drawBurntSpot(p.x, p.y));
  } else if (type === 'mega') {
    // Estrelas douradas brilhantes
    pointsInSlice(8, 80, R - 50).forEach(p => drawStar(p.x, p.y, 6));
  }
}

// ============ DESENHOS DE INGREDIENTES ============
function drawPepperoni(x, y) {
  const r = 14;
  ctx.beginPath();
  ctx.arc(x, y, r, 0, Math.PI * 2);
  const g = ctx.createRadialGradient(x - 3, y - 3, 0, x, y, r);
  g.addColorStop(0, '#e74c3c');
  g.addColorStop(0.6, '#c1272d');
  g.addColorStop(1, '#8b1a1f');
  ctx.fillStyle = g;
  ctx.fill();
  ctx.strokeStyle = '#5c0e12';
  ctx.lineWidth = 1.5;
  ctx.stroke();
  // Pontinhos de gordura
  ctx.fillStyle = '#f5a8a0';
  for (let i = 0; i < 3; i++) {
    const ang = Math.random() * Math.PI * 2;
    const rr = Math.random() * 8;
    ctx.beginPath();
    ctx.arc(x + Math.cos(ang) * rr, y + Math.sin(ang) * rr, 1.5, 0, Math.PI * 2);
    ctx.fill();
  }
}

function drawBasil(x, y) {
  ctx.save();
  ctx.translate(x, y);
  ctx.rotate(Math.random() * Math.PI);
  ctx.beginPath();
  ctx.ellipse(0, 0, 5, 11, 0, 0, Math.PI * 2);
  const g = ctx.createRadialGradient(-2, -3, 0, 0, 0, 11);
  g.addColorStop(0, '#7cb342');
  g.addColorStop(1, '#33691e');
  ctx.fillStyle = g;
  ctx.fill();
  ctx.strokeStyle = '#1b3d0f';
  ctx.lineWidth = 0.8;
  ctx.stroke();
  // Nervura
  ctx.beginPath();
  ctx.moveTo(0, -10);
  ctx.lineTo(0, 10);
  ctx.strokeStyle = '#1b3d0f';
  ctx.lineWidth = 0.5;
  ctx.stroke();
  ctx.restore();
}

function drawOlive(x, y) {
  ctx.beginPath();
  ctx.ellipse(x, y, 6, 8, Math.PI / 4, 0, Math.PI * 2);
  const g = ctx.createRadialGradient(x - 2, y - 2, 0, x, y, 8);
  g.addColorStop(0, '#5d4037');
  g.addColorStop(1, '#1a0e0a');
  ctx.fillStyle = g;
  ctx.fill();
  ctx.strokeStyle = '#000';
  ctx.lineWidth = 0.5;
  ctx.stroke();
}

function drawCheeseBubble(x, y) {
  ctx.beginPath();
  ctx.arc(x, y, 8 + Math.random() * 6, 0, Math.PI * 2);
  const g = ctx.createRadialGradient(x - 2, y - 2, 0, x, y, 12);
  g.addColorStop(0, '#fff8d4');
  g.addColorStop(1, '#d4a017');
  ctx.fillStyle = g;
  ctx.fill();
  ctx.strokeStyle = '#8b6914';
  ctx.lineWidth = 0.8;
  ctx.stroke();
}

function drawSodaBubble(x, y) {
  const r = 4 + Math.random() * 5;
  ctx.beginPath();
  ctx.arc(x, y, r, 0, Math.PI * 2);
  ctx.fillStyle = 'rgba(255, 255, 255, 0.8)';
  ctx.fill();
  ctx.strokeStyle = 'rgba(255, 255, 255, 1)';
  ctx.lineWidth = 1;
  ctx.stroke();
}

function drawStrawberry(x, y) {
  ctx.beginPath();
  ctx.moveTo(x, y - 8);
  ctx.bezierCurveTo(x + 8, y - 6, x + 8, y + 6, x, y + 10);
  ctx.bezierCurveTo(x - 8, y + 6, x - 8, y - 6, x, y - 8);
  const g = ctx.createRadialGradient(x - 2, y - 2, 0, x, y, 10);
  g.addColorStop(0, '#ff6b8b');
  g.addColorStop(1, '#c2185b');
  ctx.fillStyle = g;
  ctx.fill();
  // Sementes
  ctx.fillStyle = '#fff8d4';
  for (let i = 0; i < 4; i++) {
    const ang = Math.random() * Math.PI * 2;
    const rr = Math.random() * 5;
    ctx.beginPath();
    ctx.arc(x + Math.cos(ang) * rr, y + Math.sin(ang) * rr, 0.8, 0, Math.PI * 2);
    ctx.fill();
  }
}

function drawCoin(x, y) {
  ctx.beginPath();
  ctx.arc(x, y, 10, 0, Math.PI * 2);
  const g = ctx.createRadialGradient(x - 3, y - 3, 0, x, y, 10);
  g.addColorStop(0, '#fff5cc');
  g.addColorStop(0.5, '#f4c430');
  g.addColorStop(1, '#8b6914');
  ctx.fillStyle = g;
  ctx.fill();
  ctx.strokeStyle = '#5c4308';
  ctx.lineWidth = 1.5;
  ctx.stroke();
  ctx.fillStyle = '#5c4308';
  ctx.font = 'bold 11px serif';
  ctx.textAlign = 'center';
  ctx.textBaseline = 'middle';
  ctx.fillText('$', x, y);
}

function drawBurntSpot(x, y) {
  ctx.beginPath();
  ctx.arc(x, y, 5 + Math.random() * 6, 0, Math.PI * 2);
  ctx.fillStyle = `rgba(20, 10, 5, ${0.5 + Math.random() * 0.3})`;
  ctx.fill();
}

function drawStar(x, y, r) {
  ctx.save();
  ctx.translate(x, y);
  ctx.rotate(Math.random() * Math.PI);
  ctx.beginPath();
  for (let i = 0; i < 5; i++) {
    const ang = (i * 4 * Math.PI) / 5 - Math.PI / 2;
    const px = Math.cos(ang) * r;
    const py = Math.sin(ang) * r;
    if (i === 0) ctx.moveTo(px, py);
    else ctx.lineTo(px, py);
  }
  ctx.closePath();
  const g = ctx.createRadialGradient(0, 0, 0, 0, 0, r);
  g.addColorStop(0, '#fff8d4');
  g.addColorStop(0.5, '#f4c430');
  g.addColorStop(1, '#8b6914');
  ctx.fillStyle = g;
  ctx.fill();
  ctx.strokeStyle = '#5c4308';
  ctx.lineWidth = 1;
  ctx.stroke();
  ctx.restore();
}

function drawSliceText(start, prize) {
  ctx.save();
  ctx.translate(cx, cy);
  ctx.rotate(start + sliceAngle / 2);
  ctx.textAlign = 'right';
  
  // Fundo translúcido para o texto
  const textRadius = R - 25;
  ctx.fillStyle = 'rgba(255, 248, 231, 0.92)';
  ctx.strokeStyle = 'rgba(92, 51, 23, 0.5)';
  ctx.lineWidth = 1;
  // Pílula com texto
  const padX = 8, padY = 4;
  ctx.font = 'bold 14px "DM Sans", sans-serif';
  const txt = prize.name;
  const w = ctx.measureText(txt).width;
  
  // Pílula
  ctx.beginPath();
  const pillX = textRadius - w - padX;
  const pillY = -10;
  const pillW = w + padX * 2;
  const pillH = 22;
  const radius = 11;
  ctx.moveTo(pillX + radius, pillY);
  ctx.lineTo(pillX + pillW - radius, pillY);
  ctx.arc(pillX + pillW - radius, pillY + radius, radius, -Math.PI / 2, Math.PI / 2);
  ctx.lineTo(pillX + radius, pillY + pillH);
  ctx.arc(pillX + radius, pillY + radius, radius, Math.PI / 2, -Math.PI / 2);
  ctx.closePath();
  ctx.fill();
  ctx.stroke();
  
  // Texto
  ctx.fillStyle = '#5c3317';
  ctx.textAlign = 'center';
  ctx.textBaseline = 'middle';
  ctx.fillText(txt, pillX + pillW / 2, pillY + pillH / 2);

  // Emoji
  ctx.font = '34px Arial';
  ctx.textAlign = 'right';
  ctx.fillText(prize.icon, textRadius - 8, 28);
  
  ctx.restore();
}

drawWheel();

// =====================================================
// INGREDIENTES FLUTUANDO NO FUNDO
// =====================================================
const floaters = document.getElementById('floaters');
const ingredients = ['🍕', '🍅', '🧀', '🌿', '🫒', '🥖', '🌶️', '🧄'];
for (let i = 0; i < 12; i++) {
  const el = document.createElement('div');
  el.className = 'float-item';
  el.textContent = ingredients[Math.floor(Math.random() * ingredients.length)];
  el.style.left = Math.random() * 100 + 'vw';
  el.style.top = Math.random() * 100 + 'vh';
  el.style.fontSize = (28 + Math.random() * 25) + 'px';
  el.style.animationDuration = (6 + Math.random() * 8) + 's';
  el.style.animationDelay = -Math.random() * 10 + 's';
  el.style.opacity = 0.4 + Math.random() * 0.3;
  floaters.appendChild(el);
}

// =====================================================
// SORTEIO POR PROBABILIDADE REAL
// =====================================================
function pickPrize() {
  const r = Math.random() * 100;
  let cum = 0;
  for (let i = 0; i < prizes.length; i++) {
    cum += prizes[i].prob;
    if (r <= cum) return i;
  }
  return prizes.length - 1;
}

// =====================================================
// GIRAR ROLETA
// =====================================================
const spinBtn = document.getElementById('spinBtn');
const wheelEl = document.getElementById('wheel');
let currentRotation = 0;
let spinning = false;

spinBtn.addEventListener('click', () => {
  if (spinning) return;
  spinning = true;
  spinBtn.disabled = true;

  const winnerIndex = pickPrize();
  const sliceAngleDeg = 360 / prizes.length;
  const targetAngle = -(winnerIndex * sliceAngleDeg + sliceAngleDeg / 2);
  const extraSpins = 6;
  const jitter = (Math.random() - 0.5) * (sliceAngleDeg * 0.65);
  const finalRotation = currentRotation + (360 * extraSpins) + (targetAngle - (currentRotation % 360)) + jitter;
  currentRotation = finalRotation;
  wheelEl.style.transform = `rotate(${finalRotation}deg)`;

  setTimeout(() => {
    showResult(winnerIndex);
    spinning = false;
    spinBtn.disabled = false;
  }, 6700);
});

// =====================================================
// MOSTRAR RESULTADO
// =====================================================
const modal = document.getElementById('modal');
const modalContent = document.getElementById('modalContent');
const winLabel = document.getElementById('winLabel');
const winIcon = document.getElementById('winIcon');
const winTitle = document.getElementById('winTitle');
const winMessage = document.getElementById('winMessage');
const closeModal = document.getElementById('closeModal');

function showResult(index) {
  const prize = prizes[index];
  modalContent.classList.remove('loss', 'mega');
  winIcon.textContent = prize.icon;
  winTitle.textContent = prize.name;
  winMessage.textContent = prize.message;

  if (prize.isLoss) {
    modalContent.classList.add('loss');
    winLabel.textContent = 'Peccato...';
  } else if (prize.isMega) {
    modalContent.classList.add('mega');
    winLabel.textContent = '✨ PRÊMIO MÁXIMO ✨';
    fireMegaCelebration();
  } else {
    winLabel.textContent = 'Complimenti! 🎉';
    fireCelebration();
  }
  modal.classList.add('active');
}

closeModal.addEventListener('click', () => {
  modal.classList.remove('active');
});

// =====================================================
// CONFETE DE INGREDIENTES + FOGOS
// =====================================================
const confettiEmojis = ['🍕', '🍅', '🧀', '🌿', '🫒', '🥖', '🌶️', '🧄', '⭐', '✨', '🎉'];
const fireworkColors = ['#c1272d', '#f4c430', '#008c45', '#fff8e7', '#e63946', '#d4a017', '#7cb342'];

function fireCelebration() {
  for (let i = 0; i < 80; i++) {
    setTimeout(() => createConfetti(), i * 25);
  }
  for (let i = 0; i < 4; i++) {
    setTimeout(() => createFirework(), i * 500);
  }
}

function fireMegaCelebration() {
  // CHUVA DE INGREDIENTES MEGA
  for (let i = 0; i < 250; i++) {
    setTimeout(() => createConfetti(true), i * 12);
  }
  for (let i = 0; i < 18; i++) {
    setTimeout(() => createFirework(), i * 220);
  }
}

function createConfetti(mega = false) {
  const c = document.createElement('div');
  c.className = 'confetti';
  c.textContent = confettiEmojis[Math.floor(Math.random() * confettiEmojis.length)];
  c.style.left = Math.random() * 100 + 'vw';
  c.style.fontSize = (mega ? (22 + Math.random() * 28) : (20 + Math.random() * 18)) + 'px';
  document.body.appendChild(c);

  const duration = 2800 + Math.random() * 2200;
  const xDrift = (Math.random() - 0.5) * 500;
  const rotation = Math.random() * 1080 - 540;

  c.animate([
    { transform: 'translate(0, 0) rotate(0deg)', opacity: 1 },
    { transform: `translate(${xDrift}px, ${window.innerHeight + 80}px) rotate(${rotation}deg)`, opacity: 0 }
  ], { duration, easing: 'cubic-bezier(0.1, 0.1, 0.1, 1)' });

  setTimeout(() => c.remove(), duration);
}

function createFirework() {
  const x = 10 + Math.random() * 80;
  const y = 10 + Math.random() * 50;
  const color = fireworkColors[Math.floor(Math.random() * fireworkColors.length)];
  for (let i = 0; i < 30; i++) {
    const p = document.createElement('div');
    p.className = 'firework';
    p.style.left = x + 'vw';
    p.style.top = y + 'vh';
    p.style.width = '8px';
    p.style.height = '8px';
    p.style.background = color;
    p.style.borderRadius = '50%';
    p.style.boxShadow = `0 0 12px ${color}, 0 0 24px ${color}`;
    document.body.appendChild(p);

    const angle = (i / 30) * Math.PI * 2;
    const distance = 100 + Math.random() * 80;
    const dx = Math.cos(angle) * distance;
    const dy = Math.sin(angle) * distance;

    p.animate([
      { transform: 'translate(0, 0) scale(1)', opacity: 1 },
      { transform: `translate(${dx}px, ${dy}px) scale(0)`, opacity: 0 }
    ], { duration: 1100 + Math.random() * 500, easing: 'cubic-bezier(0, 0.5, 0.5, 1)' });

    setTimeout(() => p.remove(), 1700);
  }
}
</script>
</body>
</html>

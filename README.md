# Natural ou Fake Natty? Como Vencer na Era das IAs Generativas

## 🚀 Introdução

> Woooow! Look at this 👀

Olá pessoal! Inspirado na hype _"Natty or Not"_ do fisiculturismo, este Lab te convida a conhecer o mundo das IAs Generativas, explorando o potencial dessas tendências tecnológicas incríveis!

## 🎯 Bora Pro Desafio!? Você Já Venceu 💪🤓

Titulo

act like a painter from the 60s, and make me a work of what he would think today's times would be like

📒 Descrição
Fiz esse teste para testar algumas inteligências aritificiais generativas baseadas em imagens, como: LeonardoAI, SORA, Copilot. O objetivo era ver se eles tinham a mesma ``imaginacao`` com o promt designado.

🤖 Tecnologias Utilizadas
LeonardoAI
Sora
Copilot
Claude

🧐 Processo de Criação
act like a painter from the 60s, and make me a work of what he would think today's times would be like

🚀 Resultados
Apresente os resultados do seu projeto
![Leonardo_Lightning_XL_Atue_como_um_pintor_dos_anos_90_e_crie_u_2](https://github.com/user-attachments/assets/2c14db58-d436-4a1b-9dce-92bb1acf6997)
![Leonardo_Vision_XL_Atue_como_um_pintor_famoso_dos_anos_80_e_cr_1](https://github.com/user-attachments/assets/7a8cc739-ec4e-42af-a637-5f7e32df7a5c)
![Leonardo_Vision_XL_Atue_como_um_pintos_famoso_dos_anos_60_e_cr_3](https://github.com/user-attachments/assets/5c7f04a3-e1f0-4fa2-b5a3-f17d41027d92)

ClaudeAI:
Bom, o processo de criação no Claude foi um pouco diferente. 
Utilizando o mesmo promt que foi usado nas demais IAs ele atuou como um programador, gerando um código para a geração da image.


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Visions of Tomorrow - A 1960s Painter's Dream</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background: linear-gradient(45deg, #ff6b6b, #4ecdc4, #45b7d1, #96ceb4);
            background-size: 400% 400%;
            animation: psychedelicFlow 8s ease-in-out infinite;
            font-family: 'Courier New', monospace;
            overflow-x: hidden;
        }

        @keyframes psychedelicFlow {
            0%, 100% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
        }

        .canvas {
            position: relative;
            width: 100vw;
            height: 100vh;
            overflow: hidden;
        }

        .floating-element {
            position: absolute;
            animation: float 6s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-20px) rotate(180deg); }
        }

        .screen-people {
            position: absolute;
            top: 20%;
            left: 10%;
            width: 200px;
            height: 300px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            border-radius: 20px;
            animation: glow 3s ease-in-out infinite alternate;
            z-index: 10;
        }

        .screen-people::before {
            content: '';
            position: absolute;
            top: 10px;
            left: 10px;
            right: 10px;
            bottom: 10px;
            background: radial-gradient(circle, #ff9a9e 0%, #fecfef 50%, #fecfef 100%);
            border-radius: 15px;
            opacity: 0.8;
            animation: screenFlicker 2s infinite;
        }

        @keyframes screenFlicker {
            0%, 100% { opacity: 0.8; }
            50% { opacity: 0.3; }
        }

        @keyframes glow {
            from { box-shadow: 0 0 20px #ff6b6b; }
            to { box-shadow: 0 0 40px #4ecdc4, 0 0 60px #45b7d1; }
        }

        .flying-cars {
            position: absolute;
            top: 15%;
            right: 15%;
            width: 150px;
            height: 80px;
            background: linear-gradient(45deg, #ff7043, #ffab40);
            border-radius: 50px;
            animation: fly 4s linear infinite;
        }

        .flying-cars::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 20%;
            right: 20%;
            height: 20px;
            background: radial-gradient(ellipse, rgba(255, 112, 67, 0.6) 0%, transparent 70%);
            border-radius: 50%;
            animation: thrust 0.5s ease-in-out infinite alternate;
        }

        @keyframes fly {
            0% { transform: translateX(0) translateY(0); }
            25% { transform: translateX(100px) translateY(-30px); }
            50% { transform: translateX(200px) translateY(0); }
            75% { transform: translateX(100px) translateY(30px); }
            100% { transform: translateX(0) translateY(0); }
        }

        @keyframes thrust {
            from { transform: scaleY(1); }
            to { transform: scaleY(1.5); }
        }

        .robot-servant {
            position: absolute;
            bottom: 20%;
            left: 30%;
            width: 120px;
            height: 180px;
            background: linear-gradient(180deg, #c0392b, #e74c3c);
            border-radius: 20px 20px 40px 40px;
            animation: robotWalk 3s ease-in-out infinite;
        }

        .robot-servant::before {
            content: '';
            position: absolute;
            top: 20px;
            left: 20px;
            right: 20px;
            height: 60px;
            background: radial-gradient(circle, #f39c12 30%, transparent 70%);
            border-radius: 50%;
        }

        @keyframes robotWalk {
            0%, 100% { transform: translateX(0) skew(0deg); }
            25% { transform: translateX(20px) skew(5deg); }
            50% { transform: translateX(40px) skew(0deg); }
            75% { transform: translateX(20px) skew(-5deg); }
        }

        .space-buildings {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            height: 300px;
            background: linear-gradient(to top, #2c3e50, #3498db);
            opacity: 0.7;
        }

        .building {
            position: absolute;
            bottom: 0;
            background: linear-gradient(to top, #34495e, #9b59b6);
            animation: buildingPulse 4s ease-in-out infinite;
        }

        .building:nth-child(1) {
            left: 5%;
            width: 60px;
            height: 200px;
            animation-delay: 0s;
        }

        .building:nth-child(2) {
            left: 15%;
            width: 80px;
            height: 250px;
            animation-delay: 1s;
        }

        .building:nth-child(3) {
            left: 30%;
            width: 70px;
            height: 180px;
            animation-delay: 2s;
        }

        .building:nth-child(4) {
            right: 25%;
            width: 90px;
            height: 220px;
            animation-delay: 0.5s;
        }

        .building:nth-child(5) {
            right: 10%;
            width: 75px;
            height: 190px;
            animation-delay: 1.5s;
        }

        @keyframes buildingPulse {
            0%, 100% { transform: scaleY(1); opacity: 0.7; }
            50% { transform: scaleY(1.1); opacity: 1; }
        }

        .floating-pills {
            position: absolute;
            top: 40%;
            right: 20%;
            width: 30px;
            height: 60px;
            background: linear-gradient(45deg, #e056fd, #f093fb);
            border-radius: 15px;
            animation: pillFloat 5s ease-in-out infinite;
        }

        .floating-pills:nth-child(7) {
            top: 35%;
            right: 25%;
            animation-delay: 1s;
            background: linear-gradient(45deg, #4facfe, #00f2fe);
        }

        .floating-pills:nth-child(8) {
            top: 45%;
            right: 15%;
            animation-delay: 2s;
            background: linear-gradient(45deg, #43e97b, #38f9d7);
        }

        @keyframes pillFloat {
            0%, 100% { transform: translateY(0) rotate(0deg); }
            33% { transform: translateY(-40px) rotate(120deg); }
            66% { transform: translateY(-20px) rotate(240deg); }
        }

        .thought-bubbles {
            position: absolute;
            top: 10%;
            left: 50%;
            width: 80px;
            height: 80px;
            background: radial-gradient(circle, rgba(255, 255, 255, 0.8) 0%, rgba(255, 255, 255, 0.2) 100%);
            border-radius: 50%;
            animation: thoughtFloat 3s ease-in-out infinite;
        }

        .thought-bubbles::before,
        .thought-bubbles::after {
            content: '';
            position: absolute;
            background: radial-gradient(circle, rgba(255, 255, 255, 0.6) 0%, rgba(255, 255, 255, 0.1) 100%);
            border-radius: 50%;
        }

        .thought-bubbles::before {
            top: 60px;
            left: -20px;
            width: 40px;
            height: 40px;
        }

        .thought-bubbles::after {
            top: 80px;
            left: -40px;
            width: 20px;
            height: 20px;
        }

        @keyframes thoughtFloat {
            0%, 100% { transform: translate(0, 0); opacity: 0.8; }
            50% { transform: translate(30px, -50px); opacity: 0.3; }
        }

        .signature {
            position: absolute;
            bottom: 20px;
            right: 30px;
            color: white;
            font-size: 18px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
            opacity: 0.8;
            animation: signatureGlow 4s ease-in-out infinite;
        }

        @keyframes signatureGlow {
            0%, 100% { text-shadow: 2px 2px 4px rgba(0,0,0,0.5); }
            50% { text-shadow: 0 0 20px rgba(255,255,255,0.8); }
        }

        .title {
            position: absolute;
            top: 30px;
            left: 50%;
            transform: translateX(-50%);
            color: white;
            font-size: 24px;
            font-weight: bold;
            text-shadow: 3px 3px 6px rgba(0,0,0,0.7);
            animation: titlePulse 3s ease-in-out infinite;
        }

        @keyframes titlePulse {
            0%, 100% { transform: translateX(-50%) scale(1); }
            50% { transform: translateX(-50%) scale(1.05); }
        }
    </style>
</head>
<body>
    <div class="canvas">
        <div class="title">"The Electric Tomorrow" - 1968</div>
        
        <div class="space-buildings">
            <div class="building"></div>
            <div class="building"></div>
            <div class="building"></div>
            <div class="building"></div>
            <div class="building"></div>
        </div>
        
        <div class="screen-people floating-element"></div>
        <div class="flying-cars floating-element"></div>
        <div class="robot-servant floating-element"></div>
        <div class="floating-pills floating-element"></div>
        <div class="floating-pills floating-element"></div>
        <div class="floating-pills floating-element"></div>
        <div class="thought-bubbles floating-element"></div>
        
        <div class="signature">~ Jacques Lumière, '68</div>
    </div>

    <script>
        // Add some interactive sparkles when clicking
        document.addEventListener('click', function(e) {
            for(let i = 0; i < 5; i++) {
                createSparkle(e.clientX, e.clientY);
            }
        });

        function createSparkle(x, y) {
            const sparkle = document.createElement('div');
            sparkle.style.position = 'fixed';
            sparkle.style.left = x + (Math.random() - 0.5) * 100 + 'px';
            sparkle.style.top = y + (Math.random() - 0.5) * 100 + 'px';
            sparkle.style.width = '4px';
            sparkle.style.height = '4px';
            sparkle.style.background = `hsl(${Math.random() * 360}, 100%, 70%)`;
            sparkle.style.borderRadius = '50%';
            sparkle.style.pointerEvents = 'none';
            sparkle.style.animation = 'sparkleExplode 1s ease-out forwards';
            document.body.appendChild(sparkle);

            setTimeout(() => {
                sparkle.remove();
            }, 1000);
        }

        // Add sparkle animation
        const style = document.createElement('style');
        style.textContent = `
            @keyframes sparkleExplode {
                0% { transform: scale(0) rotate(0deg); opacity: 1; }
                100% { transform: scale(3) rotate(180deg); opacity: 0; }
            }
        `;
        document.head.appendChild(style);
    </script>
</body>
</html>

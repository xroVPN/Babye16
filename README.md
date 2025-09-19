<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>🌹 تولدت مبارک 🌹</title>
    <link href="https://fonts.googleapis.com/css2?family=Vazirmatn:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;700&display=swap');
        
        * { 
            margin: 0; 
            padding: 0; 
            box-sizing: border-box; 
            user-select: none; 
            -webkit-user-select: none; 
            -moz-user-select: none; 
            -ms-user-select: none; 
        }
        
        html, body { 
            width: 100%; 
            height: 100vh; 
            overflow: hidden; 
            position: fixed; 
            top: 0; 
            left: 0; 
            user-select: none; 
            -webkit-user-select: none; 
            -moz-user-select: none; 
            -ms-user-select: none; 
            touch-action: none;
        }
        
        body { 
            font-family: 'Vazirmatn', sans-serif; 
            height: 100vh; 
            overflow: hidden; 
            cursor: pointer; 
            position: relative; 
            background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab, #667eea, #764ba2); 
            background-size: 400% 400%;
            animation: gradientShift 15s ease infinite;
            user-select: none; 
            -webkit-user-select: none; 
            -moz-user-select: none; 
            -ms-user-select: none; 
        }

        @keyframes gradientShift {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        /* Ultra Background Layers */
        .background { 
            position: fixed; 
            top: 0; 
            left: 0; 
            width: 100%; 
            height: 100vh; 
            background: 
                radial-gradient(circle at 20% 80%, rgba(120, 119, 198, 0.3) 0%, transparent 50%),
                radial-gradient(circle at 80% 20%, rgba(255, 119, 198, 0.3) 0%, transparent 50%),
                radial-gradient(circle at 40% 40%, rgba(120, 219, 255, 0.2) 0%, transparent 50%),
                linear-gradient(45deg, rgba(255, 107, 157, 0.1) 0%, rgba(255, 140, 157, 0.1) 25%, rgba(255, 107, 157, 0.1) 50%, rgba(255, 140, 157, 0.1) 75%, rgba(255, 107, 157, 0.1) 100%);
            z-index: -3; 
            animation: backgroundPulse 8s ease-in-out infinite alternate, rotateLayer 20s linear infinite; 
        }

        @keyframes backgroundPulse { 
            0% { opacity: 0.7; } 
            100% { opacity: 1; } 
        }

        @keyframes rotateLayer {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        .bg-image { 
            position: fixed; 
            top: 0; 
            left: 0; 
            width: 100%; 
            height: 100vh; 
            background-image: url('https://s6.uupload.ir/files/img_20250918_212920_827_6ern.jpg'); 
            background-size: cover; 
            background-position: center; 
            filter: blur(0.3px) brightness(0.85) saturate(1.2) contrast(1.1); 
            z-index: -2; 
            opacity: 0.75; 
            animation: imageFloat 20s ease-in-out infinite;
        }

        @keyframes imageFloat {
            0%, 100% { transform: scale(1) translateY(0px); }
            50% { transform: scale(1.05) translateY(-10px); }
        }

        /* Floating Geometric Shapes */
        .geometric-shapes {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100vh;
            z-index: -1;
            pointer-events: none;
        }

        .shape {
            position: absolute;
            opacity: 0.1;
            animation: floatShapes 15s ease-in-out infinite;
        }

        .shape:nth-child(1) {
            top: 10%; left: 10%;
            width: 80px; height: 80px;
            background: linear-gradient(45deg, #ff6b9d, #ffd93d);
            border-radius: 50%;
            animation-delay: 0s;
        }

        .shape:nth-child(2) {
            top: 70%; right: 15%;
            width: 60px; height: 60px;
            background: linear-gradient(45deg, #54a0ff, #5f27cd);
            clip-path: polygon(50% 0%, 0% 100%, 100% 100%);
            animation-delay: 3s;
        }

        .shape:nth-child(3) {
            bottom: 20%; left: 20%;
            width: 100px; height: 100px;
            background: linear-gradient(45deg, #ff9ff3, #feca57);
            border-radius: 20px;
            animation-delay: 6s;
        }

        .shape:nth-child(4) {
            top: 40%; right: 30%;
            width: 70px; height: 70px;
            background: linear-gradient(45deg, #ff6b9d, #ff4757);
            clip-path: polygon(25% 0%, 75% 0%, 100% 50%, 75% 100%, 25% 100%, 0% 50%);
            animation-delay: 9s;
        }

        @keyframes floatShapes {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            33% { transform: translateY(-20px) rotate(120deg); }
            66% { transform: translateY(10px) rotate(240deg); }
        }

        .lock-bg { 
            position: fixed; 
            top: 0; 
            left: 0; 
            width: 100%; 
            height: 100vh; 
            background-image: url('https://i1.delgarm.com/i/828/011120/funny-gif(11).gif'); 
            background-size: cover; 
            background-position: center; 
            background-repeat: no-repeat; 
            z-index: 5; 
            opacity: 0.3; 
            filter: brightness(0.9) contrast(1.1) saturate(1.2); 
            pointer-events: none; 
            mix-blend-mode: screen;
        }

        .overlay { 
            position: fixed; 
            top: 0; 
            left: 0; 
            width: 100%; 
            height: 100vh; 
            background: 
                linear-gradient(135deg, rgba(255, 107, 157, 0.1) 0%, rgba(120, 219, 255, 0.1) 50%, rgba(255, 193, 7, 0.1) 100%),
                radial-gradient(circle at 30% 30%, rgba(255, 107, 157, 0.2) 0%, transparent 70%),
                radial-gradient(circle at 70% 70%, rgba(120, 219, 255, 0.2) 0%, transparent 70%);
            backdrop-filter: blur(2px) saturate(1.5);
            z-index: 8; 
            animation: overlayShimmer 12s ease-in-out infinite;
        }

        @keyframes overlayShimmer {
            0%, 100% { opacity: 0.8; }
            50% { opacity: 1; }
        }

        /* Sparkle System */
        .sparkle-system {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100vh;
            z-index: 15;
            pointer-events: none;
        }

        .sparkle-particle {
            position: absolute;
            width: 3px;
            height: 3px;
            background: radial-gradient(circle, #ffd700 0%, transparent 70%);
            border-radius: 50%;
            pointer-events: none;
            animation: sparkleTwinkle 3s linear infinite;
        }

        @keyframes sparkleTwinkle {
            0% { 
                opacity: 0; 
                transform: scale(0) translateY(100vh) rotate(0deg); 
            }
            10% { opacity: 1; transform: scale(1) translateY(90vh) rotate(90deg); }
            90% { opacity: 1; transform: scale(1) translateY(10vh) rotate(270deg); }
            100% { 
                opacity: 0; 
                transform: scale(0) translateY(0vh) rotate(360deg); 
            }
        }

        /* Floating Hearts Background */
        .hearts-bg {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100vh;
            z-index: 12;
            pointer-events: none;
            overflow: hidden;
        }

        .bg-heart {
            position: absolute;
            font-size: 1.2rem;
            opacity: 0.3;
            animation: heartFloatBG 8s linear infinite;
            filter: drop-shadow(0 0 10px currentColor);
            transform-origin: center;
        }

        @keyframes heartFloatBG {
            0% { 
                opacity: 0; 
                transform: translateY(100vh) scale(0.5) rotate(0deg); 
            }
            10% { opacity: 0.3; transform: translateY(90vh) scale(0.8) rotate(90deg); }
            90% { opacity: 0.3; transform: translateY(10vh) scale(1.2) rotate(270deg); }
            100% { 
                opacity: 0; 
                transform: translateY(0vh) scale(1.5) rotate(360deg); 
            }
        }

        .login-modal { 
            position: fixed; 
            top: 0; 
            left: 0; 
            width: 100%; 
            height: 100vh; 
            background: rgba(0, 0, 0, 0.85);
            backdrop-filter: blur(15px) saturate(180%); 
            display: flex; 
            justify-content: center; 
            align-items: center; 
            z-index: 2000; 
            opacity: 1; 
            visibility: visible; 
            transition: all 0.8s cubic-bezier(0.4, 0, 0.2, 1); 
            user-select: none; 
            -webkit-user-select: none; 
            -moz-user-select: none; 
            -ms-user-select: none; 
        }

        .login-modal.hidden { 
            opacity: 0; 
            visibility: hidden; 
        }

        .login-container { 
            background: linear-gradient(135deg, 
                rgba(255, 107, 157, 0.98) 0%, 
                rgba(255, 140, 157, 0.98) 25%,
                rgba(120, 219, 255, 0.98) 50%,
                rgba(255, 193, 7, 0.98) 75%,
                rgba(255, 107, 157, 0.98) 100%);
            background-size: 400% 400%;
            animation: containerGradient 10s ease infinite;
            padding: 3.5rem; 
            border-radius: 30px; 
            box-shadow: 
                0 25px 50px rgba(0, 0, 0, 0.4),
                0 0 100px rgba(255, 107, 157, 0.3),
                inset 0 1px 0 rgba(255, 255, 255, 0.2);
            text-align: center; 
            position: relative; 
            max-width: 420px; 
            width: 90%; 
            max-height: 80vh; 
            overflow: hidden; 
            animation: modalSlideIn 0.8s cubic-bezier(0.4, 0, 0.2, 1), containerFloat 6s ease-in-out infinite; 
            border: 3px solid rgba(255, 255, 255, 0.4); 
            position: relative;
            user-select: none; 
            -webkit-user-select: none; 
            -moz-user-select: none; 
            -ms-user-select: none; 
            backdrop-filter: blur(10px);
        }

        @keyframes containerGradient {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        @keyframes containerFloat {
            0%, 100% { transform: translateY(0px) rotateX(0deg); }
            50% { transform: translateY(-5px) rotateX(2deg); }
        }

        @keyframes modalSlideIn { 
            0% { 
                transform: translateY(-100px) scale(0.7) rotateX(10deg); 
                opacity: 0; 
            } 
            100% { 
                transform: translateY(0) scale(1) rotateX(0deg); 
                opacity: 1; 
            } 
        }

        .login-title { 
            color: white; 
            font-size: 2.8rem; 
            margin-bottom: 1.5rem; 
            text-shadow: 
                0 0 10px rgba(255, 255, 255, 0.5),
                2px 2px 4px rgba(0, 0, 0, 0.3),
                0 0 30px rgba(255, 107, 157, 0.8);
            font-weight: 700; 
            font-family: 'Dancing Script', cursive;
            letter-spacing: 3px;
            position: relative;
            user-select: none; 
            -webkit-user-select: none; 
            -moz-user-select: none; 
            -ms-user-select: none; 
            animation: titleGlow 3s ease-in-out infinite alternate;
        }

        @keyframes titleGlow {
            0% { 
                text-shadow: 
                    0 0 10px rgba(255, 255, 255, 0.5),
                    2px 2px 4px rgba(0, 0, 0, 0.3),
                    0 0 30px rgba(255, 107, 157, 0.6);
                transform: scale(1);
            }
            100% { 
                text-shadow: 
                    0 0 20px rgba(255, 255, 255, 0.8),
                    2px 2px 4px rgba(0, 0, 0, 0.3),
                    0 0 50px rgba(255, 107, 157, 1);
                transform: scale(1.02);
            }
        }

        .lock-icon { 
            font-size: 5rem; 
            margin-bottom: 1.5rem; 
            animation: lockPulse 2s ease-in-out infinite, iconFloat 4s ease-in-out infinite; 
            filter: drop-shadow(0 0 20px rgba(255, 255, 255, 0.5));
            user-select: none; 
            -webkit-user-select: none; 
            -moz-user-select: none; 
            -ms-user-select: none; 
        }

        @keyframes lockPulse { 
            0%, 100% { transform: scale(1) rotate(0deg); } 
            50% { transform: scale(1.15) rotate(5deg); } 
        }

        @keyframes iconFloat {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }

        .input-group { 
            position: relative; 
            margin-bottom: 2rem; 
        }

        .input-group::before {
            content: '';
            position: absolute;
            top: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 0;
            height: 2px;
            background: linear-gradient(90deg, transparent, #ffd700, transparent);
            animation: inputShine 2s ease-in-out infinite;
        }

        @keyframes inputShine {
            0%, 100% { width: 0; }
            50% { width: 100%; }
        }

        .input-group input { 
            width: 100%; 
            padding: 18px 25px; 
            border: 2px solid rgba(255, 255, 255, 0.3); 
            border-radius: 50px; 
            font-size: 1.2rem; 
            text-align: center; 
            background: rgba(255, 255, 255, 0.95); 
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1); 
            box-shadow: 
                inset 0 2px 5px rgba(0, 0, 0, 0.1),
                0 8px 25px rgba(0, 0, 0, 0.2);
            user-select: text; 
            -webkit-user-select: text; 
            -moz-user-select: text; 
            -ms-user-select: text; 
            position: relative;
        }

        .input-group input:focus { 
            outline: none; 
            transform: scale(1.05); 
            box-shadow: 
                0 15px 35px rgba(255, 107, 157, 0.4),
                inset 0 1px 0 rgba(255, 255, 255, 0.5);
            background: linear-gradient(135deg, #ffffff 0%, #f8f9fa 100%);
            border-color: #ffd700;
            animation: inputPulse 0.6s ease-out;
        }

        @keyframes inputPulse {
            0% { box-shadow: 0 0 0 0 rgba(255, 215, 0, 0.7); }
            70% { box-shadow: 0 0 0 20px rgba(255, 215, 0, 0); }
            100% { box-shadow: 0 0 0 0 rgba(255, 215, 0, 0); }
        }

        .login-btn { 
            width: 100%; 
            padding: 18px; 
            border: none; 
            border-radius: 50px; 
            background: linear-gradient(45deg, #ff6b9d, #ff8e8e, #ffd93d, #ff6b9d); 
            background-size: 300% 300%;
            animation: buttonGradient 4s ease infinite;
            color: white; 
            font-size: 1.3rem; 
            font-weight: 700; 
            cursor: pointer; 
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1); 
            box-shadow: 
                0 10px 30px rgba(255, 107, 157, 0.5),
                0 0 40px rgba(255, 107, 157, 0.3),
                inset 0 1px 0 rgba(255, 255, 255, 0.3);
            text-transform: uppercase; 
            letter-spacing: 2px; 
            position: relative;
            overflow: hidden;
            user-select: none; 
            -webkit-user-select: none; 
            -moz-user-select: none; 
            -ms-user-select: none; 
        }

        @keyframes buttonGradient {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .login-btn::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.4), transparent);
            transition: left 0.5s;
        }

        .login-btn:hover::before {
            left: 100%;
        }

        .login-btn:hover { 
            transform: translateY(-5px) scale(1.02); 
            box-shadow: 
                0 20px 40px rgba(255, 107, 157, 0.6),
                0 0 60px rgba(255, 107, 157, 0.4);
        }

        .login-btn:active { 
            transform: translateY(-2px) scale(0.98); 
        }

        .heart { 
            position: fixed; 
            font-size: 2.8rem; 
            color: #ff6b9d; 
            text-shadow: 
                0 0 20px rgba(255, 107, 157, 0.8),
                0 0 40px rgba(255, 107, 157, 0.6);
            pointer-events: none; 
            z-index: 60; 
            animation: heartFloat 3s cubic-bezier(0.25, 0.46, 0.45, 0.94) forwards; 
            filter: drop-shadow(0 0 15px currentColor); 
            user-select: none; 
            -webkit-user-select: none; 
            -moz-user-select: none; 
            -ms-user-select: none; 
        }

        @keyframes heartFloat { 
            0% { 
                opacity: 0; 
                transform: translateY(0) scale(0) rotate(0deg) skew(0deg); 
            } 
            10% { 
                opacity: 1; 
                transform: translateY(0) scale(1) rotate(0deg) skew(0deg); 
            }
            50% {
                transform: translateY(-60px) scale(1.2) rotate(180deg) skew(5deg);
            }
            90% { 
                opacity: 1; 
                transform: translateY(-140px) scale(1.1) rotate(180deg) skew(-5deg); 
            } 
            100% { 
                opacity: 0; 
                transform: translateY(-180px) scale(0.6) rotate(360deg) skew(0deg); 
            } 
        }

        .floating-particle { 
            position: fixed; 
            width: 6px; 
            height: 6px; 
            background: radial-gradient(circle, #ffd700 0%, #ff6b9d 100%); 
            border-radius: 50%; 
            pointer-events: none; 
            z-index: 25; 
            box-shadow: 0 0 10px rgba(255, 215, 0, 0.6);
            animation: particleFloat 7s cubic-bezier(0.25, 0.46, 0.45, 0.94) infinite; 
            user-select: none; 
            -webkit-user-select: none; 
            -moz-user-select: none; 
            -ms-user-select: none; 
        }

        @keyframes particleFloat { 
            0% { 
                transform: translateY(100vh) scale(0) rotate(0deg); 
                opacity: 0; 
            } 
            10% { 
                opacity: 1; 
                transform: translateY(90vh) scale(0.5) rotate(90deg); 
            }
            50% {
                transform: translateY(50vh) scale(1) rotate(180deg);
            }
            90% { 
                opacity: 1; 
                transform: translateY(10vh) scale(0.8) rotate(270deg); 
            } 
            100% { 
                transform: translateY(-20px) scale(0) rotate(360deg); 
                opacity: 0; 
            } 
        }

        .sound-control { 
            position: fixed; 
            top: 25px; 
            right: 25px; 
            z-index: 120; 
            background: linear-gradient(135deg, rgba(255, 255, 255, 0.2), rgba(255, 255, 255, 0.1)); 
            border: 2px solid rgba(255, 255, 255, 0.4); 
            border-radius: 50%; 
            width: 70px; 
            height: 70px; 
            color: white; 
            font-size: 1.8rem; 
            cursor: pointer; 
            backdrop-filter: blur(20px) saturate(180%); 
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1); 
            box-shadow: 
                0 10px 30px rgba(0, 0, 0, 0.3),
                0 0 30px rgba(255, 107, 157, 0.3);
            user-select: none; 
            -webkit-user-select: none; 
            -moz-user-select: none; 
            -ms-user-select: none; 
            position: relative;
            overflow: hidden;
        }

        .sound-control::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: radial-gradient(circle at 30% 30%, rgba(255, 255, 255, 0.1) 0%, transparent 50%);
            opacity: 0;
            transition: opacity 0.3s;
        }

        .sound-control:hover::before {
            opacity: 1;
        }

        .sound-control:hover { 
            background: linear-gradient(135deg, rgba(255, 255, 255, 0.3), rgba(255, 255, 255, 0.2)); 
            transform: scale(1.15) rotate(180deg); 
            box-shadow: 
                0 15px 40px rgba(0, 0, 0, 0.4),
                0 0 50px rgba(255, 107, 157, 0.5);
        }

        .birthday-container {
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            z-index: 100; 
            text-align: center;
            opacity: 0;
            transition: all 1s cubic-bezier(0.4, 0, 0.2, 1);
            pointer-events: none;
        }

        .birthday-container.show {
            opacity: 1;
            pointer-events: all;
            animation: containerAppear 1.5s ease-out;
        }

        @keyframes containerAppear {
            0% {
                opacity: 0;
                transform: translate(-50%, -50%) scale(0.5) rotateY(90deg);
            }
            50% {
                opacity: 0.5;
                transform: translate(-50%, -50%) scale(0.8) rotateY(45deg);
            }
            100% {
                opacity: 1;
                transform: translate(-50%, -50%) scale(1) rotateY(0deg);
            }
        }

        .birthday-title { 
            color: white; 
            font-size: 4.2rem; 
            text-align: center; 
            text-shadow: 
                0 0 20px rgba(255, 255, 255, 0.8),
                3px 3px 10px rgba(0, 0, 0, 0.7), 
                0 0 60px rgba(255, 107, 157, 0.9),
                0 0 100px rgba(255, 193, 7, 0.6);
            animation: birthdayGlow 3s ease-in-out infinite alternate, titleFloat 6s ease-in-out infinite; 
            font-weight: 700; 
            letter-spacing: 4px; 
            max-width: 90vw; 
            padding: 0 30px; 
            line-height: 1.1; 
            user-select: none; 
            -webkit-user-select: none; 
            -moz-user-select: none; 
            -ms-user-select: none; 
            display: inline-block;
            font-family: 'Dancing Script', cursive;
            position: relative;
            text-transform: uppercase;
            background: linear-gradient(45deg, #ff6b9d, #ffd93d, #54a0ff, #ff6b9d);
            background-size: 300% 300%;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: textGradient 8s ease infinite;
            pointer-events: none;
        }

        @keyframes textGradient {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        @keyframes titleFloat {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-15px); }
        }

        @keyframes birthdayGlow { 
            0% { 
                text-shadow: 
                    0 0 20px rgba(255, 255, 255, 0.8),
                    3px 3px 10px rgba(0, 0, 0, 0.7), 
                    0 0 60px rgba(255, 107, 157, 0.7),
                    0 0 100px rgba(255, 193, 7, 0.4);
                transform: scale(1);
            } 
            100% { 
                text-shadow: 
                    0 0 30px rgba(255, 255, 255, 1),
                    3px 3px 10px rgba(0, 0, 0, 0.7), 
                    0 0 80px rgba(255, 107, 157, 1),
                    0 0 120px rgba(255, 193, 7, 0.8);
                transform: scale(1.03);
            } 
        }

        .click-btn {
            margin-top: 30px;
            padding: 15px 35px;
            border: none;
            border-radius: 50px;
            background: linear-gradient(45deg, #ff6b9d, #ffd93d, #54a0ff, #ff6b9d);
            background-size: 400% 400%;
            animation: buttonGradient 4s ease infinite;
            color: white;
            font-size: 1.3rem;
            font-weight: 700;
            cursor: pointer;
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            box-shadow: 
                0 15px 35px rgba(255, 107, 157, 0.5),
                0 0 50px rgba(255, 193, 7, 0.3),
                inset 0 1px 0 rgba(255, 255, 255, 0.3);
            text-transform: uppercase;
            letter-spacing: 3px;
            user-select: none;
            -webkit-user-select: none;
            -moz-user-select: none;
            -ms-user-select: none;
            pointer-events: all;
            position: relative;
            z-index: 150;
            display: none;
            overflow: hidden;
            font-family: 'Dancing Script', cursive;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }

        .click-btn::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.4), transparent);
            transition: left 0.6s;
        }

        .click-btn:hover::before {
            left: 100%;
        }

        .birthday-container.show .click-btn {
            display: inline-block;
            animation: 
                pulse 2s ease-in-out infinite,
                buttonFloat 4s ease-in-out infinite;
        }

        .click-btn:hover {
            transform: translateY(-8px) scale(1.05);
            box-shadow: 
                0 25px 50px rgba(255, 107, 157, 0.7),
                0 0 80px rgba(255, 193, 7, 0.5);
        }

        @keyframes buttonFloat {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-5px); }
        }

        /* Image Modal Ultra Graphics */
        .image-modal {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100vh;
            background: 
                linear-gradient(135deg, rgba(0, 0, 0, 0.95) 0%, rgba(20, 0, 40, 0.95) 100%),
                radial-gradient(circle at 20% 20%, rgba(255, 107, 157, 0.3) 0%, transparent 50%),
                radial-gradient(circle at 80% 80%, rgba(255, 193, 7, 0.3) 0%, transparent 50%);
            backdrop-filter: blur(20px) saturate(200%) brightness(0.8);
            display: flex;
            justify-content: center;
            align-items: center;
            z-index: 2000;
            opacity: 0;
            visibility: hidden;
            transition: all 0.6s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .image-modal.show {
            opacity: 1;
            visibility: visible;
            animation: modalExpand 0.8s ease-out;
        }

        @keyframes modalExpand {
            0% {
                transform: scale(0.8);
                opacity: 0;
            }
            100% {
                transform: scale(1);
                opacity: 1;
            }
        }

        .image-container {
            position: relative;
            max-width: 90vw;
            max-height: 90vh;
            transform: scale(0.2) rotateY(90deg);
            transition: all 0.8s cubic-bezier(0.4, 0, 0.2, 1);
            border-radius: 25px;
            overflow: hidden;
            box-shadow: 
                0 30px 60px rgba(0, 0, 0, 0.6),
                0 0 100px rgba(255, 107, 157, 0.5),
                0 0 200px rgba(255, 193, 7, 0.3);
            border: 3px solid rgba(255, 255, 255, 0.3);
            backdrop-filter: blur(10px);
        }

        .image-modal.show .image-container {
            transform: scale(1) rotateY(0deg);
            animation: imagePop 0.8s ease-out;
        }

        @keyframes imagePop {
            0% {
                transform: scale(0.2) rotateY(90deg);
            }
            50% {
                transform: scale(1.1) rotateY(10deg);
            }
            100% {
                transform: scale(1) rotateY(0deg);
            }
        }

        .image-container img {
            width: 100%;
            height: 100%;
            object-fit: contain;
            border-radius: 22px;
            box-shadow: inset 0 0 50px rgba(255, 255, 255, 0.1);
            transition: transform 0.3s ease;
        }

        .image-container:hover img {
            transform: scale(1.02);
        }

        .close-btn {
            position: absolute;
            top: 20px;
            right: 20px;
            background: linear-gradient(135deg, rgba(255, 255, 255, 0.2), rgba(255, 255, 255, 0.1));
            border: 2px solid rgba(255, 255, 255, 0.4);
            border-radius: 50%;
            width: 50px;
            height: 50px;
            color: white;
            font-size: 1.8rem;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            backdrop-filter: blur(15px) saturate(180%);
            z-index: 10;
            box-shadow: 
                0 8px 25px rgba(0, 0, 0, 0.3),
                0 0 30px rgba(255, 107, 157, 0.3);
        }

        .close-btn:hover {
            background: linear-gradient(135deg, rgba(255, 255, 255, 0.3), rgba(255, 255, 255, 0.2));
            transform: scale(1.2) rotate(90deg);
            box-shadow: 
                0 12px 35px rgba(0, 0, 0, 0.4),
                0 0 40px rgba(255, 107, 157, 0.5);
        }

        @keyframes sparkle { 
            0%, 100% { 
                opacity: 0; 
                transform: scale(0) rotate(0deg); 
            } 
            50% { 
                opacity: 1; 
                transform: scale(1.5) rotate(180deg); 
            } 
        }

        .sparkle { 
            position: fixed; 
            width: 8px; 
            height: 8px; 
            background: radial-gradient(circle, #ffd700 0%, #ff6b9d 100%); 
            border-radius: 50%; 
            pointer-events: none; 
            z-index: 60; 
            box-shadow: 
                0 0 20px #ffd700,
                0 0 40px #ffd700;
            animation: sparkle 1.2s ease-out forwards; 
            user-select: none; 
            -webkit-user-select: none; 
            -moz-user-select: none; 
            -ms-user-select: none; 
        }

        @media (max-width: 768px) { 
            .login-container { 
                padding: 2.5rem; 
                margin: 2rem; 
                max-width: 95vw; 
                border-radius: 25px;
            } 
            .login-title { 
                font-size: 2.2rem; 
            } 
            .lock-icon { 
                font-size: 4rem; 
            } 
            .heart { 
                font-size: 2.2rem; 
            } 
            .birthday-title { 
                font-size: 3rem; 
                padding: 0 20px; 
                line-height: 1.2; 
                max-width: 95vw; 
            } 
            .sound-control { 
                width: 60px; 
                height: 60px; 
                font-size: 1.5rem; 
                top: 20px; 
                right: 20px; 
            }
            .click-btn {
                font-size: 1.1rem;
                padding: 12px 25px;
            }
            .image-container {
                max-width: 95vw;
                max-height: 95vh;
                border-radius: 20px;
            }
            .close-btn {
                width: 45px;
                height: 45px;
                font-size: 1.5rem;
                top: 15px;
                right: 15px;
            }
        }

        .loading { 
            display: inline-block; 
            width: 25px; 
            height: 25px; 
            border: 4px solid rgba(255, 255, 255, 0.3); 
            border-radius: 50%; 
            border-top-color: #ffd700; 
            animation: spin 1s ease-in-out infinite; 
            box-shadow: 0 0 20px rgba(255, 215, 0, 0.5);
        }

        @keyframes spin { 
            to { transform: rotate(360deg); } 
        }

        @keyframes shake { 
            0%, 100% { transform: translateX(0); } 
            25% { transform: translateX(-8px); } 
            75% { transform: translateX(8px); } 
        }

        /* Celebration Particles */
        .celebration {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100vh;
            z-index: 200;
            pointer-events: none;
        }

        .confetti {
            position: absolute;
            width: 10px;
            height: 10px;
            background: linear-gradient(45deg, #ff6b9d, #ffd93d);
            animation: confettiFall 3s linear infinite;
        }

        @keyframes confettiFall {
            0% {
                transform: translateY(-100vh) rotate(0deg);
                opacity: 1;
            }
            100% {
                transform: translateY(100vh) rotate(720deg);
                opacity: 0;
            }
        }

        /* Ribbon Animation */
        .ribbon {
            position: fixed;
            top: 20%;
            right: -20%;
            width: 200px;
            height: 60px;
            background: linear-gradient(45deg, #ff6b9d, #ffd93d);
            transform: rotate(45deg);
            z-index: 30;
            animation: ribbonFloat 6s ease-in-out infinite;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }

        @keyframes ribbonFloat {
            0%, 100% { transform: rotate(45deg) translateX(0px); }
            50% { transform: rotate(45deg) translateX(-20px); }
        }
    </style>
</head>
<body>
    <!-- Ultra Background Layers -->
    <div class="background"></div>
    <div class="bg-image"></div>
    <div class="geometric-shapes">
        <div class="shape"></div>
        <div class="shape"></div>
        <div class="shape"></div>
        <div class="shape"></div>
    </div>
    <div class="overlay"></div>
    <div class="lock-bg" id="lockBg"></div>
    <div class="hearts-bg" id="heartsBg"></div>
    <div class="sparkle-system" id="sparkleSystem"></div>
    <div class="ribbon"></div>
    
    <div class="login-modal" id="loginModal">
        <div class="login-container">
            <div class="lock-icon">🎂</div>
            <h2 class="login-title">ورود به جشن تولد</h2>
            <p style="color: rgba(255, 255, 255, 0.95); margin-bottom: 2.5rem; font-size: 1.2rem; user-select: none; -webkit-user-select: none; -moz-user-select: none; -ms-user-select: none; text-shadow: 0 2px 10px rgba(0, 0, 0, 0.3);">رمز عبور را وارد کنید ✨</p>
            <form id="loginForm">
                <div class="input-group">
                    <input type="password" id="passwordInput" placeholder="رمز عبور..." required>
                </div>
                <button type="submit" class="login-btn">
                    <span id="btnText">ورود به جشن ✨</span>
                    <span id="loadingSpinner" class="loading" style="display: none;"></span>
                </button>
            </form>
        </div>
    </div>
    
    <div class="birthday-container" id="birthdayContainer">
        <div class="birthday-title" id="birthdayTitle">🎂 تولدت مبارک کوچولو 🎂</div>
        <button class="click-btn" id="clickBtn">کلیک کن ✨</button>
    </div>

    <button class="sound-control" id="soundToggle" title="کنترل صدا">🔊</button>

    <!-- Ultra Image Modal -->
    <div class="image-modal" id="imageModal">
        <div class="celebration" id="celebration"></div>
        <div class="image-container">
            <img src="https://s6.uupload.ir/files/screenshot_۲۰۲۵۰۹۱۹-۱۷۲۳۵۱_gallery_7zso.jpg" alt="سورپرایز تولد">
            <button class="close-btn" id="closeBtn">✕</button>
        </div>
    </div>

    <script>
        // Security & Zoom Prevention
        document.addEventListener('touchstart', function(event) {
            if (event.touches.length > 1) event.preventDefault();
        }, { passive: false });

        let lastTouchEnd = 0;
        document.addEventListener('touchend', function(event) {
            const now = (new Date()).getTime();
            if (now - lastTouchEnd <= 300) event.preventDefault();
            lastTouchEnd = now;
        }, false);

        ['gesturestart', 'gesturechange', 'gestureend'].forEach(event => {
            document.addEventListener(event, function(e) { e.preventDefault(); });
        });

        ['copy', 'paste', 'cut', 'contextmenu', 'selectstart', 'dragstart'].forEach(event => {
            document.addEventListener(event, function(e) { e.preventDefault(); });
        });

        document.addEventListener('keydown', function(e) {
            if (e.ctrlKey && ['a', 'c', 'v', 's'].includes(e.key)) e.preventDefault();
            if (e.key === 'F12' || e.keyCode === 123) e.preventDefault();
        });

        // Core Variables
        const PASSWORD = "16"; 
        const elements = {
            loginModal: document.getElementById('loginModal'),
            loginForm: document.getElementById('loginForm'),
            passwordInput: document.getElementById('passwordInput'),
            btnText: document.getElementById('btnText'),
            loadingSpinner: document.getElementById('loadingSpinner'),
            birthdayContainer: document.getElementById('birthdayContainer'),
            birthdayTitle: document.getElementById('birthdayTitle'),
            clickBtn: document.getElementById('clickBtn'),
            soundToggle: document.getElementById('soundToggle'),
            lockBg: document.getElementById('lockBg'),
            imageModal: document.getElementById('imageModal'),
            closeBtn: document.getElementById('closeBtn'),
            heartsBg: document.getElementById('heartsBg'),
            sparkleSystem: document.getElementById('sparkleSystem'),
            celebration: document.getElementById('celebration')
        };

        let audio = new Audio('https://dl.sevilmusics.com/cdn/music/srvrf/Miras%20-%20Tavalod%20[SevilMusic].mp3');
        let isPlaying = false, isLoggedIn = false;
        audio.loop = true; audio.volume = 0.4; audio.preload = 'auto';

        // Ultra Particle Systems
        function createSparkleSystem() {
            setInterval(() => {
                if (!isLoggedIn) return;
                for (let i = 0; i < 3; i++) {
                    setTimeout(() => {
                        const sparkle = document.createElement('div');
                        sparkle.className = 'sparkle-particle';
                        sparkle.style.left = Math.random() * 100 + 'vw';
                        sparkle.style.animationDuration = (Math.random() * 2 + 2) + 's';
                        sparkle.style.animationDelay = Math.random() * 3 + 's';
                        elements.sparkleSystem.appendChild(sparkle);
                        setTimeout(() => sparkle.remove(), 5000);
                    }, i * 200);
                }
            }, 2000);
        }

        function createHeartsBackground() {
            setInterval(() => {
                if (!isLoggedIn) return;
                for (let i = 0; i < 2; i++) {
                    setTimeout(() => {
                        const heart = document.createElement('div');
                        heart.className = 'bg-heart';
                        heart.innerHTML = ['💖', '💕', '💗', '💓', '💞', '💝'][Math.floor(Math.random() * 6)];
                        heart.style.left = Math.random() * 100 + 'vw';
                        heart.style.animationDuration = (Math.random() * 4 + 4) + 's';
                        heart.style.animationDelay = Math.random() * 4 + 's';
                        const colors = ['#ff6b9d', '#ff8e8e', '#ffd93d', '#54a0ff', '#ff9ff3', '#feca57'];
                        heart.style.color = colors[Math.floor(Math.random() * colors.length)];
                        elements.heartsBg.appendChild(heart);
                        setTimeout(() => heart.remove(), 8000);
                    }, i * 1000);
                }
            }, 3000);
        }

        function createParticles() { 
            for (let i = 0; i < 8; i++) { 
                setTimeout(() => { 
                    const particle = document.createElement('div'); 
                    particle.className = 'floating-particle'; 
                    particle.style.left = Math.random() * 100 + 'vw'; 
                    particle.style.animationDelay = Math.random() * 6 + 's'; 
                    particle.style.animationDuration = (Math.random() * 3 + 4) + 's'; 
                    document.body.appendChild(particle); 
                    setTimeout(() => particle.remove(), 7000); 
                }, i * 150); 
            } 
        } 

        function createHeart(x, y) { 
            const heart = document.createElement('div'); 
            heart.className = 'heart'; 
            heart.innerHTML = ['💖', '💕', '💗', '💓', '💞', '💝'][Math.floor(Math.random() * 6)]; 
            heart.style.left = x + 'px'; 
            heart.style.top = y + 'px'; 
            const colors = ['#ff6b9d', '#ff8e8e', '#ffd93d', '#54a0ff', '#ff9ff3', '#feca57', '#00d2d3', '#ff9f43']; 
            const randomColor = colors[Math.floor(Math.random() * colors.length)]; 
            heart.style.color = randomColor; 
            heart.style.textShadow = `0 0 30px ${randomColor}, 0 0 50px ${randomColor}`; 
            heart.style.filter = `drop-shadow(0 0 20px ${randomColor})`;
            document.body.appendChild(heart); 
            createSparkle(x, y); 
            setTimeout(() => heart.remove(), 3000); 
        } 

        function createSparkle(x, y) { 
            for (let i = 0; i < 5; i++) { 
                setTimeout(() => { 
                    const sparkle = document.createElement('div'); 
                    sparkle.className = 'sparkle'; 
                    sparkle.style.left = (x + (Math.random() - 0.5) * 60) + 'px'; 
                    sparkle.style.top = (y + (Math.random() - 0.5) * 60) + 'px'; 
                    sparkle.style.animationDelay = (i * 0.15) + 's';
                    sparkle.style.animationDuration = (Math.random() * 0.5 + 0.8) + 's';
                    document.body.appendChild(sparkle); 
                    setTimeout(() => sparkle.remove(), 1500); 
                }, i * 120); 
            } 
        }

        // Ultra Celebration System
        function createCelebration() {
            elements.celebration.innerHTML = '';
            for (let i = 0; i < 50; i++) {
                setTimeout(() => {
                    const confetti = document.createElement('div');
                    confetti.className = 'confetti';
                    confetti.style.left = Math.random() * 100 + 'vw';
                    confetti.style.background = ['linear-gradient(45deg, #ff6b9d, #ffd93d)', 
                                                'linear-gradient(45deg, #54a0ff, #00d2d3)', 
                                                'linear-gradient(45deg, #ff9ff3, #feca57)'][Math.floor(Math.random() * 3)];
                    confetti.style.animationDelay = Math.random() * 3 + 's';
                    confetti.style.animationDuration = (Math.random() * 2 + 2) + 's';
                    elements.celebration.appendChild(confetti);
                    setTimeout(() => confetti.remove(), 4000);
                }, i * 50);
            }
        }

        // Modal Functions
        function showImageModal() {
            createCelebration();
            elements.imageModal.classList.add('show');
            // Ultra celebration effects
            for (let i = 0; i < 15; i++) {
                setTimeout(() => {
                    const offsetX = (Math.random() - 0.5) * window.innerWidth;
                    const offsetY = (Math.random() - 0.5) * window.innerHeight;
                    createHeart(window.innerWidth/2 + offsetX, window.innerHeight/2 + offsetY);
                }, i * 80);
            }
            // Sound effect if possible
            if (audio) audio.volume = 0.6;
        }

        function hideImageModal() {
            elements.imageModal.classList.remove('show');
            if (audio) audio.volume = 0.4;
        }

        // Event Listeners
        elements.clickBtn.addEventListener('click', function(e) {
            e.preventDefault(); e.stopPropagation();
            showImageModal();
        });

        elements.closeBtn.addEventListener('click', function(e) {
            e.preventDefault(); e.stopPropagation();
            hideImageModal();
        });

        elements.imageModal.addEventListener('click', function(e) {
            if (e.target === elements.imageModal) hideImageModal();
        });

        elements.loginForm.addEventListener('submit', function(e) { 
            e.preventDefault(); 
            const password = elements.passwordInput.value.trim();
            if (password === PASSWORD) { 
                elements.btnText.style.display = 'none'; 
                elements.loadingSpinner.style.display = 'inline-block'; 
                setTimeout(() => { 
                    elements.loginModal.classList.add('hidden'); 
                    elements.lockBg.style.opacity = '0'; 
                    elements.lockBg.style.transition = 'opacity 1.5s ease-out'; 
                    elements.lockBg.style.pointerEvents = 'none';
                    setTimeout(() => { 
                        elements.birthdayContainer.classList.add('show');
                        elements.birthdayTitle.classList.add('show'); 
                        isLoggedIn = true; 
                        
                        // Start all particle systems
                        setInterval(createParticles, 2000);
                        createParticles();
                        createSparkleSystem();
                        createHeartsBackground();
                        
                        audio.play().then(() => { 
                            elements.soundToggle.innerHTML = '🔊'; 
                            isPlaying = true; 
                        }).catch(e => console.log('Audio autoplay blocked:', e)); 
                    }, 800); 
                }, 1000); 
            } else { 
                // Enhanced shake animation
                elements.passwordInput.style.border = '3px solid #ff4757'; 
                elements.passwordInput.style.animation = 'shake 0.6s cubic-bezier(0.36, 0.07, 0.19, 0.97) 2'; 
                elements.loginContainer.style.animation = 'shake 0.6s cubic-bezier(0.36, 0.07, 0.19, 0.97) 2'; 
                setTimeout(() => { 
                    elements.passwordInput.style.border = '2px solid rgba(255, 255, 255, 0.3)'; 
                    elements.passwordInput.style.animation = ''; 
                    elements.loginContainer.style.animation = ''; 
                }, 1200); 
            } 
        }); 

        document.addEventListener('click', function(e) { 
            if (!isLoggedIn) return; 
            if (['soundToggle', 'clickBtn', 'closeBtn'].includes(e.target.id) || e.target.classList.contains('click-btn') || e.target.classList.contains('close-btn')) return; 
            
            // Ultra click effect
            createHeart(e.clientX, e.clientY); 
            for (let i = 0; i < 6; i++) { 
                setTimeout(() => { 
                    const offsetX = (Math.random() - 0.5) * 100; 
                    const offsetY = (Math.random() - 0.5) * 100; 
                    createHeart(e.clientX + offsetX, e.clientY + offsetY); 
                }, i * 60); 
            }
            // Additional sparkles
            createSparkle(e.clientX, e.clientY);
        }); 

        elements.soundToggle.addEventListener('click', function() { 
            if (!isLoggedIn) return; 
            if (isPlaying) { 
                audio.pause(); 
                elements.soundToggle.innerHTML = '🔇'; 
                elements.soundToggle.title = 'صدا را روشن کنید'; 
            } else { 
                audio.play().catch(e => { 
                    console.log('Audio error:', e); 
                    alert('موزیک به دلیل محدودیت مرورگر پخش نشد.'); 
                }); 
                elements.soundToggle.innerHTML = '🔊'; 
                elements.soundToggle.title = 'صدا را خاموش کنید'; 
            } 
            isPlaying = !isPlaying; 
        }); 

        // Audio Events
        audio.addEventListener('ended', () => {
            isPlaying = false; 
            elements.soundToggle.innerHTML = '🔇'; 
        }); 

        audio.addEventListener('play', () => {
            isPlaying = true; 
            elements.soundToggle.innerHTML = '🔊'; 
        }); 

        // Input Focus
        elements.passwordInput.focus(); 
        elements.passwordInput.addEventListener('keypress', function(e) { 
            if (e.key === 'Enter') elements.loginForm.dispatchEvent(new Event('submit')); 
        }); 

        // Cleanup System
        setInterval(() => { 
            document.querySelectorAll('.heart, .floating-particle, .sparkle, .bg-heart, .sparkle-particle, .confetti').forEach(el => {
                if (el.getBoundingClientRect().top < -200) el.remove();
            });
        }, 3000); 

        // Initialize
        setTimeout(createParticles, 1500);
        setTimeout(createSparkleSystem, 2000);
    </script>
</body>
</html>۵

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carte de Visite - Belaggoun Hebatallah</title>
    <!-- استدعاء مكتبات التصميم -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <!-- مكتبة QR Code -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>
    <!-- مكتبة تحويل HTML إلى صورة -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js"></script>
    
    <style>
        .flip-card {
            background-color: transparent;
            width: 100%;
            max-width: 450px;
            height: 250px;
            perspective: 1000px;
            cursor: pointer;
            margin: 0 auto;
        }

        .flip-card-inner {
            position: relative;
            width: 100%;
            height: 100%;
            text-align: center;
            transition: transform 0.6s;
            transform-style: preserve-3d;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            border-radius: 0.75rem;
        }

        .flip-card.flipped .flip-card-inner {
            transform: rotateY(180deg);
        }

        .flip-card-front, .flip-card-back {
            position: absolute;
            width: 100%;
            height: 100%;
            -webkit-backface-visibility: hidden;
            backface-visibility: hidden;
            border-radius: 0.75rem;
            overflow: hidden;
        }

        .flip-card-front {
            background-color: white;
            color: black;
        }

        .flip-card-back {
            background-color: #f0fdfa;
            color: black;
            transform: rotateY(180deg);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            border: 2px solid #0d9488;
        }

        .click-hint {
            animation: bounce 2s infinite;
        }
        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
            40% { transform: translateY(-10px); }
            60% { transform: translateY(-5px); }
        }
        
        /* إخفاء أزرار التحميل عند التقاط الصورة */
        .hide-on-download {
            display: flex;
        }
    </style>
</head>
<body class="bg-gray-200 min-h-screen flex flex-col items-center justify-center p-4 font-sans text-gray-800">

    <div class="mb-6 text-center hide-on-download flex-col items-center">
        <h1 class="text-2xl font-bold text-gray-700 mb-2">Carte de Visite Digitale</h1>
        <p class="text-sm text-gray-500 click-hint"><i class="fa-solid fa-hand-pointer mr-2"></i>Cliquez sur la carte pour la retourner</p>
    </div>

    <!-- حاوية البطاقة -->
    <div class="flip-card" id="myCard" onclick="toggleFlip()">
        <div class="flip-card-inner" id="cardInner">
            
            <!-- الوجه الأمامي -->
            <div class="flip-card-front flex flex-col justify-between" id="cardFront">
                <div class="bg-teal-600 text-white p-5 text-left h-2/5 flex flex-col justify-center">
                    <h2 class="text-2xl font-bold tracking-wide">Belaggoun Hebatallah</h2>
                    <p class="text-teal-100 font-medium mt-1 uppercase text-xs tracking-widest"><i class="fa-solid fa-staff-snake mr-2"></i>Vendeuse & Assistante en Pharmacie</p>
                </div>
                
                <div class="bg-white p-5 text-left h-3/5 flex flex-col justify-center space-y-3">
                    <div class="flex items-center text-sm text-gray-700">
                        <div class="w-8 h-8 rounded-full bg-teal-100 text-teal-600 flex items-center justify-center mr-3">
                            <i class="fa-solid fa-phone"></i>
                        </div>
                        <span>(213) 0563 54 50 16</span>
                    </div>
                    <div class="flex items-center text-sm text-gray-700">
                        <div class="w-8 h-8 rounded-full bg-teal-100 text-teal-600 flex items-center justify-center mr-3">
                            <i class="fa-solid fa-envelope"></i>
                        </div>
                        <span>hibatallahbelaggoun@gmail.com</span>
                    </div>
                    <div class="flex items-center text-sm text-gray-700">
                        <div class="w-8 h-8 rounded-full bg-teal-100 text-teal-600 flex items-center justify-center mr-3">
                            <i class="fa-solid fa-location-dot"></i>
                        </div>
                        <span>Hai Mohamed Boudiaf, Es Sénia, Oran</span>
                    </div>
                </div>
            </div>

            <!-- الوجه الخلفي -->
            <div class="flip-card-back p-4 relative" id="cardBack">
                <div class="absolute top-0 left-0 w-full h-2 bg-teal-600"></div>
                
                <h3 class="text-lg font-bold text-teal-800 mb-1">Mon CV Complet</h3>
                <p class="text-xs text-gray-600 mb-4">Scannez ce code pour visualiser mon parcours</p>
                
                <div class="bg-white p-2 rounded-lg shadow-sm border border-gray-200" id="qrcode"></div>
                
                <div class="mt-4 flex flex-wrap justify-center gap-2">
                    <span class="bg-teal-100 text-teal-800 text-[10px] px-2 py-1 rounded-full font-semibold">Logiciel CHIFA</span>
                    <span class="bg-teal-100 text-teal-800 text-[10px] px-2 py-1 rounded-full font-semibold">Gestion de Stock</span>
                    <span class="bg-teal-100 text-teal-800 text-[10px] px-2 py-1 rounded-full font-semibold">Conseil Client</span>
                </div>
            </div>

        </div>
    </div>

    <!-- أزرار التحميل كصورة -->
    <div class="mt-8 flex gap-4 hide-on-download">
        <button onclick="downloadImage('front', event)" class="bg-gray-700 hover:bg-gray-800 text-white px-4 py-2 rounded-lg text-sm transition shadow">
            <i class="fa-solid fa-download mr-2"></i>Télécharger Recto (الأمام)
        </button>
        <button onclick="downloadImage('back', event)" class="bg-teal-600 hover:bg-teal-700 text-white px-4 py-2 rounded-lg text-sm transition shadow">
            <i class="fa-solid fa-download mr-2"></i>Télécharger Verso (الخلف)
        </button>
    </div>

    <script>
        // دالة لقلب البطاقة
        function toggleFlip() {
            document.getElementById('myCard').classList.toggle('flipped');
        }

        // إنشاء كود QR برابط Google Drive الخاص بك
        const cvLink = "https://drive.google.com/file/d/1Iy0Ltcx4wJfwMaulMGkKm1RJ45MAQzoT/view?usp=drivesdk"; 
        new QRCode(document.getElementById("qrcode"), {
            text: cvLink,
            width: 100,
            height: 100,
            colorDark : "#0f766e",
            colorLight : "#ffffff",
            correctLevel : QRCode.CorrectLevel.H
        });

        // دالة تحميل البطاقة كصورة
        function downloadImage(side, event) {
            // منع قلب البطاقة عند النقر على الزر
            event.stopPropagation();
            
            const card = document.getElementById('myCard');
            const elementToCapture = side === 'front' ? document.getElementById('cardFront') : document.getElementById('cardBack');
            
            // التأكد من أن الوجه المطلوب مرئي قبل التقاط الصورة
            if(side === 'front' && card.classList.contains('flipped')) {
                card.classList.remove('flipped');
            } else if (side === 'back' && !card.classList.contains('flipped')) {
                card.classList.add('flipped');
            }

            // ننتظر قليلاً حتى تكتمل حركة الدوران (Animation) ثم نلتقط الصورة
            setTimeout(() => {
                html2canvas(elementToCapture, {
                    scale: 3, // دقة عالية للصورة
                    backgroundColor: side === 'front' ? "#ffffff" : "#f0fdfa",
                    useCORS: true
                }).then(canvas => {
                    const link = document.createElement('a');
                    link.download = `Carte_Visite_${side}_Hebatallah.png`;
                    link.href = canvas.toDataURL('image/png');
                    link.click();
                });
            }, 600); // الانتظار 0.6 ثانية
        }
    </script>
</body>
</html>

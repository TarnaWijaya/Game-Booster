# Download App
Android:
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            background-color: #1a1a1a;
            font-family: Arial, sans-serif;
        }

        .download-button {
            display: inline-block;
            padding: 15px 40px;
            font-size: 20px;
            font-weight: bold;
            color: #fff;
            background: linear-gradient(135deg, #ff0077, #ff7f00);
            text-decoration: none;
            border-radius: 50px;
            box-shadow: 0 8px 16px rgba(255, 127, 0, 0.3);
            transition: all 0.4s ease;
            position: relative;
            overflow: hidden;
        }

        .download-button::before, .download-button::after {
            content: '';
            position: absolute;
            border-radius: 50%;
            transition: all 0.4s ease;
        }

        .download-button::before {
            width: 200%;
            height: 200%;
            background-color: rgba(255, 127, 0, 0.3);
            top: -100%;
            left: 50%;
            transform: translateX(-50%);
            opacity: 0;
            z-index: 0;
        }

        .download-button::after {
            width: 30px;
            height: 30px;
            background-color: rgba(255, 255, 255, 0.3);
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%) scale(0);
            z-index: 0;
        }

        .download-button:hover {
            background: linear-gradient(135deg, #ff7f00, #ff0077);
            box-shadow: 0 10px 20px rgba(255, 127, 0, 0.4);
        }

        .download-button:hover::before {
            top: 50%;
            opacity: 1;
            transform: translate(-50%, -50%) scale(1);
        }

        .download-button:hover::after {
            transform: translate(-50%, -50%) scale(8);
        }

        .download-button span {
            position: relative;
            z-index: 1;
            display: inline-block;
            transition: transform 0.4s ease;
        }

        .download-button:hover span {
            transform: scale(1.1);
        }
    </style>
</head>
<body>
    <a href="https://github.com/namauser/repositori" class="download-button" target="_blank">
        <span>Download di GitHub</span>
    </a>
</body>
</html>
<br>
IOS: Belum Tersedia.
<br>
Windows: Belum Tersedia.
<br>
Lunux: Belum Tersedia.
<p></p>

# Info Update
<p style="margin-bottom: 10px;">
Update info:
  <br>
•Mencepatkan kinerja hp secara paksa
  <br>
•Fps akan stabil jika bermain game ringan
  <br>
•Jika Game Booster diaktifkan hp akan perlahan lahan akan panas
</p>

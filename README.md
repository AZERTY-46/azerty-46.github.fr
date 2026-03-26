<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Se connecter à Microsoft</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Segoe+UI:wght@400;600&display=swap');

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
            background: linear-gradient(135deg, #f0f0f0, #e0e0e0);
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #242424;
        }

        .container {
            background: white;
            width: 420px;
            border-radius: 12px;
            box-shadow: 0 8px 30px rgba(0, 0, 0, 0.12);
            overflow: hidden;
            padding: 40px 40px 50px;
        }

        .header {
            text-align: center;
            margin-bottom: 40px;
        }

        .microsoft-logo {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            font-size: 28px;
            font-weight: 600;
            color: #0078d4;
        }

        .microsoft-logo img {
            width: 32px;
            height: 32px;
        }

        .title {
            font-size: 24px;
            font-weight: 600;
            margin: 20px 0 8px;
        }

        .subtitle {
            color: #666;
            font-size: 15px;
        }

        .form-group {
            margin-bottom: 20px;
        }

        input {
            width: 100%;
            padding: 14px 16px;
            border: 1px solid #8a8a8a;
            border-radius: 6px;
            font-size: 15px;
            transition: all 0.2s;
        }

        input:focus {
            border-color: #0078d4;
            outline: none;
            box-shadow: 0 0 0 2px rgba(0, 120, 212, 0.2);
        }

        .options {
            margin: 12px 0 30px;
        }

        .link {
            color: #0078d4;
            text-decoration: none;
            font-size: 14px;
        }

        .link:hover {
            text-decoration: underline;
        }

        .btn {
            width: 100%;
            background: #0078d4;
            color: white;
            border: none;
            padding: 14px;
            border-radius: 6px;
            font-size: 15px;
            font-weight: 600;
            cursor: pointer;
            transition: background 0.2s;
        }

        .btn:hover {
            background: #106ebe;
        }

        .footer-links {
            text-align: center;
            margin-top: 35px;
            font-size: 13px;
        }

        .footer-links a {
            color: #0078d4;
            margin: 0 8px;
            text-decoration: none;
        }

        .footer-links a:hover {
            text-decoration: underline;
        }

        /* Petit badge "Microsoft" en haut à droite comme sur la vraie page */
        .top-bar {
            position: absolute;
            top: 20px;
            right: 30px;
            font-size: 13px;
            color: #666;
        }
    </style>
</head>
<body>

    <div class="top-bar">Microsoft</div>

    <div class="container">
        <div class="header">
            <div class="microsoft-logo">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/44/Microsoft_logo.svg/512px-Microsoft_logo.svg.png" 
                     alt="Microsoft">
            </div>
            <div class="title">Se connecter</div>
            <div class="subtitle">pour accéder à Microsoft 365</div>
        </div>

        <form>
            <div class="form-group">
                <input type="text" placeholder="E-mail, téléphone ou identifiant Skype" autocomplete="username" required>
            </div>

            <div class="options">
                <a href="#" class="link">Options de connexion</a>
            </div>

            <button type="submit" class="btn">Suivant</button>
        </form>

        <div style="text-align: center; margin: 25px 0 15px;">
            <a href="#" class="link" style="font-size: 14px;">Pas de compte ? Créez-en un !</a>
        </div>

        <div class="footer-links">
            <a href="#">Conditions d’utilisation</a>
            <a href="#">Confidentialité</a>
            <a href="#">Aide</a>
        </div>
    </div>

</body>
</html>

<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>DevoirHome</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:Arial, sans-serif;
    }

    body{
      background:#f4f7fb;
      color:#222;
    }

    header{
      background:#1e3a8a;
      color:white;
      padding:20px;
      text-align:center;
    }

    nav{
      background:#2563eb;
      display:flex;
      justify-content:center;
      gap:20px;
      padding:12px;
      flex-wrap:wrap;
    }

    nav a{
      color:white;
      text-decoration:none;
      font-weight:bold;
    }

    .hero{
      padding:60px 20px;
      text-align:center;
      background:linear-gradient(to right,#2563eb,#3b82f6);
      color:white;
    }

    .hero h1{
      font-size:50px;
      margin-bottom:20px;
    }

    .hero p{
      font-size:20px;
      margin-bottom:30px;
    }

    .btn{
      background:white;
      color:#2563eb;
      padding:14px 25px;
      border:none;
      border-radius:8px;
      cursor:pointer;
      font-size:16px;
      font-weight:bold;
      text-decoration:none;
    }

    .section{
      padding:50px 20px;
    }

    .cards{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:20px;
      margin-top:30px;
    }

    .card{
      background:white;
      padding:25px;
      border-radius:12px;
      box-shadow:0 4px 10px rgba(0,0,0,0.1);
      text-align:center;
    }

    .card h3{
      margin-bottom:15px;
      color:#1e3a8a;
    }

    .login-box{
      max-width:450px;
      margin:auto;
      background:white;
      padding:30px;
      border-radius:15px;
      box-shadow:0 4px 10px rgba(0,0,0,0.1);
    }

    .login-box input,
    .login-box select{
      width:100%;
      padding:12px;
      margin:10px 0;
      border:1px solid #ccc;
      border-radius:8px;
    }

    .login-box button{
      width:100%;
      padding:12px;
      background:#2563eb;
      color:white;
      border:none;
      border-radius:8px;
      cursor:pointer;
      font-size:16px;
    }

    .discussion{
      background:white;
      padding:20px;
      border-radius:12px;
      margin-top:20px;
      box-shadow:0 4px 10px rgba(0,0,0,0.1);
    }

    .message{
      padding:10px;
      margin:10px 0;
      border-radius:8px;
    }

    .parent{
      background:#dbeafe;
    }

    .prof{
      background:#dcfce7;
    }

    footer{
      background:#1e3a8a;
      color:white;
      text-align:center;
      padding:20px;
      margin-top:40px;
    }
  </style>
</head>

<body>

  <header>
    <h1>DevoirHome</h1>
    <p>La plateforme scolaire moderne</p>
  </header>

  <nav>
    <a href="#">Accueil</a>
    <a href="#">Devoirs</a>
    <a href="#">Notes</a>
    <a href="#">Discussion</a>
    <a href="#">Connexion</a>
  </nav>

  <section class="hero">
    <h1>Bienvenue Sur DevoirHome</h1>
    <p>
      Une plateforme pour les élèves, professeurs, parents et direction.
    </p>

    <a class="btn" href="#connexion">
      Commencer
    </a>
  </section>

  <section class="section">
    <h2 style="text-align:center;">Fonctionnalités</h2>

    <div class="cards">

      <div class="card">
        <h3>📚 Devoirs</h3>
        <p>
          Les professeurs peuvent ajouter les devoirs pour les élèves.
        </p>
      </div>

      <div class="card">
        <h3>📝 Notes</h3>
        <p>
          Les notes sont affichées de 0,00 à 20,00.
        </p>
      </div>

      <div class="card">
        <h3>💬 Discussion</h3>
        <p>
          Les parents peuvent discuter avec les professeurs.
        </p>
      </div>

      <div class="card">
        <h3>👨‍🏫 Comptes</h3>
        <p>
          Élève, parent, professeur, directeur et directrice.
        </p>
      </div>

    </div>
  </section>

  <section class="section" id="connexion">
    <h2 style="text-align:center; margin-bottom:30px;">
      Connexion / Création De Compte
    </h2>

    <div class="login-box">

      <input type="text" placeholder="Nom complet">

      <input type="email" placeholder="Adresse email">

      <input type="password" placeholder="Mot de passe">

      <select>
        <option>Choisir un rôle</option>
        <option>Élève</option>
        <option>Professeur</option>
        <option>Parent</option>
        <option>Directeur</option>
        <option>Directrice</option>
      </select>

      <button>
        Se connecter
      </button>

    </div>
  </section>

  <section class="section">
    <h2 style="text-align:center;">
      Discussion Parent - Professeur
    </h2>

    <div class="discussion">

      <div class="message parent">
        Bonjour professeur, mon fils a-t-il fait ses devoirs ?
      </div>

      <div class="message prof">
        Bonjour, oui il a terminé les exercices de mathématiques.
      </div>

    </div>
  </section>

  <section class="section">
    <h2 style="text-align:center; margin-bottom:20px;">
      Exemple Des Notes
    </h2>

    <div class="cards">

      <div class="card">
        <h3>Mathématiques</h3>
        <p>16,50 / 20,00</p>
      </div>

      <div class="card">
        <h3>Français</h3>
        <p>14,00 / 20,00</p>
      </div>

      <div class="card">
        <h3>Sciences</h3>
        <p>18,75 / 20,00</p>
      </div>

    </div>
  </section>

  <footer>
    © 2026 DevoirHome - Tous droits réservés
  </footer>

</body>
</html>
<!-- AJOUTE CE CODE DANS LA PARTIE "Connexion / Création De Compte" -->

<section class="section" id="connexion">
  <h2 style="text-align:center; margin-bottom:30px;">
    Connexion / Création De Compte
  </h2>

  <div class="login-box">

    <input type="text" placeholder="Nom">

    <input type="text" placeholder="Prénom">

    <input type="email" placeholder="Adresse email">

    <input type="tel" placeholder="Numéro de téléphone">

    <input type="password" placeholder="Mot de passe">

    <select>
      <option>Choisir un rôle</option>
      <option>Élève</option>
      <option>Professeur</option>
      <option>Parent</option>
      <option>Directeur</option>
      <option>Directrice</option>
    </select>

    <button>
      Créer un compte
    </button>

  </div>
</section>

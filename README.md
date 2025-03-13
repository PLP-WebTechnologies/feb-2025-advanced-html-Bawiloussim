# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

  # Answers

  <!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multimedia Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1 style="background-color: blue; text-align: center;">Welcome on my page</h1>

    <!-- Element audio -->
   <div style="border: 4cm; ">
    <audio controls>
        <source src="Khaid_-_KUPE__Official_Teaser_Audio__[MT._PsychoZenn](128k).m4a" type="audio/mpeg">
        Votre navigateur ne prend pas en charge l'élément audio.
    </audio>
   </div>

    <!-- Element vidéo -->
    <div>
        <video width="320" height="240" controls>
            <source src="Kocee_x_KS_Bloom_-_Stranger_[Clip_Officiel](360p).mp4" type="video/mp4">
            Votre navigateur ne prend pas en charge l'élément vidéo.
        </video>
    </div>

    <div>
        <!-- Liste ordonnée -->
    <div>
        <ol>
            <li>Premier élément</li>
            <li>Deuxième élément</li>
            <li>Troisième élément</li>
        </ol>
    </div>

<!-- Liste non ordonnée -->
    <div>
        <ul style="">
            <li>First element </li>
            <li>Second element</li>
            <li>third element</li>
        </ul>
    </div>
    </div>

    <div>
        
    <h1>Inscription</h1>
    <form action="#" method="POST">

        <!-- Champ Nom -->
        <label for="name">Name :</label>
        <input type="text" id="name" name="name" placeholder="Entrez votre nom" required><br><br>

        <!-- Champ Email -->
        <label for="email">Email :</label>
        <input type="email" id="email" name="email" placeholder="Entrez votre email" required><br><br>

        <!-- Champ Mot de passe -->
        <label for="password">Password :</label>
        <input type="password" id="password" name="password" placeholder="Entrez votre mot de passe" required><br><br>

        <!-- Champ Date -->
        <label for="birthdate">Date of beath:</label>
        <input type="date" id="birthdate" name="birthdate" required><br><br>

        <!-- Liste déroulante -->
        <label for="country">Pays :</label>
        <select id="country" name="country" required>
            <option value="">Select your country</option>
            <option value="france">France</option>
            <option value="canada">Canada</option>
            <option value="belgium">Belgique</option>
        </select><br><br>

        <!-- Boutons radio -->
        <fieldset>
            <legend>Sex :</legend>
            <label for="male">Man</label>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="female">Woman</label>
            <input type="radio" id="female" name="gender" value="female" required>
        </fieldset><br><br>

        <!-- Cases à cocher -->
        <fieldset>
            <legend>Preferences :</legend>
            <label for="newsletter">login to newsletter :</label>
            <input type="checkbox" id="newsletter" name="newsletter" value="yes"><br><br>
            <label for="terms">Accepte the conditions terms :</label>
            <input type="checkbox" id="terms" name="terms" value="accepted" required><br><br>
        </fieldset>

        <!-- Bouton d'envoi -->
        <input type="submit" value="Login">

    </form>
    </div>
</body>
</html>


>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨

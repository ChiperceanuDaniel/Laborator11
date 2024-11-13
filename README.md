<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feature Repository - Sistem de Gestionare a Elevilor</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
        }
        .feature-list {
            list-style-type: none;
            padding: 0;
        }
        .feature-item {
            background: #e9e9e9;
            margin: 10px 0;
            padding: 15px;
            border-radius: 5px;
        }
        .add-feature-form {
            display: flex;
            flex-direction: column;
        }
        .add-feature-form input,
        .add-feature-form textarea,
        .add-feature-form button {
            margin: 5px 0;
            padding: 10px;
            font-size: 1em;
        }
        .add-feature-form button {
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .add-feature-form button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Feature Repository - Sistem de Gestionare a Elevilor</h1>
        
        <!-- Lista de Funcționalități -->
        <ul class="feature-list">
            <li class="feature-item">Funcționalitate 1: Adaugare Elevi</li>
            <li class="feature-item">Funcționalitate 2: Actualizare Date Elev</li>
            <li class="feature-item">Funcționalitate 3: Acces Profesori la Notele Elevilor</li>
            <li class="feature-item">Funcționalitate 4: Acces Părinți la Rapoartele Elevilor</li>
        </ul>

        <!-- Formular pentru adăugarea unei noi funcționalități -->
        <h2>Adaugă o nouă Funcționalitate</h2>
        <form class="add-feature-form" action="submit_feature.php" method="post">
            <input type="text" name="feature_name" placeholder="Nume Funcționalitate" required>
            <textarea name="feature_description" placeholder="Descriere Funcționalitate" rows="4" required></textarea>
            <button type="submit">Adaugă Funcționalitate</button>
        </form>
    </div>
</body>
</html>


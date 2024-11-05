<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TechNest</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>TechNest</h1>
        <p>Ανακαλύψτε τα τελευταία νέα στην τεχνολογία!</p>
    </header>

    <main>
        <section class="post">
            <h2>Τίτλος Άρθρου 1</h2>
            <p>Εδώ είναι το πρώτο άρθρο με περιγραφή και πληροφορίες για το συγκεκριμένο θέμα.</p>
        </section>
        <section class="post">
            <h2>Τίτλος Άρθρου 2</h2>
            <p>Αυτό είναι το δεύτερο άρθρο του blog με τα πιο πρόσφατα νέα στην τεχνολογία.</p>
        </section>
        <!-- Μπορείς να προσθέσεις περισσότερα άρθρα εδώ -->
    </main>

    <footer>
        <p>&copy; 2024 TechNest. Όλα τα δικαιώματα κατοχυρωμένα.</p>
    </footer>
</body>
</html>


/* Βασικές ρυθμίσεις για την εμφάνιση του site */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #121212;
    color: #ffffff;
    line-height: 1.6;
}

/* Header στυλ */
header {
    text-align: center;
    padding: 20px;
    background-color: #1a1a1a;
    border-bottom: 3px solid #b22222;
}

header h1 {
    font-size: 2.5rem;
    color: #ff3b3b;
}

header p {
    font-size: 1.2rem;
    color: #cccccc;
}

/* Κεντρικό μέρος με τα άρθρα */
main {
    max-width: 800px;
    margin: 20px auto;
    padding: 10px;
}

/* Κάθε άρθρο */
.post {
    background-color: #1c1c1c;
    padding: 20px;
    margin: 20px 0;
    border-radius: 8px;
    border-left: 5px solid #ff3b3b;
}

.post h2 {
    font-size: 1.8rem;
    color: #ff5757;
    margin-bottom: 10px;
}

.post p {
    color: #dddddd;
}

/* Footer στυλ */
footer {
    text-align: center;
    padding: 10px;
    background-color: #1a1a1a;
    color: #888888;
    font-size: 0.9rem;
    border-top: 3px solid #b22222;
}

//html structure

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spotify Clone</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <!-- Spotify logo and navigation bar can be added here -->
    </header>

    <main>
        <section class="playlist">
            <!-- Playlist details and songs go here -->
            <!-- For simplicity, you can add a few sample songs -->
            <div class="song">
                <img src="song1.jpg" alt="Song 1">
                <h3>Song 1</h3>
                <p>Artist 1</p>
            </div>
            <div class="song">
                <img src="song2.jpg" alt="Song 2">
                <h3>Song 2</h3>
                <p>Artist 2</p>
            </div>
            <!-- Add more songs as needed -->
        </section>
    </main>

    <script src="script.js"></script>
</body>
</html>
# s_clone

//css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    /* Style the header with Spotify logo and navigation */
}

.main {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

.playlist {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    grid-gap: 20px;
}

.song {
    text-align: center;
}

.song img {
    width: 100%;
    height: auto;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    cursor: pointer;
}

.song h3 {
    margin: 10px 0;
}

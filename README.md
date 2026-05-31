# Matthew-Kerr
Fun games 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GameHub</title>
<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}
body{
    background:#121212;
    color:white;
}
header{
    background:#1e1e1e;
    padding:20px;
    text-align:center;
}
header h1{
    color:#00ff88;
}
.search-box{
    margin:20px auto;
    max-width:500px;
}
.search-box input{
    width:100%;
    padding:12px;
    border:none;
    border-radius:8px;
}
.games{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
    padding:20px;
}
.game-card{
    background:#222;
    border-radius:12px;
    overflow:hidden;
    transition:.3s;
}
.game-card:hover{
    transform:scale(1.05);
}
.game-card img{
    width:100%;
    height:150px;
    object-fit:cover;
}
.game-card h3{
    padding:10px;
}
.play-btn{
    display:block;
    text-align:center;
    background:#00ff88;
    color:black;
    padding:10px;
    text-decoration:none;
    font-weight:bold;
}
footer{
    text-align:center;
    padding:20px;
    background:#1e1e1e;
}
</style>
</head>
<body>

<header>
    <h1>🎮 GameHub</h1>
    <p>Play Free Browser Games</p>
</header>

<div class="search-box">
    <input type="text" placeholder="Search games...">
</div>

<section class="games">

    <div class="game-card">
        <img src="https://picsum.photos/300/200?1">
        <h3>Racing Game</h3>
        <a href="#" class="play-btn">Play Now</a>
    </div>

    <div class="game-card">
        <img src="https://picsum.photos/300/200?2">
        <h3>Puzzle Game</h3>
        <a href="#" class="play-btn">Play Now</a>
    </div>

    <div class="game-card">
        <img src="https://picsum.photos/300/200?3">
        <h3>Adventure Game</h3>
        <a href="#" class="play-btn">Play Now</a>
    </div>

    <div class="game-card">
        <img src="https://picsum.photos/300/200?4">
        <h3>Action Game</h3>
        <a href="#" class="play-btn">Play Now</a>
    </div>

</section>

<footer>
    © 2026 GameHub
</footer>

</body>
</html>

# My-First-website
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Website Saya</title>
    <style>
        body {
            font-family: Arial;
            background-color: #f4f4f4;
            text-align: center;
        }
        header {
            background: #333;
            color: white;
            padding: 15px;
        }
        .content {
            margin: 20px;
        }
        button {
            padding: 10px 20px;
            background: blue;
            color: white;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>

<header>
    <h1>Selamat Datang di Website Saya</h1>
</header>

<div class="content">
    <p>Ini adalah website sederhana buatan saya.</p>
    <button onclick="halo()">Klik Saya</button>
</div>

<script>
    function halo() {
        alert("Halo! Terima kasih sudah klik 😊");
    }
</script>

</body>
</html>

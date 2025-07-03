# filmes-2
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Galeria de Filmes Favoritos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            text-align: center;
        }
        h1 {
            margin-top: 20px;
        }
        .galeria {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            padding: 20px;
        }
        .galeria a {
            text-decoration: none;
        }
        .galeria img {
            width: 200px;
            height: 300px;
            object-fit: cover;
            border-radius: 10px;
            transition: transform 0.3s;
        }
        .galeria img:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <h1>Meus Filmes Favoritos</h1>
    <div class="galeria">
        <a href="https://pt.wikipedia.org/wiki/Interestelar" target="_blank">
            <img src="imagens/Interestelar.jpg" alt="Interestelar">
        </a>
        <a href="https://pt.wikipedia.org/wiki/O_Senhor_dos_An%C3%A9is:_A_Sociedade_do_Anel" target="_blank">
            <img src="imagens/Senhor-dos-Anéis.jpg" alt="O Senhor dos Anéis">
        </a>
        <a href="https://pt.wikipedia.org/wiki/A_Origem" target="_blank">
            <img src="imagens/A origem.jpg" alt="A Origem">
        </a>
        <a href="https://pt.wikipedia.org/wiki/Clube_da_Luta" target="_blank">
            <img src="imagens/Clube-da-luta.jpg" alt="Clube da Luta">
        </a>
        <a href="https://pt.wikipedia.org/wiki/Pulp_Fiction" target="_blank">
            <img src="imagens/Pulp-fiction.jpg" alt="Pulp Fiction">
        </a>
        <a href="https://pt.wikipedia.org/wiki/Matrix" target="_blank">
            <img src="imagens/Matrix.jpg" alt="Matrix">
        </a>
    </div>
</body>
</html>

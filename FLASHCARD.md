<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flashcards Interativo</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Jogo de Flashcards</h1>
        <div id="flashcard">
            <div id="question">Clique para ver a pergunta</div>
            <div id="answer">Clique para ver a resposta</div>
        </div>
        <div class="controls">
            <button id="next">Próximo</button>
            <button id="edit">Editar Perguntas</button>
        </div>
        <div id="editSection" style="display: none;">
            <h3>Editar Perguntas e Respostas</h3>
            <label for="newQuestion">Pergunta:</label>
            <input type="text" id="newQuestion" placeholder="Digite a nova pergunta">
            <label for="newAnswer">Resposta:</label>
            <input type="text" id="newAnswer" placeholder="Digite a nova resposta">
            <button id="addCard">Adicionar Flashcard</button>
        </div>
    </div>

    <audio id="correctSound">
        <source src="correct.mp3" type="audio/mpeg">
    </audio>
    <audio id="incorrectSound">
        <source src="incorrect.mp3" type="audio/mpeg">
    </audio>

    <script src="script.js"></script>
</body>
</html>
<!---
anarafael1b/anarafael1b is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>HTML5 & CSS3 - Curso em Vídeo</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --bg: #0f172a;
            --card: #1e293b;
            --card-hover: #334155;
            --primary: #38bdf8;
            --text: #f8fafc;
            --muted: #94a3b8;
            --success: #22c55e;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background: var(--bg);
            color: var(--text);
            min-height: 100vh;
        }

        header {
            text-align: center;
            padding: 60px 20px;
            background: linear-gradient(135deg, #0f172a, #1e293b);
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        header p {
            color: var(--muted);
            font-size: 1.1rem;
        }

        .container {
            width: min(1200px, 90%);
            margin: auto;
            padding: 40px 0;
        }

        .stats {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            margin-bottom: 50px;
        }

        .stat-card {
            background: var(--card);
            padding: 20px 30px;
            border-radius: 15px;
            text-align: center;
            min-width: 180px;
            border: 1px solid rgba(255,255,255,0.05);
        }

        .stat-card h3 {
            font-size: 2rem;
            color: var(--success);
        }

        .stat-card p {
            color: var(--muted);
        }

        section {
            margin-bottom: 60px;
        }

        section h2 {
            margin-bottom: 20px;
            color: var(--primary);
            font-size: 2rem;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
            gap: 15px;
        }

        .card a {
            display: block;
            text-decoration: none;
            color: var(--text);
            background: var(--card);
            padding: 20px;
            border-radius: 15px;
            transition: 0.3s;
            border: 1px solid rgba(255,255,255,0.05);
        }

        .card a:hover {
            transform: translateY(-5px);
            background: var(--card-hover);
            box-shadow: 0 10px 25px rgba(0,0,0,.3);
        }

        .emoji {
            font-size: 1.4rem;
            display: block;
            margin-bottom: 10px;
        }

        footer {
            text-align: center;
            padding: 30px;
            color: var(--muted);
            border-top: 1px solid rgba(255,255,255,.1);
        }

        footer a {
            color: var(--primary);
            text-decoration: none;
        }

        @media(max-width: 600px) {
            header h1 {
                font-size: 2rem;
            }

            section h2 {
                font-size: 1.5rem;
            }
        }
    </style>
</head>

<body>

    <header>
        <h1>📚 HTML5 & CSS3</h1>
        <p>Curso em Vídeo • Gustavo Guanabara</p>
    </header>

    <div class="container">

        <div class="stats">
            <div class="stat-card">
                <h3>21</h3>
                <p>Exercícios</p>
            </div>

            <div class="stat-card">
                <h3>10</h3>
                <p>Desafios</p>
            </div>

            <div class="stat-card">
                <h3>31</h3>
                <p>Projetos</p>
            </div>
        </div>

        <section>
            <h2>🚀 Exercícios</h2>

            <div class="grid">

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/exercicio/ex001/"><span class="emoji">📄</span>Exercício 001</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/exercicio/ex002/"><span class="emoji">📄</span>Exercício 002</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/exercicio/ex003/"><span class="emoji">📄</span>Exercício 003</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/exercicio/ex004/"><span class="emoji">📄</span>Exercício 004</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/exercicio/ex006/"><span class="emoji">📄</span>Exercício 006</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/exercicio/ex007/"><span class="emoji">📄</span>Exercício 007</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/exercicio/ex008/"><span class="emoji">📄</span>Exercício 008</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/exercicio/ex009/"><span class="emoji">📄</span>Exercício 009</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/exercicio/ex010/"><span class="emoji">📄</span>Exercício 010</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/exercicio/ex011/"><span class="emoji">📄</span>Exercício 011</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/exercicio/ex012/"><span class="emoji">📄</span>Exercício 012</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/exercicio/ex013/"><span class="emoji">📄</span>Exercício 013</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/exercicio/ex014/"><span class="emoji">📄</span>Exercício 014</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/exercicio/ex015/"><span class="emoji">📄</span>Exercício 015</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/exercicio/ex016/"><span class="emoji">📄</span>Exercício 016</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/exercicio/ex017/"><span class="emoji">📄</span>Exercício 017</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/exercicio/ex018/fonte01.html"><span class="emoji">📄</span>Exercício 018</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/exercicio/ex019/seletor01.html"><span class="emoji">📄</span>Exercício 019</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/exercicio/ex020/links.html"><span class="emoji">📄</span>Exercício 020</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/exercicio/ex021/caixa01.html"><span class="emoji">📄</span>Exercício 021</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/exercicio/ex022/"><span class="emoji">📄</span>Exercício 022</a></div>

            </div>
        </section>

        <section>
            <h2>🎯 Desafios</h2>

            <div class="grid">

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/desafios/desafio%201/"><span class="emoji">🏆</span>Desafio 1</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/desafios/desafio%202/"><span class="emoji">🏆</span>Desafio 2</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/desafios/desafio%203/"><span class="emoji">🏆</span>Desafio 3</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/desafios/desafio%204/"><span class="emoji">🏆</span>Desafio 4</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/desafios/desafio%205/"><span class="emoji">🏆</span>Desafio 5</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/desafios/desafio%206/"><span class="emoji">🏆</span>Desafio 6</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/desafios/desafio%207/"><span class="emoji">🏆</span>Desafio 7</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/desafios/desafio%208/"><span class="emoji">🏆</span>Desafio 8</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/desafios/desafio%209/"><span class="emoji">🏆</span>Desafio 9</a></div>

                <div class="card"><a href="https://cmddiogo171.github.io/HTML5-CSS/desafios/desafio%2010/android.html"><span class="emoji">🏆</span>Desafio 10</a></div>

            </div>
        </section>

    </div>

    <footer>
        Desenvolvido por <strong>Diogo Ribeiro</strong> 🚀 <br>
        Curso HTML5 e CSS3 - Curso em Vídeo
    </footer>

</body>

</html>
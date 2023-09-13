# MyClass
<html>
<head>
    <title>MyClass</title>
</head>
<div class="scroller">
    <ol>
        <li style="--bg: url(https://proprikol.ru/wp-content/uploads/2020/07/kartinki-znak-voprosa-1.jpg)">
            <h2>Пока пусто</h2>
            <p>Пока пусто</p>
        </li>
        <li style="--bg: url(https://spaceholder.cc/i/600x800?2)">
            <h2>Пока пусто</h2>
            <p>Пока пусто</p>
        </li>
        <li style="--bg: url([https://spaceholder.cc/i/600x800?3](https://proprikol.ru/wp-content/uploads/2020/07/kartinki-znak-voprosa-17.jpg))">
            <h2>Пока пусто</h2>
            <p>Пока пусто</p>
        </li>
        <li style="--bg: url([https://spaceholder.cc/i/600x800?4](https://proprikol.ru/wp-content/uploads/2020/07/kartinki-znak-voprosa-17.jpg))">
            <h2>Пока пусто</h2>
            <p>Пока пусто</p>
        </li>
        <li style="--bg: url([https://spaceholder.cc/i/600x800?5](https://proprikol.ru/wp-content/uploads/2020/07/kartinki-znak-voprosa-17.jpg))">
            <h2>Пока пусто</h2>
            <p>Пока пусто</p>
        </li>
        <li style="--bg: url([https://spaceholder.cc/i/600x800?6](https://proprikol.ru/wp-content/uploads/2020/07/kartinki-znak-voprosa-17.jpg))">
            <h2>Пока пусто</h2>
            <p>Пока пусто</p>
        </li>
        <li style="--bg: url([https://spaceholder.cc/i/600x800?7](https://proprikol.ru/wp-content/uploads/2020/07/kartinki-znak-voprosa-17.jpg))">
            <h2>Пока пусто</h2>
            <p>Пока пусто</p>
        </li>
        <li style="--bg: url([https://spaceholder.cc/i/600x800?8](https://proprikol.ru/wp-content/uploads/2020/07/kartinki-znak-voprosa-17.jpg))">
            <h2>Пока пусто</h2>
            <p>Пока пусто</p>
        </li>
        <li style="--bg: url(https://proprikol.ru/wp-content/uploads/2020/07/kartinki-znak-voprosa-17.jpg)">
            <h2>Пока пусто</h2>
            <p>Пока пусто</p>
        </li>
        <li style="--bg: url([https://spaceholder.cc/i/600x800?1](https://proprikol.ru/wp-content/uploads/2020/07/kartinki-znak-voprosa-17.jpg))">
            <h2>Пока пусто</h2>
            <p>Пока пусто</p>
        </li>
        <li style="--bg: url([https://spaceholder.cc/i/600x800?2](https://proprikol.ru/wp-content/uploads/2020/07/kartinki-znak-voprosa-17.jpg))">
            <h2>Пока пусто</h2>
            <p>Пока пусто</p>
        </li>
        <li style="--bg: url([https://spaceholder.cc/i/600x800?3](https://proprikol.ru/wp-content/uploads/2020/07/kartinki-znak-voprosa-17.jpg))">
            <h2>Пока пусто</h2>
            <p>Пока пусто</p>
        </li>
        <li style="--bg: url([https://spaceholder.cc/i/600x800?4](https://proprikol.ru/wp-content/uploads/2020/07/kartinki-znak-voprosa-17.jpg))">
            <h2>Пока пусто</h2>
            <p>Пока пусто</p>
        </li>
        <li style="--bg: url(https://proprikol.ru/wp-content/uploads/2020/07/kartinki-znak-voprosa-17.jpg)">
            <h2>Пока пусто</h2>
            <p>Пока пусто</p>
        </li>
        <li style="--bg: url([https://spaceholder.cc/i/600x800?6](https://proprikol.ru/wp-content/uploads/2020/07/kartinki-znak-voprosa-17.jpg))">
            <h2>Пока пусто</h2>
            <p>Пока пусто</p>
        </li>
        <li style="--bg: url([https://spaceholder.cc/i/600x800?7](https://proprikol.ru/wp-content/uploads/2020/07/kartinki-znak-voprosa-17.jpg))">
            <h2>Пока пусто</h2>
            <p>Пока пусто</p>
        </li>
        <li style="--bg: url([https://spaceholder.cc/i/600x800?8](https://proprikol.ru/wp-content/uploads/2020/07/kartinki-znak-voprosa-17.jpg))">
            <h2>Пока пусто</h2>
            <p>Пока пусто</p>
        </li>
        <li style="--bg: url([https://spaceholder.cc/i/600x800?9](https://proprikol.ru/wp-content/uploads/2020/07/kartinki-znak-voprosa-17.jpg))">
            <h2>Пока пусто</h2>
            <p>Пока пусто</p>
        </li>
    </ol>
</div>
<style>
body {
    background-color: #000;
    color: #fff;
    font-family: sans-serif;
    line-height: 1.6;
    background: radial-gradient(
        ellipse at top center,
        #310038 0%,
        #000000 100%
    );
    background-size: cover;
    min-height: 100vh;
    margin: 0;
}

.scroller {
    overflow: auto;
    padding: 1rem;
    scroll-timeline-name: --scroller;
    scroll-timeline-axis: inline;
}

ol,
ul {
    //   display: grid;
    //   grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
    // grid-gap: 1rem;
    display: flex;
    gap: 1rem;
    list-style: none;
    padding-left: 0;
    counter-reset: list-item;
    perspective: 9000px;
    transform-style: preserve-3d;
    perspective-origin: 50% 50%;

    > li {
        flex: 1 1 240px;
        min-width: 240px;
        border: 1px solid currentColor;
        padding: 1rem;
        animation: auto ease-in-out intro forwards,
            auto ease-in-out outro forwards;
        animation-timeline: view(inline);
        animation-range: entry, exit;
        transform-origin: bottom center;
    }

    p,
    h2 {
        margin-top: 1rem;
        margin-bottom: 0;
    }

    h2 {
        color: #aaa;
        font-weight: normal;
    }
}

ol > li {
    display: flex;
    flex-direction: column;
    color: #ccc;
    position: relative;
    overflow: hidden;

    &::before {
        counter-increment: list-item;
        content: counter(list-item) ".";
        font-size: 5em;
        font-weight: bold;
        color: #fff;
        margin-bottom: 1rem;
        line-height: 1;
    }

    &::after {
        content: "";
        background-image: var(--bg);
        position: absolute;
        inset: -20px;
        background-size: cover;
        transform: scale(1);
        transition: transform 0.5s ease-out, opacity 0.4s linear;
        opacity: 0;
        z-index: -1;
    }

    &:hover {
        color: #fff;
        &::after {
            transform: scale(1.1) rotate(4deg);
            opacity: 0.8;
        }
    }
}

// Play with the intro and outro animations!

@keyframes intro {
    from {
        transform-origin: center left;
        opacity: 0;
        scale: 0;
        // rotate: z -90deg;
        // translate: 0 -100%;
    }
    to {
        transform-origin: center left;
        opacity: 1;
        scale: 1;
        // rotate: z 0deg;
        // translate: 0 0;
    }
}

@keyframes outro {
    from {
        transform-origin: center right;
        opacity: 1;
        scale: 1;
        // translate: 0 0;
    }
    to {
        transform-origin: center right;
        opacity: 0;
        scale: 0;
        // translate: 0 100%;
    }
}

</style>

<body>
    <h1>Hello, World!</h1>
    
    <button onclick="openNewScript()">Открыть другой скрипт</button>

    <script>
        function openNewScript() {
            window.location.href = 'main.html';
        }
    </script>
    <p id="textContainer">okay</p>
    <a href="http://192.168.0.105:80/hello">Download Maj++ 9.0</a>
</body>
</html>


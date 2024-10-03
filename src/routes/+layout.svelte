<nav class="app-menu">
    <header class="app-menu_header">
        <a href="/">
            <img class="app-menu_header-logo" src="{logo}" alt="Wuthering Waves logo">
        </a>
        <span class="app-menu_header-title">Wuthering Waves</span>
        <span class="app-menu_header-subtitle">Companion</span>
    </header>
    <ul class="app-menu_nav">
        <li><a href="/new">What's new?</a></li>
        <li><a href="/characters">Characters</a></li>
        <li><a href="/echoes">Echoes</a></li>
        <li><a href="/weapons">Weapons</a></li>
        <li><a href="/items">Items</a></li>
        <li><a href="/events">Events</a></li>
        <li><a href="/map">Map</a></li>
    </ul>
    <footer class="app-menu_footer">
        <span class="app-menu_footer-version">v0.0.1</span>
    </footer>
</nav>

<main class="app">
    <slot></slot>
</main>

<script>
    import '../app.css';

    import logo from '$lib/images/logo.png'
</script>
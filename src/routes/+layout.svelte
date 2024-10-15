<script>
    import github from '$lib/images/github.svg';
    import linkedin from '$lib/images/linkedin.svg';
    import './layout.css';
</script>

<header>
    <p class="jm">Julien Mauré</p>
    <nav>
	    <a href="/">Accueil</a>
	    <a href="/about">Présentation</a>
	    <a href="/cv">Mon CV</a>
    </nav>
    <div class='logo'>
        <a href="https://www.linkedin.com/in/julien-maur%C3%A9-9b0b8b255/">
            <img src={linkedin} alt="LinkedIn" />
        </a>
    </div>
</header>

<slot></slot>

<!-- <footer>
    <div class="foot">
        <div class='logo'>
            <a href="https://github.com/sveltejs/kit">
                <img src={github} alt="GitHub" />
            </a>
        </div>
        <div class='logo'>
            <a href="https://www.linkedin.com/in/julien-maur%C3%A9-9b0b8b255/">
                <img src={linkedin} alt="LinkedIn" />
            </a>
        </div>
    </div>
</footer> -->
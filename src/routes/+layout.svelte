<header>
    <h1>Aidan Roig</h1>
    <!-- <a href="#" class="toggle-button">
        <span class="bar"></span>
        <span class="bar"></span>
        <span class="bar"></span>
    </a> -->
    <nav>
        <ul>
            <li><a href="/">About Me</a></li>
            <li><a href="/resume">Resume</a></li>
            <li><a href="/projects">Projects</a></li>
            <li><a href="/contact">Contact</a></li>
        </ul>
    </nav>
</header>

<slot />

<footer>
    <ul>
        <li>
            <a href="https://github.com/aroig1" target="_blank">
                <img src="/images/github.png" alt="GitHub link">
            </a>
        </li>
        <li>
            <a href="mailto:aroig@arizona.edu" target="_blank">
                <img src="/images/email.png" alt="Link to Email">
            </a>
        </li>
        <li>
            <a href="https://www.linkedin.com/in/aidan-javier-roig/" target="_blank">
                <img src="/images/linkedin.png" alt="Link to LinkedIn">
            </a>
        </li>
    </ul>
</footer>

<style>
    * {
        margin: 0;
        padding: 0;
    }

    header {
        background-color:#292526;
        padding: 5% 0 0 0;
        display: flex;
        align-items: flex-end;
        justify-content: space-between;
    }

    header h1 {
        padding: 0 5%;
        color:#de9e48;
        font-size: 50px;
    }

    nav {
        flex-grow: 1;
    }

    nav ul {
        display: flex;
        justify-content: end;
    }

    nav ul li {
        list-style: none;
        text-align: center;
        padding: 1% 5%;
    }

    nav li a {
        display: block;
        color: white;
        text-decoration: none;
    }

    nav li:hover {
        background-color:#de9e48;
    }

    footer {
        background-color: #292526;
        padding: 10px 0;
    }

    footer ul {
        display: flex;
        justify-content: center;
    }

    footer ul li {
        display: block;
        margin: 0 20px;
    }

    footer img {
        width: 60px;
        height: 60px;
    }
</style>
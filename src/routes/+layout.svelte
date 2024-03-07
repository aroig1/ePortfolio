<header class="main-header">
    <div class="main-header-container">
        <h1>Aidan Roig</h1>
        <!-- <a href="#" class="toggle-button">
            <span class="bar"></span>
            <span class="bar"></span>
            <span class="bar"></span>
        </a> -->
        <nav class="nav">
            <ul>
                <li><a href="/">About Me</a></li>
                <li><a href="/resume">Resume</a></li>
                <li><a href="/projects">Projects</a></li>
                <li><a href="/contact">Contact</a></li>
            </ul>
        </nav>
    </div>
</header>

<slot />

<footer>
    <div class="footer-container">
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
    </div>
</footer>

<style>
    @import './styles.css';
</style>
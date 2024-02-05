<body>
    <div class="container">
        <div align="center">
            <h1>Hey 👋, I'm Dante Rodríguez</h1>
        </div>
        <h2 class="intro" align="center">Passionate technology student always eager to strengthen and expand his skills in this fascinating
            field.
        </h2>
    </div>
    <div class="info">
        <!-- cards terminal -->
        <div class="card">
            <div class="tools">
                <div class="circle">
                    <span class="red box"></span>
                </div>
                <div class="circle">
                    <span class="yellow box"></span>
                </div>
                <div class="circle">
                    <span class="green box"></span>
                </div>
            </div>
            <div class="card__content">
                <p> > Actualmente me encuentro cursando mi ultimo ciclo de estudios </p>
                <p> > Soy estudiante en TECSUP</p>
            </div>
        </div>
    </div>
    <!-- Social media -->
    <div class="social">
        <nav>
            <a href="https://www.linkedin.com/in/dante-samuel-rodriguez-chambi-444041279/">
                <img class="social-icon" src="/images/linkedin.svg" alt="">
            </a>
            <a href="https://www.facebook.com/profile.php?id=100041512209159">
                <img class="social-icon" src="/images/facebook.svg" alt="">
            </a>
            <a href="https://www.instagram.com/dantesamuelrodriguez/">
                <img class="social-icon" src="/images/instagram.svg" alt="">
            </a>
        </nav>
    </div>
    <div class="skills">
        <div class="skills-title">
            <img src="/images/skills.svg" alt="">
            <h1>Languages & Frameworks & Tools & Abilities</h1>
        </div>
        <nav>
            <a href="">
                <img class="icon" src="/images/html.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/css.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/javascript.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/typerscript.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/tailwind.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/bootstrap.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/python.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/php.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/flutter.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/kotlin.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/react.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/angular.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/astro.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/materialui.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/django.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/npm.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/pnpm.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/node.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/spring.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/express.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/sqllite.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/supabase.svg" alt="">
            </a>
            <a href="">
                <img class="icon2" src="/images/mngodb.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/mysql.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/netlify.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/nextjs.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/vercel.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/vscode.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/android.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/github.svg" alt="">
            </a>
            <a href="">
                <img class="icon" src="/images/git.svg" alt="">
            </a>
        </nav>
    </div>
</body>

<style>
    @font-face {
    font-family: 'Onest Variable';
    font-style: normal;
    font-display: swap;
    font-weight: 100 900;
    src: url(https://cdn.jsdelivr.net/fontsource/fonts/onest:vf@latest/latin-wght-normal.woff2) format('woff2-variations');
    unicode-range: U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+0304,U+0308,U+0329,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD;
    }
    body{
        font-family: 'Onest Variable', sans-serif;
    }
    .info {
        display: flex;
        justify-content: center;
    }

     /* card */
    .card {
        width: 300px;
        height: 154px;
        margin: 0 auto;
        background-color: #011522;
        border-radius: 8px;
        z-index: 1;
    }

    .tools {
        display: flex;
        align-items: center;
        padding: 9px;
    }

    .circle {
        padding: 0 4px;
    }

    .box {
        display: inline-block;
        align-items: center;
        width: 10px;
        height: 10px;
        padding: 1px;
        border-radius: 50%;
    }

    .red {
        background-color: #ff605c;
    }

    .yellow {
        background-color: #ffbd44;
    }

    .green {
        background-color: #00ca4e;
    }

    .card__content {
        color: white;
        margin-left: 1rem;
    }
    .social{
        display: flex;
        justify-content: center;
        align-items: center;
        margin-top: 1rem;
    }
    .social-icon{
        width: 40px;
    }
    nav {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap;
        margin-top: 0.5rem;
    }
    
    .skills-title {
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 1.2rem;
    }

    .social-icon,.icon, .icon2 {
        margin: 0 10px;
    }

    .icon {
        width: 40px;
    }

    .icon2 {
        width: 20px;
    }   
</style>

<!DOCTYPE html>
<html>
    <body>
        <section id="profile">
            <div class="row">
                <h1>👋 "Hello, World!"</h1>
                <div class="left-col">
                    <img class="avatar" src="https://avatars.githubusercontent.com/u/85803896?v=4" alt="Profile Avatar" />
                    <a href="https://github.com/Maria-Papa">
                        <img src="https://visitcount.itsvg.in/api?id=Maria-Papa&icon=8&color=6" alt="Profile Views"/>
                    </a>
                    <a href="https://linkedin.com/in/papadopoulou-maria">
                        <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" alt="LinkedIn"/>
                    </a>
                </div>
                <div class="right-col">
                    <p>
                        I'm Maria, a PHP Backend Developer currently working for SchooX!!
                        <br>
                        <br>
                        😄 <b>Pronouns:</b> She/Her
                        <br>
                        🌱 <b>Currently Learning:</b> Python & C#
                        <br>
                        💭 <b>Looking For:</b> Ideas for small apps 
                        <br>
                        💥 <b>Passionate About:</b> Experimenting with code
                        <br>
                        ❤️ <b>Loves:</b> Traveling, Music, Gaming, Food, Dark Themes, Reading (On/Off-line)
                    </p>
                </div>
            </div>
        </section>
        <section id="tech-stack">
            <h1>💻 Tech Stack</h1>
            <h2>Backend</h2>
            <img src="https://skillicons.dev/icons?i=php,cs,py" alt="Backend Skills" />
            <h2>Frontend</h2>
            <img src="https://skillicons.dev/icons?i=laravel,vue,bootstrap,js,html" alt="Frontend Skills" />
            <h2>Databases</h2>
            <img src="https://skillicons.dev/icons?i=mysql,mongodb" alt="Database Skills" />
        </section>
        <section id="tech-stack">
            <h1>📊 GitHub Stats</h1>
            <div class="wrapper">
                <div class="items-left">
                    <img src="https://github-readme-stats.vercel.app/api?username=Maria-Papa&theme=tokyonight&hide_border=false&include_all_commits=true&count_private=true" />
                    <br>
                    <img src="https://github-readme-streak-stats.herokuapp.com/?user=Maria-Papa&theme=tokyonight&hide_border=false" />
                </div>
                <div class="items-right">
                    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Maria-Papa&theme=tokyonight&hide_border=false&include_all_commits=true&count_private=true&langs_count=5" />
                </div>
            </div>
        </section>
        <section id="trophies">
            <h1>🏆 Trophies</h1>
            <h2>GitHub</h2>
            <img src="https://github-profile-trophy.vercel.app/?username=Maria-Papa&theme=tokyonight&no-frame=false&no-bg=true&margin-w=4" width="50%" />
            <h2>Holopin</h2>
            <img src="https://holopin.me/mariapapadopoulou" alt="@mariapapadopoulou's Holopin board" width="50%" />
        </section>
    </body>
    <style>
        section {
            margin-bottom: 50px;
        }
        .avatar {
            border-radius: 50%;
            height: 120px;
            margin-bottom: 20px;
        }
        .left-col {
            float: left;
            width: 10%;
            text-align: center;
        }
        .right-col {
            position: relative;
            height: 200px;
        }
        .right-col p {
            margin: 0;
            position: absolute;
            top: 50%;
            left: 27%;
            transform: translate(-50%, -50%);
        }
        .row:after {
            content: "";
            display: table;
            clear: both;
        }
        .wrapper {
            display: grid;
            grid-template-areas: "l r .";
            align-items: stretch;
            width: 50%;
            grid-gap: 10px;
        }
        .items-left { grid-area: l; }
        .items-right { grid-area: r; }
        .items-left img, .items-right img {
            width: 100%;
        }
    </style>
</html>

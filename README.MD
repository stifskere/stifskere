<style>
            @import url('https://fonts.cdnfonts.com/css/cascadia-code');
            @import url('https://fonts.googleapis.com/css2?family=Mukta&display=swap');
            @import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono&display=swap');
            body, html {
                height: 100%;
                width: 100%;
                margin: 0;
                position: absolute;
                top: 0;
                left: 0;
                color: white;
            }
            .mainCode {
                background-color: rgba(0, 0, 0);
                display: flex;
                flex-direction: column;
                margin: 1vh 1vw;
                padding: 1vh 1vw;
                border-radius: 8px;
            }
            .command, .commandInstruction {
                margin: 0.5vh 0 0;
            }
            .commandInstruction {
                font-family: 'Cascadia Code', sans-serif;
            }
            .commandPre {
                color: #55a832;
            }
            .commandResponse {
                margin-left: 3vw;
            }
            .intro {
                margin: 0;
                border: 0;
                background-color: transparent;
            }
            .cursor {
                animation: cursor 1s cubic-bezier(1,-1, 0, 2) infinite;
            }
            @keyframes cursor {
                0%{
                    color: black;
                }
                50% {
                    color: white;
                }
                100% {
                    color: black;
                }
            }
            .featured {
                display: flex;
                gap: 1vw;
                margin: 1vw
            }
            .featuredPanel {
                flex: 1 1 0;
                border-radius: 8px;
            }
            .memwWebParent {
                background: linear-gradient(145deg, rgb(35, 35, 35) 0%, rgb(17, 17, 17) 50%, rgba(0, 0, 0, 1) 100%) no-repeat;
            }
            .memwWeb {
                font-family: 'Mukta', sans-serif;
                font-weight: bold;
                text-align: center;
                background: url("stars.png") no-repeat fixed center center;
                background-size: cover;
                margin: 5vh 0;
                padding: 0;
            }
            .memwWeb h1 {
                font-size: 3em;
                margin: -1vh 0 0;
            }
            .memwWeb p {
                margin: -2vh 0 0;
            }
            .memwLib {
                background-color: #262626;
                color: white;
                display: flex;
                align-items: center;
                justify-content: center;
                font-family: 'JetBrains Mono', monospace;
            }
            .codeModifier {
                color: #6085d3;
            }
            .codeString {
                color: #c69f66;
            }
            .codeMemberName {
                color: #b284ea;
            }
            .codeOperator {
                color: #2ccc8c;
            }
            .coolBackground {
                height: 30vh;
                background-repeat: repeat-x;
                background-image: url("./coolgif.gif");
                margin: 0 1vw;
                border-radius: 8px;
            }
</style>
<div class="mainCode">
<div class="command">
<p class="commandInstruction"><span class="commandPre">memw@github-readme:~$</span> ./userinfo</p>
<div class="commandResponse">
<pre class="intro">
    __  ___
   /  |/  /__  ____ ___ _      __       Hello, I'm Esteve, a 17-year-old
  / /|_/ / _ \/ __ `__ \ | /| / /       full-stack web developer. utilizing a
 / /  / /  __/ / / / / / |/ |/ /        diverse skill set that includes languages
/_/  /_/\___/_/ /_/ /_/|__/|__/         such as C#, TypeScript, Python, and C++
</pre>
</div>
</div>
<div class="command">
<p class="commandInstruction"><span class="commandPre">memw@github-readme:~$</span><span class="cursor"> &block;</span></p>
</div>
</div>
<div class="featured">
<!-- linear-gradient(145deg, rgb(35, 35, 35) 0%, rgb(17, 17, 17) 30%, rgba(0, 0, 0, 1) 100%) no-repeat; -->
<div class="memwWebParent featuredPanel">
<div class="memwWeb">
<h1>MEMW</h1>
<p>Read more about me.</p>
</div>
</div>
<div class="memwLib featuredPanel">
<pre>
<span class="codeModifier">public static class</span> <span class="codeMemberName">MemwLib</span>
{
<span class="codeModifier">public static string</span> Description
<span class="codeOperator">=</span> <span class="codeString">"Another utils library for c#"</span>;
}
</pre>
</div>
</div>
<div class="coolBackground"></div>

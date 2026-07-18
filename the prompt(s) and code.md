the prompts i placed on  Chatgpt 
For my Devconf landing Page project which is only Using HTML and CSS , I need a section and a idea than is convay the topic Heckathon, Innovation wall,  projects showcase and sign up , mixed up that all  in a unique way that is blend with the project . Color preferance is  #0D1B2A, White and black . Design it  a way that dosen't affact the original code and codes are simple and natural and minimalistic both CSS and HTML are . 

 ---------------------------------------------------------
| CREATE • BUILD • SHARE         |  Hackathon            |
|                                |-----------------------|
| Hackathon & Innovation Hub     |  Innovation Wall      |
|                                |-----------------------|
| Short description...           |  Project Showcase     |
|                                |                       |
| [ Register Now ]               |                       |
 ---------------------------------------------------------
 its gives me the mayout and code 


 ok thats great but ineed it only using HTML and CSS grid and flex not more advance one 
 i modified it with this prompet 

 +----------------------------------------------------+
|                                                    |
| BUILD • SHARE • INSPIRE                            |
|                                                    |
| Build the Future                                   |
| Hackathon + Innovation Wall + Showcase             |
|                                                    |
| [ Register ]                                       |
|                                                    |
| +----------------+  +----------------+             |
| | Hackathon      |  | Innovation     |             |
| |                |  | Wall           |             |
| +----------------+  +----------------+             |
|                                                    |
| +----------------------------------------------+   |
| | Project Showcase          [ Join Now ]        |   |
| +----------------------------------------------+   |
|                                                    |
+----------------------------------------------------+

make it more precise and shorter 

 --------------------------------------------------------------
| BUILD • SHARE • INSPIRE                                     |
|                                                             |
| Hackathon & Innovation Hub      🚀 Hackathon                |
|                                                             |
| Turn your ideas into reality...   💡 Innovation Wall        |
|                                                             |
| [ Register Now ]                  🏆 Project Showcase       |
|                                   [ Join Now ]              |
 --------------------------------------------------------------

ok keeping the same layout can u give me a more shorter and cleaner code approach

HTML CODE 
<section class="innovation">

    <div class="left">
        <p>BUILD • SHARE • INSPIRE</p>

        <h2>Hackathon & Innovation Hub</h2>

        <p>
            Join the hackathon, share ideas on the Innovation Wall,
            and showcase your project with the DevConf community.
        </p>

        <a href="#">Register Now</a>
    </div>

    <div class="right">

        <div class="card">
            <h3>🚀 Hackathon</h3>
            <p>Build creative solutions with your team.</p>
        </div>

        <div class="card">
            <h3>💡 Innovation Wall</h3>
            <p>Share ideas and discover new innovations.</p>
        </div>

        <div class="card last">
            <h3>🏆 Project Showcase</h3>
            <p>Present your work and connect with developers.</p>
            <a href="#">Join Now</a>
        </div>

    </div>

</section>




CSS CODE 

.innovation{
    max-width:1100px;
    margin:80px auto;
    padding:60px;
    background:#0D1B2A;
    border-radius:20px;

    display:grid;
    grid-template-columns:1fr 1.2fr;
    gap:30px;
}

.left{
    display:flex;
    flex-direction:column;
    justify-content:center;
    gap:18px;
}

.left p:first-child{
    color:#fff;
    letter-spacing:2px;
    font-size:14px;
}

.left h2{
    color:#fff;
    font-size:40px;
}

.left p{
    color:#ddd;
    line-height:1.6;
}

.left a{
    width:max-content;
    padding:12px 22px;
    background:#fff;
    color:#0D1B2A;
    text-decoration:none;
    border-radius:8px;
    font-weight:bold;
}

.right{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:18px;
}

.card{
    background:#fff;
    padding:22px;
    border-radius:14px;

    display:flex;
    flex-direction:column;
    gap:12px;
}

.card h3{
    color:#0D1B2A;
}

.card p{
    color:#555;
    line-height:1.5;
}

.last{
    grid-column:1/3;

    display:flex;
    justify-content:space-between;
    align-items:center;
}

.last a{
    background:#0D1B2A;
    color:#fff;
    text-decoration:none;
    padding:10px 18px;
    border-radius:8px;
}


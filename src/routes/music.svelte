<div>
    <header>
        <h1>MUSIC</h1>
    </header>

    <nav>
        <a href=".">Home</a>
        <a href="education">Education</a>
        <a href="entertainment">Entertainment</a>
        <a href="music">Music</a>
      </nav>

    <main>
        <h2>T-Series</h2>
        <h3>172 million subs</h3>

        <p>
            T-Series is a record label in India started by Gulshan Kumar in
            1983. T-Series is one of the fastest-growing channels on YouTube. In
            April 2019, T-Series became a YouTube channel with the most
            subscribers, surpassing PewDiePie. In late May 2019, T-Series
            officially became the first YouTube channel ever to pass 100 million
            subscribers.
        </p>

        <h2>Zee Music Company</h2>
        <h3>68 million subs</h3>

        <p>
            Zee Music Company (ZMC) is an Indian music company, a subsidiary of
            Zee Entertainment Enterprises Ltd. It carries its business
            activities mainly from New Delhi. The company has captured a major
            chunk of market share in Bollywood Music in a short span of time.
        </p>

        <h2>Canal KondZilla</h2>
        <h3>63 million subs</h3>

        <p>
            Konrad Dantas (born 29 September 1994), better known by the stage
            name KondZilla, or just KOND, is a Brazilian screenwriter and
            director. He is the founder of KondZilla Records, which is a music
            video production company and record label often credited for being
            the main popularizer of funk ostentação. He currently owns the
            largest YouTube channel in Brazil and Latin America, and the third
            largest music channel in the world, with more than 53 million
            subscribers and over 26 billion views. In addition to his music
            videos, he is also the creator and director of the Netflix drama
            Sintonia.
        </p>
    </main>
</div>

<style>
    @import url("https://fonts.googleapis.com/css2?family=Cormorant+Garamond&family=Jura:wght@500&family=Shippori+Mincho&display=swap");
  
    header {
        grid-area: h;
        background-color: #8e9dcc;
    }
    nav {
        grid-area: n;
        text-align: center;
        background-color: #7d84b2;
    }
    main {
        grid-area: m;
        background-color: #FFEEDB;
    }
  
    div {
        display: grid;
        grid:
            " h    h   h" auto
            " n    n   n " auto
            " m    m   m " auto
            " f   f    f " auto
            / 1fr 1fr 1fr;
    }
    * {
        font-family: "Jura", sans-serif;
    }
  
    h1 {
        text-align: center;
        font-family: "Jura", sans-serif;
    }
  
    h2 {
        text-align: center;
        font-family: "Cormorant Garamond", serif;
    }
  
    p {
        text-align: left;
        font-family: "Shippori Mincho", serif;
    }
  
    a {
        text-decoration: none;
        color: black;
        border: 1px solid black;
        padding-left: 0.5em;
        padding-right: 0.5em;
    }
  
    a:hover {
        color: white;
        background-color: lightgray;
    }
  </style>
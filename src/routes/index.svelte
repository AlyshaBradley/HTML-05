<div>

  <header>
    <h1>YouTube’s Biggest Channels</h1>
  </header>

  <nav>
    <a href=".">Home</a>
    <a href="education">Education</a>
    <a href="entertainment">Entertainment</a>
    <a href="music">Music</a>
  </nav>

  <main>
    <h2>What is YouTube</h2>

    <p>
      YouTube is a free video sharing website on the internet. The website lets
      people upload, view, and share videos. YouTube was started on February 14,
      2005 by three former workers of PayPal. Google (a search engine company)
      has owned and operated YouTube since 2006. YouTube now carries paid
      advertisements on all pages. Videos can be rated with likes or dislikes,
      and viewers can subscribe to channels they like. Videos can be commented
      on if viewers log into their own accounts. The number of times a video has
      been watched, known as "views", are shown. Many different types of videos
      can be put onto the website, such as educational content, animations, and
      events.
    </p>
  </main>

  <footer>
    <p>&copy; Alysha Bradley 2021</p>
  </footer>

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

  footer {
    background-color: #7d84b2;
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
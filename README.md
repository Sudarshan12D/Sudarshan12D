<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width" />
    <link rel="stylesheet" href="./style.css" />
  </head>
  <body>
    <title> Hi there 👋.</title>
    <h1>Welcome to my GitHub</h1>
    <div class = "allbuttons" id = "allbuttons">
      <button class = "headerbtn" style = "margin-left: -0.2em;" type = "button" onclick="Invert()" > &#9681; </button>
      <button class = "headerbtn" style = "margin-left: -0.2em;" type = "button" onclick = "openhint()"> &#63; </button>
      <button class = "headerbtn" style = "margin-left: -0.2em;" type = "button" onclick="openInst()"> &#9432; </button>
    </div>
    <hr> 
    <div class = "rightside" id = "rightside">
      <div class = "popup" id = "popup">
        <h2 style="text-align: left; padding-left: 20px;">How To Play Wordle ?</h2>
        <ol>
          <li> Start typing. The letters will appear in the boxes.</li>
          <li> Remove letters with Backspace.</li>
          <li> Hit Enter/Return to submit an answer.</li>
          <li> Letters with green background are in the right spot.</li>
          <li> Letters with yellow background exists in the word, but in the wrong spot. </li>
          <li> Letters with gray background do not exist in the word</li>
          <li> If you need a hint, click the ? icon.</li>
        </ol>
      </div>
    </div>
    <br>
    <div class = "foothint" id = "foothint"><p></p></div>
    <br>
    <div id = "box"></div>
    <br>
    <div class = "imge" id = "imge">
      <img src="https://res.cloudinary.com/mkf/image/upload/v1675467141/ENSF-381/labs/congrats_fkscna.gif" width = "400" alt="ALTERNATE_TEXT">
      <h2> YOU WON !!!</h2>
    </div>
    <br>
    <div class = "Startover">
      <button id = "againbtn" type = "button" onclick = "STARTOVER()" > Start Over </button>
    </div>
    <br>
    <p id = "answer"></p>
    <br>
    <P class="footer"> © Sudarshan Naicker 2023 </P>
  </body>
</html>
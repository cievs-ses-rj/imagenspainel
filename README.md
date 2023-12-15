<!DOCTYPE html>
<html lang="en-US" xmlns="http://www.w3.org/1999/xhtml">

<head>
  <title>Centro de Inteligência em Saúde!</title>
  <style type="text/css">
    body,
    html {
      font-family: Helvetica, Arial, sans-serif;
      background-color: #F5F5F5;
      color: #114;
      margin: 0;
      padding: 0;
    }

    a {
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    #titleBar {
      height: 80px;
      background-color: #3475b4;
      overflow: hidden;
      border-bottom: 1px solid #3475b3;
      -moz-box-shadow: 0px 0px 10px 3px #BBC;
      -webkit-box-shadow: 0px 0px 10px 3px #BBC;
      box-shadow: 0px 0px 10px 3px #BBC;
    }

    #titleBar #container {
      margin-top: 14px;
    }

    #titleBar h1 {
      margin: 0 auto .5em auto;
      padding: .2em;
      color: #EEE;
      text-align: center;
    }

    #intro {
      background-color: #DDD;
      margin: 1em 1em 0 1em;
      padding: .75em;
      text-align: center;
      border: 1px solid #CCC;
      font-size: 18px;
    }

    #intro p {
      margin: .3em 0 .3em 0;
    }

    #outer-content {
      max-width: 910px;
      margin: 0 auto;
    }

    #content {
      margin: 1em auto 1em auto;
      float: left;
    }

    #main {
      margin-right: 35px;
      float: left;
      line-height: 24px;
    }

    #shiny {
      float: left;
      width: 305px;
      margin-left: 30px;
      padding-left: 20px;
      border-left: 1px solid #AAA;
    }

    #shiny iframe {
      margin-top: 30px;
    }

    .image-container {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: space-between;
    }

    .image-container a {
      flex-basis: calc(25% - 5px);
      text-decoration: none;
      color: #114;
    }

    .image-container img {
      width: 100%;
      height: auto;
      border: 1px solid #AAA;
    }

    .caption {
      margin-top: 5px;
      text-align: center;
    }
  </style>
  
  <center><img src="https://raw.githubusercontent.com/eduardompeixoto/painel_viral/main/mockup.png" width=1800 height =100></center>
  
</head>

<center>
<body>
  <div id="titleBar">
    <div id="container">
      <h1>Bem-vindos ao Centro em Inteligência a Saúde do Estado do Rio de Janeiro!</h1>
    </div>
  </div>
  <div id="outer-content">
    <div id="intro">
      <p> Aqui se concentram os painéis produzidos em R-shiny para o monitoramento dos agravos e eventos de interesse de saúde pública</p>
    </div>
    <div id="content">
      <div id="main">

      </div>
    </div>
    
    <p>
      
    </p>

<p></p>
    <div class="image-container">
      <a href="https://cisshiny.saude.rj.gov.br/SER/">
        <img src="https://raw.githubusercontent.com/cievs-ses-rj/imagenspainel/main/Regula%C3%A7%C3%A3o2.jpeg"
          alt="Monitoramento da Central Estadual de Regulação">
        <div class="caption">Monitoramento da Central Estadual de Regulação</div>
      </a>

      <a href="https://cisshiny.saude.rj.gov.br/covid/">
        <img src="https://raw.githubusercontent.com/cievs-ses-rj/imagenspainel/main/Coroninha2.jpeg"
          alt="Indicadores Precoces da COVID-19">
        <div class="caption">Indicadores Precoces da COVID-19</div>
      </a>


      <a href="https://cisshiny.saude.rj.gov.br/diagrama_dengue/">
        <img src="https://raw.githubusercontent.com/cievs-ses-rj/imagenspainel/main/Dengue2.jpeg"
          alt="Diagrama de Controle Dengue">
        <div class="caption">Diagrama de Controle Dengue</div>
        
        
        <a href="https://cisshiny.saude.rj.gov.br/now/">
        <img src="https://www.pontorh.com.br/y/2960/atraso-trabalho-e1473097348496.jpg"
          alt="Nowcasting - outros agravos">
        <div class="caption">Nowcasting - outros agravos</div>
        
        
           <a href="https://cisshiny.saude.rj.gov.br/cemaden/">
        <img src="https://raw.githubusercontent.com/cievs-ses-rj/imagenspainel/main/Desastre2.jpeg"
          alt="Desastres">
        <div class="caption">CEMADEN</div>
        
        
           <a href="https://cisshiny.saude.rj.gov.br/upa_sintomas/">
        <img src="https://raw.githubusercontent.com/cievs-ses-rj/imagenspainel/main/upa2.jpeg"
          alt="UPA - sintomas">
        <div class="caption">UPA</div>
        
        
      </a>
    </div>
  </div>
</body>
</center>
</html>

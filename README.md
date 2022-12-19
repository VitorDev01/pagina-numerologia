<html lang="pt-br">
    <head>
        <title>Somar valores de input</title>
        <meta charset="utf-8">
        <link rel="stylesheet" href="reset.css">
    <style>
      
          body {
            background: #100a1c;
            background-image:
            radial-gradient(50% 30% ellipse at center top, #201e40 0%, rgba(0,0,0,0) 100%),
            radial-gradient(60% 50% ellipse at center bottom, #261226 0%, #100a1c 100%);
                 background-attachment: fixed;
            text-align: center;
          }
          h1 {
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            font: bold 40px serif;
            border-bottom: solid 5px rgba(255, 255, 255, .15);
          }
          p {
            color: #fff;
            display: flex;
            justify-content: center;
            text-align: center;
            margin: 5px;
            font: bold 20px serif;
          }
          .num1, .num2 {
            text-align: center;
            width: 300px;
            height: 40px;
            font: bold 1.2rem serif;
            background: rgba(255, 255, 255, .15);
            color: #fff;
            border: none;
            outline: none;
            cursor: pointer;
            border-radius: 15px;
          }
          .resultado {
            size: 20px;
            color: #fff;
            font: bold 1.2rem serif;
            border-radius: 15px;
          
          }
          button{
            border: none;
            width: 300px;
            height: 40px;
            font: bold 1.2rem serif;
            background: rgba(255, 255, 255, .15);
            color: #fff;
            outline: none;
            cursor: pointer;
            border-radius: 15px;
          }
          .conteiner {
            margin: 30px;
            flex-direction: column;
            /*Efeito vidro*/
            box-shadow: 0 0 1rem 0 rgba(0, 0, 0, .2); 
            
            background-color: rgba(255, 255, 255, .15);
            backdrop-filter: blur(5px);
            width: 350px;
            height: 750px;
            align-items: center;
            justify-content: space-evenly;
            border-radius: 20px;
          }
          img {
            width: 100px;
            height: 140px;
            border-radius: 15px;
            justify-content:space-between ;
            margin: 5px;
          }
          
          /*guias dos Anos pessoais*/
          .hide {
              display:none;
            }
            input[type="checkbox"] {
              display: none;
            }
            #btn-a:checked ~ .hide {
              display: block;
            }
            #btn-a:not(:checked) ~ .hide {
              display: none;
            }
            #btn-b:checked ~ .hide {
              display: block;
            }
              #btn-b:not(:checked) ~ .hide {
              display: none;
            }
            #btn-c:checked ~ .hide {
              display: block;
            }
            #btn-c:not(:checked) ~ .hide {
              display: none;
            }
            #btn-d:checked ~ .hide {
              display: block;
            }
            #btn-d:not(:checked) ~ .hide {
              display: none;
            }
            #btn-e:checked ~ .hide {
              display: block;
            }
            #btn-e:not(:checked) ~ .hide {
              display: none;
            }
            #btn-f:checked ~ .hide {
              display: block;
            }
            #btn-f:not(:checked) ~ .hide {
              display: none;
            }
            #btn-g:checked ~ .hide {
              display: block;
            }
            #btn-g:not(:checked) ~ .hide {
              display: none;
            }
            #btn-h:checked ~ .hide {
              display: block;
            }
            #btn-h:not(:checked) ~ .hide {
              display: none;
            }
            #btn-i:checked ~ .hide {
              display: block;
            }
            #btn-i:not(:checked) ~ .hide {
              display: none;
            }
            
            
          a { /*Links menu*/
            color: white;
            font: 370 20px/1.6 "Source Sans Pro",sans-serif;
          }
        
          a:hover { /*cor ao tocar nos links*/
           background:rgba(0, 0, 0, .09);
           width: 20px;
          }
    
          .swiffy-slider {
            height: 150px;
            width: 150px;
            margin: 40px;
       
          }
          
          .area p {
              text-align: center;
              margin: 10px;
              font: bold 20px serif;
            }

            .area {
             border: 3px solid ;
             border-radius: 15px;
             background-color: rgba(255, 255, 255, .15);
             backdrop-filter: blur(5px);
             border-top-color: #0B1516;
             border-bottom-color: #0B1516;
             border-right-color: #0B1516;
             border-left-color: #DDF7F8;
             display: block;
             margin: 30px;
             
            }
    </style>
  
    </head>
    <body>
        <div class="conteiner">
        <h1>Seu Ano Pessoal Na Númerologia & Tarot</h1>
      
            <div class="centro">
                <p>Dia De Nascimento:</p>
                <input class="num1" type="number"><br>
                <p>Mês de Aniversário:</p>
                <input class="num2" type="number"><br><br>
                
                <button onclick="clicar()">Resultado</button>
                <br><br>
                <p class="resultado"></p>
                <br>
                <p>Some o resultado acima até chegar a um número de 1 a 9 caso tenha 0 corte</p><b><br>
                <p>Observação: Seu ano pessoal começa a valer a partir da sua data de aniversário e muda no próximo.<br><br>
                Este é um conteúdo vendido sobre demanda então caso tenha interesse entre em contato para agendar!.
                </p>
            </div>
           </div>
           <br>

          <!--AnosPessoais-->
          <input type="checkbox" id="btn-a">
          <button id="btn-1">
          <!-- botão pessoa -->
          <label for= "btn-a" >
            <p><strong>Ano Pessoal 1</strong></p>
          </label>
          </button>
          <br>
          <div class="hide">
            <div class="area">
              <p>Ano Marcado Por Novos
              Inícios E Recomeços</p><a href="https://wa.me/5524992717594?text=Olá+Gostaria+De+Saber+Mais+Sobre+As+Consultas+Online">
                Adquirir Leitura Completa
                nas Áreas:</a>
                <p><b>Sentimental,
                   Material
                    & Tomada de 
                   Decisões</b></p>
                <img src="1espada.jpg">
                <img src="1ouro.jpg">
                <img src="copas.jpg">
                <br>
             </div>
          </div>
         <br>
         
          <input type="checkbox" id="btn-b">
          <button id="btn-2">
          <!-- botão pessoa -->
          <label for= "btn-b" >
            <p><strong>Ano Pessoal 2</strong></p>
          </label>
          </button>
          <br>
          <div class="hide">
            <div class="area">
              <p>Ano Marcado pelas Parcerias & Uniões importantes
              </p><a href="https://wa.me/5524992717594?text=Olá+Gostaria+De+Saber+Mais+Sobre+As+Consultas+Online">
                Adquirir Leitura Completa
                nas Áreas:</a>
                <p><b>Sentimental,
                   Material &
                   Tomadas 
                   Decisões</b></p>
                <img src="paus.jpg">
                <img src="2ouro.jpg">
                <img src="2copas.jpg">
                <br>
             </div>
          </div>
         <br>
         <input type="checkbox" id="btn-c">
          <button id="btn-2">
          <!-- botão pessoa -->
          <label for= "btn-c" >
            <p><strong>Ano Pessoal 3</strong></p>
          </label>
          </button>
          <br>
          <div class="hide">
            <div class="area">
              <p>Ano Marcado pelas Comunicações Sociais
              </p><a href="https://wa.me/5524992717594?text=Olá+Gostaria+De+Saber+Mais+Sobre+As+Consultas+Online">
                Adquirir Leitura Completa
                nas Áreas:</a>
                <p><b>Sentimental,
                   Material &
                   Tomadas 
                   Decisões</b></p>
                <img src="3p.jpg">
                <img src="3copas.jpg">
                <img src="3ouros.jpg">
                <br>
             </div>
          </div>
         <br>
         <input type="checkbox" id="btn-d">
          <button id="btn-2">
          <!-- botão pessoa -->
          <label for= "btn-d" >
            <p><strong>Ano Pessoal 4</strong></p>
          </label>
          </button>
          <br>
          <div class="hide">
            <div class="area">
              <p>Ano Marcado pelo trabalho e a família 
              </p><a href="https://wa.me/5524992717594?text=Olá+Gostaria+De+Saber+Mais+Sobre+As+Consultas+Online">
                Adquirir Leitura Completa
                nas Áreas:</a>
                <p><b>Sentimental,
                   Material &
                   Tomadas 
                   Decisões</b></p>
                <img src="4ouros.jpg">
                <img src="4espadas.jpg">
                <img src="4paus.jpg">
                <br>
             </div>
          </div>
         <br>
         <input type="checkbox" id="btn-e">
          <button id="btn-2">
          <!-- botão pessoa -->
          <label for= "btn-e" >
            <p><strong>Ano Pessoal 5</strong></p>
          </label>
          </button>
          <br>
          <div class="hide">
            <div class="area">
              <p>Ano Marcado pelas Mudanças Pessoais 
              </p><a href="https://wa.me/5524992717594?text=Olá+Gostaria+De+Saber+Mais+Sobre+As+Consultas+Online">
                Adquirir Leitura Completa
                nas Áreas:</a>
                <p><b>Sentimental,
                   Material &
                   Tomadas 
                   Decisões</b></p>
                <img src="5ouros.jpg">
                <img src="5espadas.jpg">
                <img src="5paus.jpg">
                <br>
             </div>
          </div>
         <br>
         <input type="checkbox" id="btn-f">
          <button id="btn-2">
          <!-- botão pessoa -->
          <label for= "btn-f" >
            <p><strong>Ano Pessoal 6</strong></p>
          </label>
          </button>
          <br>
          <div class="hide">
            <div class="area">
              <p>Ano Marcado Pela vida sentimental & Romances 
              </p><a href="https://wa.me/5524992717594?text=Olá+Gostaria+De+Saber+Mais+Sobre+As+Consultas+Online">
                Adquirir Leitura Completa
                nas Áreas:</a>
                <p><b>Sentimental,
                   Material &
                   Tomadas 
                   Decisões</b></p>
                <img src="6ouros.jpg">
                <img src="6espadas.jpg">
                <img src="6paus.jpg">
                <br>
             </div>
          </div>
         <br>
         <input type="checkbox" id="btn-g">
          <button id="btn-2">
          <!-- botão pessoa -->
          <label for= "btn-g" >
            <p><strong>Ano Pessoal 7</strong></p>
          </label>
          </button>
          <br>
          <div class="hide">
            <div class="area">
              <p>Ano Marcado pelo Autoconhecimento & a espiritualidade 
              </p><a href="https://wa.me/5524992717594?text=Olá+Gostaria+De+Saber+Mais+Sobre+As+Consultas+Online">
                Adquirir Leitura Completa
                nas Áreas:</a>
                <p><b>Sentimental,
                   Material &
                   Tomadas 
                   Decisões</b></p>
                <img src="7ouros.jpg">
                <img src="7espadas.jpg">
                <img src="7paus.jpg">
                <br>
             </div>
          </div>
         <br>
         <input type="checkbox" id="btn-h">
          <button id="btn-2">
          <!-- botão pessoa -->
          <label for= "btn-h" >
            <p><strong>Ano Pessoal 8</strong></p>
          </label>
          </button>
          <br>
          <div class="hide">
            <div class="area">
              <p>Ano Marcado pelo Poder Pessoal & Financeiro 
              </p><a href="https://wa.me/5524992717594?text=Olá+Gostaria+De+Saber+Mais+Sobre+As+Consultas+Online">
                Adquirir Leitura Completa
                nas Áreas:</a>
                <p><b>Sentimental,
                   Material &
                   Tomadas 
                   Decisões</b></p>
                <img src="8copas.jpg">
                <img src="8espadas.jpg">
                <img src="8paus.jpg">
                <br>
             </div>
          </div>
         <br>
         <input type="checkbox" id="btn-i">
          <button id="btn-2">
          <!-- botão pessoa -->
          <label for= "btn-i" >
            <p><strong>Ano Pessoal 9</strong></p>
          </label>
          </button>
          <br>
          <div class="hide">
            <div class="area">
              <p>Ano Marcado por términos importantes em áreas da vida
              </p><a href="https://wa.me/5524992717594?text=Olá+Gostaria+De+Saber+Mais+Sobre+As+Consultas+Online">
                Adquirir Leitura Completa
                nas Áreas:</a>
                <p><b>Sentimental,
                   Material &
                   Tomadas 
                   Decisões</b></p>
                <img src="9ouros.jpg">
                <img src="9paus.jpg">
                <img src="9copas.jpg">
                <br>
             </div>
          </div>
         <br><br>
    <script>
          function clicar() {
            var num1 = document.querySelector(".num1").value;
            var num2 = document.querySelector(".num2").value;
           
            var resultado = parseInt(num1) + parseInt(num2) + 7;
            document.querySelector(".resultado").innerHTML = resultado;
          }
    </script>
   
   </body>
</html>

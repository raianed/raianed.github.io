<!DOCTYPE html>
<html lang="pt">
<head>
 
<a href="index.html">voltar</a>

    <span class='index'></span>

  <span class='topo'></span>
 <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
<meta charset="utf-8">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css">
<script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/js/bootstrap.bundle.min.js"></script>

      			<span	id='topo'></span>

  </head>
      			<script>

      			$(function(){

$('#info').hide;

$('#titulo').click(function(){

$('#info').toggle();

});

});

				

      		

$(document).ready(function() {

    var $cap1= $('#cap1');

    var $sub1 = $('#sub1');  

    

var myArray = [$cap1, $sub1];

$('#cap1').mouseenter(function (){

$(this).addClass('newColor');

$(myArray).each(function(index, element) {

        $('#sub1').show();      

$('#cap1').mouseout(function() {

$('#sub1').hide();

$(this).removeClass('newColor');

    });

 });

});

});

$(document).ready(function() {

var $cap2= $('#cap2');

    var $sub2 = $('#sub2');  

var myArray = [$cap2, $sub2];

$('#cap2').mouseenter(function (){

$(this).addClass('newColor');

$(myArray).each(function(index, element) {

        $('#sub2').show();      

$('#cap2').mouseout(function() {

$('#sub2').hide();

$(this).removeClass('newColor');

    });

 });

});

});

$(document).ready(function() {

var $cap3= $('#cap3');

    var $sub3 = $('#sub3');  

var myArray = [$cap3, $sub3];

$('#cap3').mouseenter(function (){

$(this).addClass('newColor');

$(myArray).each(function(index, element) {

        $('#sub3').show();      

$('#cap3').mouseout(function() {

$('#sub3').hide();

$(this).removeClass('newColor');

    });

 });

});

});

$(document).ready(function() {

var $cap4= $('#cap4');

    var $sub4 = $('#sub4');  

var myArray = [$cap4, $sub4];

$('#cap4').mouseenter(function (){

$(this).addClass('newColor');

$(myArray).each(function(index, element) {

        $('#sub4').show();      

$('#cap4').mouseout(function() {

$('#sub4').hide();

$(this).removeClass('newColor');

    });

 });

});

});

$(document).ready(function() {

var $cap5= $('#cap5');

    var $sub5 = $('#sub5');  

    

var myArray = [$cap5, $sub5];

$('#cap5').mouseenter(function (){

$(this).addClass('newColor');

$(myArray).each(function(index, element) {

        $('#sub5').show();      

$('#cap5').mouseout(function() {

$('#sub5').hide();

$(this).removeClass('newColor');

    });

 });

});

});

$(document).ready(function() {

$('#sum').mouseenter(function (){

$(this).addClass('newColor');

$('#sum').mouseout(function() {

$(this).removeClass('newColor');

    });

 });

});

$(document).ready(function() {

$('#ref').mouseenter(function (){

$(this).addClass('newColor');

$('#ref').mouseout(function() {

$(this).removeClass('newColor');

    });

 });

});

$(document).ready(function() {

$('#ape').mouseenter(function (){

$(this).addClass('newColor');

$('#ape').mouseout(function() {

$(this).removeClass('newColor');

    });

 });

});

      </script>

<style>

            ul {

                list-style-type: none;

            }

            

          #sub1{

      display:none;

}

 #sub2{

      display:none;

}

 #sub3{

      display:none;

}

 #sub4{

      display:none;

}

 #sub5{

      display:none;

}

.newColor{

color:red;

}

        </style>

        

        <body>

        

 <div  class="container mt-3">
<p><b>Sumário</b></p> 
 <ul class="nav nav-tabs">

   <li class="nav-item" id="sumário">
    <a  class="nav-link"  href="#sumario" class="btn btn-info" role="button"> Sumário</a></li>
    
  <li class="nav-item" id="cap1">
    <a  class="nav-link"  href="#introdução" class="btn btn-info" role="button"> INTRODUÇÃO</a></li>

  

  <li class="nav-item" id="cap2">
    <a  class="nav-link"  href="#referencial" class="btn btn-info" role="button"> REFERENCIAL TEÓRICO</a></li>

 
      <li class="nav-item" id="cap3"><a class="nav-link" href="#mapeamento" class="btn btn-info" role="button">MAPEAMENTO SISTEMÁTICO DA LITERATURA </a></li>

            
  <li  class="nav-item" id="cap4"><a class="nav-link" href="#pesquisa" class="btn btn-info" role="button">PESQUISA COM PROFISSIONAIS</a></li>



  <li  class="nav-item" id="cap5"><a class="nav-link" href="#conclusão"  class="btn btn-info" role="button">CONCLUSÃO</a></li>

   <li  class="nav-item" id="referências"><a class="nav-link" href="#referencias"  class="btn btn-info" role="button">REFERÊNCIAS</a></li>
   
   
   <li  class="nav-item" id="apêndices"><a class="nav-link" href="#apendices"  class="btn btn-info" role="button">APÊNDICES</a></li>
          </ul>
         <ol class="breadcrumb">

  <li class="breadcrumb-item"><a href="index.html">Início</a></li>

  <li class="breadcrumb-item"><a href="sumario.html">Índice</a></li>

  

</ol>
  <div class="tab-content border mb-3">
    <div id="sumario" class="container tab-pane fade"><br><ul> 
<li>Sumário............................................................................................8</li></ul> 
    </div>
      
    <div id="introdução" class="container tab-pane fade"><br><ul> 
      <li>1. INTRODUÇÃO ...................................................................................................................................4</li>
      <li>1.1 Motivação Motivação Motivação........................................................................................5 </li> 
      <li>1.2 Objetivos................................................................................................................................5 </li>
      <li> 1.3 Metodologia.........................................................................................................................5</li>
      <li>1.4 Estrutura do Trabalho..........................................................................................................5</li></ul>
    </div>
<div id="referencial" class="container tab-pane fade"><br><ul>
        <li>2. REFERENCIAL TEÓRICO .................................................................................................................7</li>
        <li>2.1 Introdução.............................................................................................................................7</li>
        <li>2.2 Testes de Software ..............................................................................................................7</li>
        <li>2.3 Modelos de Maturidade ......................................................................................................8</li>
        <li>2.4 TMMi .....................................................................................................................................8</li>
        <li>2.4.1 Nível 1 – Inicial .......................................................................................................10</li>
        <li>2.4.2 Nível 2 – 2.4.1 Nível 1 – Inicial ..............................................................................10</li>
        <li>2.4.3 Nível 3 – Definido ...................................................................................................11</li>
        <li>2.4.4 Nível 4 – Mensurado ...............................................................................................11</li>
        <li>2.4.5 Nível 5 – Otimizado ................................................................................................12</li>
        <li>2.5 Áreas de Processos do TMMi Nível 2.................................................................................12</li>
        <li>2.5.1 Políticas e Estratégias de Testes ..............................................................................12</li>
        <li>2.5.2 Planejamento de Testes ...........................................................................................13</li>
        <li>2.5.3 Monitoramento e Controle do Processo de Teste...................................................14</li>
        <li>2.5.4 Design e Execução de testes...................................................................................15</li>
        
        <li>2.5.5 Ambiente de Testes.................................................................................................16 </li>
  <li>2.6 Considerações Finais................................17 </li></ul>
  </div>
    <div id="mapeamento" class="container tab-pane fade"><br><ul>
        <li>3. MAPEAMENTO SISTEMÁTICO DA LITERATURA .........................................................................17</li>
        <li>3.1 Introdução ...........................................................................................................................17</li>
        <li>3.2 Método de Pesquisa ............................................................................................................17</li>
        <li>3.2.1 Perguntas de pesquisa ............................................................................................17</li>
        <li>3.2.2 Estratégia de busca ................................................................................................17</li>
        <li>Resultados .........................................................................................................................18</li>
        <li>3.3.1 IEEE ......................................................................................................................20</li>
        <li>3.3.2 SCOPUS ................................................................................................................21</li>
        <li>3.3.3 GOOGLE SCHOLAR ...........................................................................................23</li>
        <li>3.3.4 ACM ......................................................................................................................25</li>
        <li>3.4 Considerações finais ...........................................................................................................25</li></ul>
      </div>
    <div id="pesquisa" class="container tab-pane fade"><br><ul>
        <li> 4. PESQUISA COM PROFISSIONAIS .................................................................................................27</li>
        <li>4.1 Introdução ...........................................................................................................................27</li>
        <li>4.2 Metodologia .......................................................................................................................27</li>
        <li>.3 Questionário .......................................................................................................................28</li>
        <li>4.4 Amostra ..............................................................................................................................28</li>
        <li>4.4.1 Perfil profissional e pessoal ..................................................................................28</li>
        <li>4.4.2 Perfil da empresa ..................................................................................................32</li>
        <li>4.4.3 Práticas do TMMi..................................................................................................33</li>
        <li>4.5 Considerações Finais ...............................................................................................45</li>
      </div></ul>
     <div id="conclusão" class="container tab-pane fade"><br><ul>
        
       <li>5.CONCLUSÃO ...................................................................................................................................47</li>
        <li>5.1 Considerações Finais .........................................................................................................47</li>
        <li>5.2 Limitações .........................................................................................................................47</li>
        <li>5.3 Trabalhos Futuros ..............................................................................................................48</li></ul>
         </div>
    
    <div id="toast1" class="toast" style="position: absolute; down: 0; right: 0;" role="alert" aria-live="assertive" aria-atomic="true"   data-delay="5000">
    <div class="toast-header">
     <strong class="mr-auto">Capítulo 1</strong> 
    </div>
    <div class="toast-body">
      Introdução           
    </div>
  </div>
    
    <div id="toast2" class="toast" style="position: absolute; down: 0; right: 0;" role="alert" aria-live="assertive" aria-atomic="true"   data-delay="5000">
    <div class="toast-header">
     <strong class="mr-auto">Capítulo 2</strong> 
    </div>
    <div class="toast-body">
      Referencial Teórico
    </div>
  </div>
    
     <div id="toast3" class="toast" style="position: absolute; down: 0; right: 0;" role="alert" aria-live="assertive" aria-atomic="true"   data-delay="5000">
    <div class="toast-header">
     <strong class="mr-auto">Capítulo 3</strong> 
    </div>
    <div class="toast-body">
      Mapeamento Sistemático da Literatura
    </div>
  </div>
    
    <div id="toast4" class="toast" style="position: absolute; down: 0; right: 0;" role="alert" aria-live="assertive" aria-atomic="true"   data-delay="5000">
    <div class="toast-header">
     <strong class="mr-auto">Capítulo 4</strong> 
    </div>
    <div class="toast-body">
      Pesquisa com Profissionais
    </div>
  </div>
    
    <div id="toast5" class="toast" style="position: absolute; down: 0; right: 0;" role="alert" aria-live="assertive" aria-atomic="true"   data-delay="5000">
    <div class="toast-header">
     <strong class="mr-auto">Capítulo 5</strong> 
    </div>
    <div class="toast-body">
      Conclusão
    </div>
  </div>
   </div>
   <a href="#topo">Voltar ao topo</a>
<script>
$(document).ready(function(){
  $("#cap1").click(function(){
    $('#toast1').toast('show');
    
  });
});
</script>
   
   <script>
$(document).ready(function(){
  $("#cap2").click(function(){
    $('#toast2').toast('show');
  });
});
</script>
   
    <script>
$(document).ready(function(){
  $("#cap3").click(function(){
    $('#toast3').toast('show');
  });
});
</script>
    
   <script>
$(document).ready(function(){
  $("#cap4").click(function(){
    $('#toast4').toast('show');
  });
});
</script>
   
    <script>
$(document).ready(function(){
  $("#cap5").click(function(){
    $('#toast5').toast('show');
  });
});
</script>
    <script>
$(document).ready(function(){
  $(".nav-tabs a").click(function(){
    $(this).tab('show');
  });
 $('.nav-tabs a').on('shown.bs.tab', function(event){
    var x = $(event.target).text();         //active tab
    var y = $(event.relatedTarget).text();  // previous tab
    $(".act span").text(x);
    $(".prev span").text(y);
  });
});
   </script>
</body>
      
</html>


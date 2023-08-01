# JavaScript-JQuery-e-Ajax
Mais conhecida como JS, n a criação de Script para WEB.



**Alterando um id**

!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>função</title>
</head>
<body>
<p id="paragrafo">Olá!</p>
<script>
function mFuncao() {
var x = document.getElementById("paragrafo");
x.innerHTML="Hello!";
}
</script>
<button type="button" onclick="mFuncao();"> Translate</button>


**Alterando Atributo**
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>função</title>
</head>
<body>
<script>
function trocaImagem() {
var elemento=document.getElementById("myimage");
if (elemento.src.match("bulbon")) {
elemento.src="pic_bulboff.gif";
} else {
elemento.src="pic_bulbon.gif";
}
}
</script>
<p><img id="myimage" onclick="trocaImagem()"
src="pic_bulboff.gif" width=100 height=180></p>
<p>Clique na lâmpada para ligar/desligar a luz</p>



*****função****

!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>função</title>
</head>
<body>
    <script>
    function somaDoisNumeros(numero1,numero2){
        alert(numero1+numero2);
    }
    // somaDoisNumeros(10,20);//exibe 30
     //função  com parametro  e retorno

     function somaDoisNumeros(numero1,numero2){
        return numero1 + numero2
     }
     var numero =80;
     var resultado = somaDoisNumeros(10,20);
     alert(numero-resultado);
    </script>
</body>
</html>







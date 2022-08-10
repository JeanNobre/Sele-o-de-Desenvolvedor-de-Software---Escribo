#Desenvolvedor-de-Software---Escribo

Olá senhoras e senhores.

Venho por meio deste enunciado relatar de forma simples e prática o funcionamento de uma função cujo objetivo é implementar um equacionamento que receba um número inteiro positivo e retorne o somatório de todos os valores inteiros divisíveis por 3 ou 5 e que sejam inferiores ao número escolhido anteriormente.
Inicialmente os senhores devem ter um software que aceite uma linguagem de hipertexto (HTML) e de programação JavaScript, o software utilizado neste teste foi o VS Code que é gratuito e de fácil instalação.
Com o software instalado copie o código abaixo e cole no VS Code, pode-se notar que na décima linha do código possui a declaração somar = (11), para fazer diferentes tipos de testes basta trocar o número 11 no código por qualquer outro número, em seguida  salve o arquivo como “blablabla”.html e abra de preferência no Google Chrome. Com o arquivo html aberto em seu navegador, aperte a tecla F12 que irá abrir a função de ferramentas do desenvolvedor, na sub-aba chamada de console será ilustrado o resultado do somatório dos números divisíveis por 3 e 5.
<html>
<script>
somar (11)
function somar (limite) {
let DivididosPor3 = 0;
let DivididosPor5 = 0;
for (i=0;i < limite;i++)
{if (i % 3 === 0) DivididosPor3 += i;
if (i % 5 === 0) DivididosPor5 += i;}
console.log(DivididosPor3 + DivididosPor5);}
</script>
</html>

# Computação Gráfica - Estrela ⭐

<f2 align = "left"> **O seguinte projeto possui o objetivo de construir uma estrela por meio de conhecimentos com fractal.**</f2> 
<img src="estrela.gif.gif" align="center"/>
<hr> </hr>

# Importando o módulo Turtle
<p>Para utilizar um módulo no Python, utilizamos o comando import (importar) seguido do nome do módulo que queremos importar. Após a importação, já podemos utilizar todos os objetos e funções que o módulo disponibiliza.<p>   
  
    import turtle
<p>Em seguida, para criar uma tela chamada "estrela" use a função:<p>   
  
    estrela = turtle.Screen()
  
<p> Logo, ele cria um objeto tartaruga chamado "geekyTurtle" usando a função: </p>

    geekyTurtle = turtle.Turtle()

<p> Assim, o código entra em um loop for que será executado cinco vezes (para os cinco pontos da estrela). Dentro do loop, a tartaruga avança 200 pixels usando o método forward() e, em seguida, vira 144 graus para a direita usando o método right(). A tartaruga continuará avançando e virando à direita até completar uma estrela de cinco pontas completa.</p>
  
    for i in range(5):
        geekyTurtle.forward(200)

        geekyTurtle.right(144)

<p> Por fim, o código finaliza a janela gráfica da tartaruga chamando a função:</p>

    turtle.done();

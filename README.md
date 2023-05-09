# keylogger
Este é um código em C++ que monitora as teclas pressionadas no teclado de um computador. 
Ele usa a função GetAsyncKeyState() para verificar se uma determinada tecla foi pressionada e, se sim, registra a tecla pressionada em uma string e exibe a tecla no console.
O programa monitora as teclas alfabéticas, espaços, pontos e números de 0 a 9. Quando uma tecla é pressionada, o programa adiciona o caractere correspondente à string "keys" e aguarda 200 milissegundos antes de verificar outra tecla. 
Quando a tecla "Enter" é pressionada, o programa adiciona a tag "<br>" à string "keys" em vez de uma nova linha.
Este tipo de programa pode ser usado para monitorar a atividade do usuário em um computador, mas deve ser usado com cuidado e ética, pois pode violar a privacidade do usuário.

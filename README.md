# Chat-socket
Este é um projeto de chat desenvolvido em JavaScript no Node.js utilizando o framework Express e a biblioteca Socket.IO para implementar comunicação em tempo real através de web sockets. O chat possui uma funcionalidade especial, na qual os usuários são separados em dois grupos distintos (Grupo 1 e Grupo 2) .

Foi um projeto bem especial pra mim no qual pude aplicar pela primeira vez os web sockets com a biblioteca socket.io que havia estudados nos ultimos dias.

Funcionalidades
Divisão em Grupos
Ao acessar o chat, você será solicitado a inserir um nome de usuário e selecionar um grupo (Grupo 1 ou Grupo 2) você pode  acessar o grupo 1 ou grupo 2 atraves do endereço http://localhost:3000/grupo1 para o grupo 1 e http://localhost:3000/grupo2 para o grupo 2.
Depois de inserir essas informações, você será redirecionado para a sala de chat correspondente ao grupo selecionado.

Os usuários no Grupo 1 só poderão ver as mensagens enviadas por outros usuários do Grupo 1.
Os usuários no Grupo 2 só poderão ver as mensagens enviadas por outros usuários do Grupo 2.
Enviando Mensagens
Dentro da sala de chat, você pode enviar mensagens para o grupo selecionado. Basta digitar a mensagem no campo de texto na parte inferior da tela e pressionar Enter ou clicar no botão de envio. Sua mensagem será enviada apenas para os membros do mesmo grupo.

Atualização em Tempo Real
O chat utiliza web sockets fornecidos pela biblioteca Socket.IO para fornecer uma experiência de atualização em tempo real. Isso significa que, sempre que uma mensagem é enviada por qualquer membro do grupo, ela será exibida imediatamente nos navegadores de todos os outros membros do mesmo grupo.

# Digital Nutri
## Análise de Requisitos

### 1. Introdução

Tem se tornado cada vez maior a busca por alimentação saudável. Alimentos com baixo teor calórico, sem glúten ou sem lactose. Pensando nesse público, e na tentativa de influenciar cada vez mais pessoas a se alimentarem de forma saudável, está loja se destina a fornecem diversas iguarias que se adequam à vida saudável.

Dentre nossos produtos, encontram-se óleos de coco, óleos de abacate, barras de cereal ou de frutas, doces sem lactoses e temperos sem adição desal ou produtos inorgânicos. Além disso, nosso site contará com dicas de como incluir alimentos saudáveis à rotina diária, e quais os benefícios que estes alimentos trazem para anossa saúde. Como substituir alimentos gordurosos e calóricos por alimentos mais saudáveis e muitas outras dicas.



### 2. Casos de Uso

#### 2.1 Caso de Uso I - Cadastrar Cliente
  - **Nível:**Administrador ou Cliente
  - **Atores primários:** Administrador e Cliente, 
  - **Interessados:**
    - **Administrador:** Efetuação de cadastro a fim de acessar o sistema.
    - **Cliente:** Efetuação de cadastro a fim de acessar o sistema.
  - **Pré-condições:** Acesso à Internet.
  - **Garantias de sucesso:** Clientes devidamente adicionado ao banco de dados. 
  - **Cenário de sucesso principal:**
	1. Cliente acessa a página web;
	2. Cliente seleciona o link Cadastrar ;
	3. Cliente preenche devidamente os campos do formulário de cadastro.
	4. Cliente confirma o cadastro
	5. Sistema confirma que o cadastro foi efetuado com sucesso.
  - **Extensões:** Passos 3 à 5 _ Campos preenchidos erroneamente:
	a. Processo de cadastro é interrompido
	b. Usuário recebe feedback relativos ao problema


Caso de Uso II - Cadastrar Produto

Escopo: 
Nível: Administrador
Atores primários: Administrador
Interessados: Administrador: Efetuação de cadastro a fim de adicionar produtos ao banco de dados.
Pré-condições: Acesso à Internet.
Garantias de sucesso: Produtos devidamente adicionados ao banco de dados. 
Cenário de sucesso principal:
1. Administrador acessa a página web;
2. Administrador seleciona o link Cadastrar Produtos ;
3. Administrador preenche devidamente os campos do formulário de cadastro.
4. Administrador confirma o cadastro
6. Sistema confirma que o cadastro foi efetuado com sucesso.
Extensões: Passos 3 à 5 _ Campos preenchidos erroneamente:
a. Processo de cadastro é interrompido
b. Administrador  recebe feedback relativos ao problema.


Caso de Uso III - Editar Cliente

Escopo: 
Nível: Administrador ou Cliente
Atores primários: Cliente
Interessados: Cliente: Realizar alterações em campos editáveis após cadastro.
Pré-condições: Acesso à Internet. Usuário autenticado.
Garantias de sucesso: Campo devidamente alterado no banco de dados. Atualização do valor do campo exibido no sistema.
Cenário de sucesso principal:
1. Cliente acessa a página web;
2. Cliente seleciona o link Fazer Login;
3. Cliente realiza o processo de autenticação;
4. Cliente acessa seu Perfil;
5. Cliente seleciona modifica o campo desejado;
6. Cliente confirma a edição;
7. Perfil do cliente é atualizado;
Extensões: Passo 3 _ Usuário ou senha inválidos:
a. Processo de login é interrompido;
b. Erro é notificado ao usuário;
c. Dados são solicitados novamente;
Passos 5-6 _ Campos preenchidos erroneamente:
a. Processo de edição é interrompido.
b. Usuário recebe feedback relativos ao problema
.

Caso de Uso IV - Editar Produto
Escopo: 
Nível: 
Atores primários: Administrador
Interessados: Administrador: Realizar alterações em campos editáveis após cadastro.
Pré-condições: Acesso à Internet. Usuário autenticado.
Garantias de sucesso: Campo devidamente alterado no banco de dados. Atualização do valor do campo exibido no sistema.
Cenário de sucesso principal:
1. Administrador acessa a página web;
2. Administrador seleciona o link Fazer Login;
3. Administrador realiza o processo de autenticação;
4. Administrador acessa seu link de Produto;
5. Administrador seleciona link editar produto;
6. Administrador seleciona e modifica o campo desejado;
7. Administrador confirma a edição;
7. Produto é atualizado;
Extensões: Passo 3 _ Usuário ou senha inválidos:
a. Processo de login é interrompido;
b. Erro é notificado ao usuário;
c. Dados são solicitados novamente;
Passos 5-6 _ Campos preenchidos erroneamente:
a. Processo de edição é interrompido.
b. Usuário recebe feedback relativos ao problema


Caso de Uso V - Remover Usuário

Escopo: 
Nível: Administrador
Atores primários: Administrador
Interessados: Administrador: Realizar remoção de um usuário cadastrado.
Pré-condições: Acesso à Internet. Privilégio de Administrador.
Garantias de sucesso: Usuário devidamente removido do banco de dados. Confirmação exibida.
Cenário de sucesso principal: 
1. Administrador acessa a página web;
2. Administrador realiza o processo de autenticação;
3. Administrador pesquisa usuário à ser removido;
4. Administrador aperta o botão remover;
5. Administrador confirma que ele realmente deseja remover o usuário;
6. Usuário é removido do banco de dados;
7. Mensagem de confirmação de remoção é exibida.
Extensões: Passo 2 _ Usuário ou senha inválidos:
a. Processo de login é interrompido;
b. Erro é notificado ao usuário;
c. Dados são solicitados novamente;

Caso de Uso VI – Logar

Escopo: 
Nível: Administrador ou Cliente
Atores primários: Administrador, Cliente
Interessados: Administrador: Efetuação de autenticação a fim de acessar o sistema.
Cliente: Efetuação de autenticação a fim de acessar o sistema.
Pré-condições: Acesso à Internet. Usuário previamente cadastrado.
Garantias de sucesso: Redirecionamento para página inicial do usuário.
Cenário de sucesso principal:
1. Cliente acessa a página web;
2. Cliente seleciona o link Logar ;
3. Cliente informa campos usuário e senha;
4. Cliente pressiona botão Logar ;
5. Cliente redirecionado para sua página inicial;
Extensões: Passos 3-4 _ Usuário ou senha inválidos:
a. Processo de login é interrompido;
b. Erro é notificado ao usuário;
c. Dados são solicitados novamente;

Caso de Uso VII – Comprar produto

Escopo: 
Nível: Cliente
Atores primários: Cliente
Interessados: Cliente: Comprar um produto em oferta.
Pré-condições: Acesso à Internet. Usuário autenticado.
Garantias de sucesso: O produto é selecionado e ao final do processo é retirado do banco de dados.
Cenário de sucesso principal:
1. Cliente realiza processo de login no sistema;
2.Cliente seleciona o link do produto(os) desejado(os);
3. Cliente preenche os dados para finalização da compra;
4. A compra é finalizada e o produto é retirado do banco de dados;
Extensões: Passo 1 _ Usuário ou senha inválidos:
a. Processo de login é interrompido;
b. Erro é notificado ao usuário;
c. Dados são solicitados novamente;
Passo 3 _ Campos preenchidos erroneamente:
a. Processo de criação é interrompido.
b. Administrador recebe feedback relativos ao problema.

Caso de Uso VIII – Tabela de todos os tipo de produtos existentes

Escopo: 
Nível: Administrador ou Clientes
Atores primários: Administrador, Clientes
Interessados: Administrador: Visualizar todas as opções de produtos oferecidos para venda.
Cliente: Visualizar todas as opções de produtos oferecidos para venda.
Pré-condições: Acesso à Internet. Administrador ou Clientes autenticados.
Garantias de sucesso: Nova aba é aberta e uma tabela é exibida. Em
seguida, o usuário pode visualizar os produtos e fazer a compra dos mesmos se desejado.
Cenário de sucesso principal:
1. Usuário acessa a página web;
2. Usuário realiza processo autenticação;
3. Usuário seleciona o link Produtos;
4. A tabela de produtos é exibida com opções de botões para compra;
5. Usuário escolhe os produtos e a quantidade desejada.
6. Se selecionado algum produto para compra, nova aba é aberta para o processo de Compra de Produto.
Extensões:
Passo 1 _ Usuário ou senha inválidos:
a. Processo de autenticação é interrompido;
b. Erro é notificado ao usuário;
c. Dados são solicitados novamente;
Passo 5 _ Quantidade de produtos desejados é maior que a quantidade disponível no banco de dados:
a. Notificação do problema é exibido.
b. Alerta informando a quantidade disponível em estoque.
c. Retorna a aba de produtos.

Caso de Uso IX – Aba de Dicas

Escopo: 
Nível: Administrador ou Clientes
Atores primários: Administrador, Clientes
Interessados: Administrador: Visualizar todas as opções de produtos oferecidos para venda.
Cliente: Visualizar dicas de como se alimentar de forma saudável. Como substituir alimentos gordurosos ou calóricos por alimentos mais saudáveis. Quais os benefícios que cada um desses alimentos pode trazer. e muitas outras dicas
Cenário de sucesso principal:
1. Usuário acessa a página web;
2. Usuário realiza processo autenticação;
3. Usuário seleciona o link Dicas;
4. A lista de dicas é exibida com opções de botões para compra;


3. Objetivo

Fornecer aos clientes de forma prática e no conforto de suas casas, produtos orgânicos e saudáveis. Produtos livres de glúten, lactose, componentes inorgânicos e demasiada quantidade de sódio. Além disso, buscaremos fornecer dicas de como se alimentar de forma saudável, como incluir tais alimentos na rotina alimentar, e como substituir alimentos gordurosos e calóricos por alimentos saudáveis. 
Nosso foco é atender ao público que deseja manter uma dieta alimentar saudável. E incentivar a transformação dos hábitos alimentares de cada vez mais pessoas. Nosso site conta também com uma aba de dicas de alimentação saudável.







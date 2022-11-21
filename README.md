# INspire - Uma rede que inspira e conecta pessoas que buscam melhorar sua qualidade de vida e saúde mental

<div align="center">
  <img src='./src/imagens/InspireReadme.jpeg' style="altura: 12rem;">

  Confira [ aqui ](https://juliene-araujo.github.io/SAP008-social-network/) o resultado final! 

</div>


## Índice

* [1. Apresentação](#1-apresentação)
* [2. Resumo do projeto](#2-resumo-do-projeto)
* [3. Pesquisa de usuários](#3-pesquisa-de-usuário)
* [4. Histórias de usuários](#4-histórias-de-usuários)
* [5. Critérios de aceitação mínimos do
  projeto](#5-criterios-de-aceitação-mínimos-do-projeto)
* [6. Hacker edition](#6-hacker-edition)
* [7. Entrega](#7-entrega)
* [8. Guias, dicas e leituras
  complementares](#8-guias-dicas-e-leituras-complementares)

***

## 1. Apresentação

Esse foi o terceiro projeto desenvolvido pelo bootcamp da Laboratoria e tem como principal objetivo a construção de uma rede social com múltiplas telas em Vanilla JavaScript que seja responsiva a partir do método Single-page Application (SPA) e  que permita o usuário:

- criar conta de acesso;
- logar-se com e-mail e senha;
- logar com o Google;
- criar, editar e deletar publicações;
- dar likes e dislikes nas publicações. 

## 2. Resumo do projeto

Diariamente estamos conectados em diversas redes socias sujeitos a diferentes conteúdos que nem sempre podemos filtrar. Pensando neste contexto, a rede INspire surgiu da necessidade de ter uma rede social com um ambiente acolhedor, livre de mensagens nocivas que possam impactar de maneira negativa no dia a dia.

**Qual a necessidade busca resolver? E para quem?**

Segundo a Organização Mundial da Saúde (OMS) no primeiro ano de pandemia de COVID-19, a prevalência global de ansiedade e depressão aumentou em 25%. 
A Folha de São Paulo destacou que os Brasileiros se preocupam mais com a saúde mental do que com o câncer. Essa foi a constatação da pesquisa "Monitor Global dos Serviços de Saúde", feita pelo Instituto Ipsos.
De acordo com o levantamento, 49% dos entrevistados no Brasil apontaram o bem-estar psicológico como o principal fator de preocupação. A sondagem foi realizada entre julho e agosto de 2022, com 23.507 pessoas, em 34 países

Dado esse contexto e pensando em remodelar os ambientes que influenciam nossa vida e fortalecer o cuidado com a saúde mental, a aplicação tem o objetivo de conectar pessoas que buscam melhorar sua qualidade de vida e saúde mental, por meio de informações, links relacionados e apoio, tendo em vista que muitas pessoas relataram não ter espaço onde possam se expressar e serem acolhidas de alguma forma.

Por meio de um ambiente seguro, construímos um espaço com informações relacionadas ao tema que possibilitam a troca de experiências livre de discriminação e julgamento. Nela o usuário tem um espaço para ser ouvido e para compartilhar aquilo que lhe faz bem e possa ajudar outras pessoas a ter um dia melhor.


## 3. Pesquisa de usuários

Para conhecer os usuários, realizamos uma pesquisa utilizando a ferramenta Google Forms. A partir desta pesquisa foi possível traçar o perfil das personas, identificar as necessidades dos usuários e elaborar a interface da aplicação.

- Formulário da pesquisa aplicado com os possíveis usuários:

COLOCAR GIF DA PESQUISA (VER COMO SE FAZ)

<p>
  <img width="460" heigth="300" src='./src/imagens/GifDaPesquisa.gif'>
</p>

- Resultado da pesquisa:

COLOCAR GIF DO RESULTADO (VER COMO SE FAZ)
<p>
  <img width="460" heigth="300" src='./src/imagens/GifResultadoDaPesquisa.gif'>
</p>


## 4. Histórias de usuários

Com base nas pesquisas com os usuários, elaboramos 3 histórias de usuário:

**História do usuário 1:**

"Eu como usuária de redes sociais gostaria de logar na aplicação com e-mail e senha para criar uma conta em um ambiente mais seguro

- Critérios de aceitação: 
   - Página de cadastro e login

**História do usuário 2:**

" Eu como usuária de redes sociais, gostaria de me logar com minha conta do google para acessar a aplicação mais rápido sem precisar fazer um cadastro."

## 5. Critérios de aceitação mínimos do projeto

### 5.1 Boilerplate

Este projeto não inclui um _boilerplate_, portanto você terá que definir a
estrutura de pastas e escrever seus próprios testes unitários (_tests_). Para
isso, você pode guiar-se por meio de projetos anteriores.

### 5.2 Definição do produto

No `README.md`, conte-nos brevemente como você mapeou as necessidades dos seus
usuários e como você chegou à definição final do seu produto. É importante que
detalhe:

* Quem são os principais usuários do produto.
* Qual problema o produto resolve/para que ele serve para esses usuários.

### 5.3 Histórias de usuário

Depois de entender as necessidades de seus usuários, escreva as Histórias de
Usuário. Elas representam tudo o que ele precisa fazer/ver na Rede Social. Cada
uma de suas histórias de usuário deve possuir:

* **Critérios de aceitação:** tudo o que deve acontecer para satisfazer as
  necessidades do usuário.

* **Definição de pronto:** todos os aspectos técnicos que devem ser atendidos
  para que, como equipe, saibam que essa história está finalizada e pronta para
  ser publicada. **Todas** suas histórias de usuário (com exceções), devem
  incluir esses aspectos em sua definição de pronto (além de tudo o que precisa
  adicionar):

  - Ser uma SPA.
  - Ser _responsivo_.
  - Receber _code review_ de pelo menos uma parceira de outra equipe.
  - Fazer _tests_ unitários.
  - Fazer testes manuais buscando erros e imperfeições simples.
  - Fazer testes de usabilidade e incorporar o _feedback_ dos usuários como
    melhorias.
  - Fazer deploy do aplicativo e marcar a versão (git tag).

### 5.4 Desenho da Interface de Usuário (protótipo de baixa fidelidade)

Você deve definir qual será o fluxo que o usuário seguirá dentro do seu
aplicativo e, com isso, criar a interface do usuário (UI) que siga este fluxo.

### 5.5 Responsivo

Deve funcionar bem em dispositivos de tela grande (computadores, laptops etc.) e
pequena (_tablets_, telefones celulares etc.). Sugerimos seguir a técnica
_`mobile first`_ (mais detalhes sobre essa técnica ao final).

### 5.6 Considerações sobre o comportamento da Interface do Usuário (UI)

Essas considerações ajudarão você a escrever as definições de pronto de sua
H.U.:

#### Criação e login de conta de usuário

* _Login_ com Firebase:
  - Para o _login_ e postagens na timeline, você pode usar o
    [Firebase](https://firebase.google.com/products/database/)
  - O usuário deve poder criar uma conta de acesso ou autenticar-se com conta de
    e-mail e senha e também com uma conta do Google.
* Validações:
  - Somente usuários com contas válidas têm acesso permitido.
  - Não haver usuários repetidos.
  - A conta do usuário deve ser um email válido.
  - O que o usuário digita no campo de senha (_input_) deve ser secreto.
* Comportamento:
  - Quando o formulário de registro ou login é enviado, ele deve ser validado.
  - Se houver erros, mensagens descritivas devem ser exibidas para ajudar o
    usuário.

#### Timeline/linha do tempo

* Validações:
  - Ao publicar, deve ser validado se há conteúdo no _input_.
* Comportamento:
  - Ao recarregar o aplicativo, é necessário verificar se o usuário está
    _logado_ antes de exibir o conteúdo,
  - Conseguir publicar um _post_.
  - Poder dar e remover _likes_ em uma publicação. Máximo de um por usuário.
  - Visualizar contagem de _likes_.
  - Poder excluir uma postagem específica.
  - Solicitar confirmação antes de excluir um _post_.
  - Ao clicar em editar um _post_, você deve alterar o texto para um _input_ que
    permite editar o texto e salvar as alterações.
  - Ao salvar as alterações, você deve voltar ao texto normal, mas com a
    informação editada.
  - Ao recarregar a página, poder ver os textos editados.

### 5.7 Considerações técnicas sobre front-end

* Separar a manipulação do DOM da lógica (separação de responsabilidades).
* Ter várias telas. Para isso, seu aplicativo deve ser um [Single Page
  Application
  (SPA)](https://pt.wikipedia.org/wiki/Aplicativo_de_p%C3%A1gina_%C3%BAnica)
* Alterar e persistir dados. Os dados que você adiciona ou modifica devem
  persistir por todo o aplicativo. Recomendamos que você use o
  [Firebase](https://firebase.google.com/) para isso também.

#### Testes unitários

* Lembre-se de que não há _setup_ de **testes** definido, isso dependerá da
  estrutura do seu projeto. Você não deve esquecer de pensar sobre os testes.
  Eles podem ajudar a definir a estrutura e sua lógica.

* Os testes de unidade devem cobrir no mínimo 70% de _statements_, _functions_,
  _lines_ e _branches_.

### 5.8 Considerações técnicas UX

* Faça pelo menos 2 entrevistas com os usuários.
* Faça um protótipo de baixa fidelidade.
* Verifique se a implementação do código segue as diretrizes do protótipo.
* Faça sessões de teste de usabilidade com o produto em HTML.

## 6. Hacker Edition

As seções chamadas _Hacker Edition_ são **opcionais**. Se **você terminou** e
cumpriu todos os requisitos acima e sobrou tempo, tente concluí-las. Dessa
forma, você pode aprofundar e/ou exercitar mais os objetivos de aprendizagem do
projeto.

* Criar posts com imagens.
* Procurar usuários, adicionar e excluir "amigos".
* Definir a privacidade de _posts_ (público ou apenas para amigos).
* Permitir ver na linha do tempo de usuários "não amigos" apenas os posts
  públicos.
* Permitir comentar ou responder a uma postagem.
* Editar perfil.

## 7. Entrega

O projeto será entregue subindo seu código no GitHub (`commit` /`push`) e a
interface será hospedada usando o GitHub pages ou outro serviço de hospedagem
que você pode ter encontrado ao longo do caminho.

***

## 8. Guias, dicas e leituras complementares

### Mobile first

O conceito de [_mobile
first_](https://tableless.com.br/mobile-first-a-arte-de-pensar-com-foco/) faz
referência a um processo de desenho e desenvolvimento que parte de como se vê e
como funciona uma aplicação primeiro em um dispositivo móvel e mais adiante se
analisa como adaptar a aplicação à telas progressivamente maiores. Esta é uma
contraposição ao modelo tradicional, no qual primeiro se desenha os websites (ou
webapps) para desktops e depois os adaptam para telas menores.

A motivação aqui é se assegurar que desde o começo sejam desenhadas telas
_responsivas_. Dessa forma, começamos com a aparência e o comportamento do
aplicativo em uma tela e ambiente móvel.

### Múltiplas telas

Em projetos anteriores, nossas aplicações eram compostas de apenas uma tela
_principal_ (uma só _página_). Neste projeto, precisaremos dividir nossa
interface em várias _views_ ou _pages_ e oferecer uma maneira de navegar entre
essas telas. Esse problema pode ser resolvido de várias maneiras: com arquivos
HTML independentes (cada um com seu próprio URL) e links tradicionais; mantendo
na memória e renderizando condicionalmente (sem atualizar a página);
[manipulando o histórico do
navegador](https://developer.mozilla.org/es/docs/DOM/Manipulando_el_historial_del_na_gador)
com
[`window.history`](https://developer.mozilla.org/es/docs/Web/API/Window/history).
Neste projeto, convidamos você a explorar opções e decidir sobre uma opção de
implementação.

### Gravação de dados

Nos projetos anteriores, consumimos dados, mas ainda não tínhamos escrito dados
(salvar alterações, criar dados, excluir, etc). Neste projeto, você precisará
criar (salvar) novos dados, além de ler, atualizar e modificar os dados
existentes. Esses dados podem ser salvos remotamente usando o
[Firebase](https://firebase.google.com/).

Outras:

* [Mobile
  First](https://tableless.com.br/mobile-first-a-arte-de-pensar-com-foco/)
* [Mobile First Is NOT Mobile Only - Nielsen Norman
  Group](https://www.nngroup.com/articles/mobile-first-not-mobile-only/)
* [Flexbox - CSS
  Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
* [Módulos:
  Export](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/export)
* [Módulos:
  Import](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Sentencias/import)

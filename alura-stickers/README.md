## Getting Started

Welcome to the VS Code Java world. Here is a guideline to help you get started to write Java code in Visual Studio Code.

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).


#Conteúdos para auxiliar no aprendizado e facilitar a execução do projeto, construir uma aplicação do zero para consumir uma API de filmes com Java. 💻

Link 1 Vídeo | Como posso estudar melhor?: https://www.youtube.com/watch?v=Is6c9KSGCbk&ab_channel=Alura
Link 2 Artigo | Algoritmos e Lógica de programação: O que são e qual a importância?: https://www.alura.com.br/artigos/algoritmos-e-logica-de-programacao
Link 3 Vídeo | Orientação a objetos com Roberta Arcoverde: https://www.youtube.com/watch?v=jpuJ1qrluoU&ab_channel=Alura
Link 4 O que é o Java?: https://www.youtube.com/watch?v=90NcVNsKGik&ab_channel=Alura
Link 5 Java: o que é, linguagem e um Guia para iniciar na tecnologia: https://www.alura.com.br/artigos/java
Link 6 Ecossistema Java revisitado: https://open.spotify.com/episode/0Gi0MlOlG4qmNfUFBr9Xh2?go=1&sp_cid=c9556b5b0068d6bf380b8ab5622717f8&utm_source=embed_player_p&utm_medium=desktop&nd=1
Link 7 Guia de Carreira JAVA: https://www.youtube.com/watch?v=TUBqH9zVs3M&ab_channel=Alura
Link 8 Como fazer um bom portfólio?: https://www.youtube.com/watch?v=gu1OXrirC0U&ab_channel=Alura

image.png

Aula 01:<br>
Links, dicas e notas de aula
Boas-vindas! Chegou a hora de mergulhar em Java com a segunda Imersão Java da Alura!

Nesta primeira aula, vamos construir uma aplicação do zero para consumir a API do IMDb e exibir os filmes mais populares, destacando seus pôsteres e visualizando sua classificação... Tudo isso sem usar nenhuma biblioteca externa!

Abaixo disponibilizamos todo o material para que você acompanhe a aula e avance em seu projeto.

Código da Aula
Clique aqui para acessar o código completo da aula.

Notion Guia de Mergulho
Para te ajudar durante as aulas, criamos um notion exclusivo da Imersão Java! Com dicas de como se preparar para a Imersão, conteúdos relacionados ao tema, calendário para você ficar por dentro de tudo que vai rolar nessa edição e muito mais.

Links citados
Os 250 melhores filmes de acordo com a classificação do IMDB.
A documentação da API do IMDB.
Instalação do Visual Studio Code com o Coding Pack para Java
Documentação da classe HttpRequest do pacote java.net.http.
Classe pronta que utiliza Expressões Regulares para fazer parse de um JSON.
Biblioteca Jackson, que faz parse de JSON.
Site que ajuda a entender Expressões Regulares.
Artigo: Como deixar no seu GitHub com um README interessante.
O endpoint da API do IMDB que devolve os 250 melhores filmes: https://imdb-api.com/en/API/Top250Movies/ + SUA-API-KEY

Desafios desta aula
Consumir o endpoint de filmes mais populares da API do IMDB. Procure também, na documentação da API do IMDB, o endpoint que retorna as melhores séries e o que retorna as séries mais populares. Confira a resolução do desafio aqui
Usar sua criatividade para deixar a saída dos dados mais bonitinha: usar emojis com código UTF-8, mostrar a nota do filme como estrelinhas, decorar o terminal com cores, negrito e itálico usando códigos ANSI, e mais! Confira a resolução do desafio aqui
Colocar a chave da API do IMDB em algum lugar fora do código como um arquivo de configuração (p. ex, um arquivo .properties) ou uma variável de ambiente. Confira a resolução do desafio aqui
Material complementar
Artigo na Alura “O que é JSON?”.
Artigo na Alura sobre como pintar o terminal, com tabelinha de cores e negrito.
Artigo na Alura sobre como usar VS Code para codar em Java.
API do IMDb
A documentação da API do IMDb pode ser encontrada no seguinte link: https://imdb-api.com/api

Lembrando que você precisará registrar-se e criar a sua chave (API Key), conforme exemplo abaixo:

API Key do IMDb
A URL dos 250 melhores filmes no IMDb é a seguinte:

https://imdb-api.com/en/API/Top250Movies/sua-chave

Observação: troque sua-chave pela API Key obtida no IMDb.

Instabilidade da API do IMDb
Caso a API do IMDb esteja instável ou fora do ar, você pode utilizar os seguintes endereços alternativos:

https://raw.githubusercontent.com/alura-cursos/imersao-java-2-api/main/TopMovies.json
https://raw.githubusercontent.com/alura-cursos/imersao-java-2-api/main/TopTVs.json
https://raw.githubusercontent.com/alura-cursos/imersao-java-2-api/main/MostPopularMovies.json
https://raw.githubusercontent.com/alura-cursos/imersao-java-2-api/main/MostPopularTVs.json
Para utilizar os endereços alternativos, troque a URL da aula por uma das novas URLs:

// fazer uma conexão HTTP e buscar os top 250 filmes
// String url = "https://imdb-api.com/en/API/Top250Movies/k_0ojt0yvm";
String url = "https://raw.githubusercontent.com/alura-cursos/imersao-java-2-api/main/TopMovies.json"; // usando endereço alternativo
Divulgue seu projeto
Mostre seu projeto para o mundo compartilhando no LinkedIn e Instagram! Marque a Alura (@AluraOnline) e o Paulo (@paulo_hipster). Vamos adorar ver seus projetos e acompanhar sua evolução! Lembre-se de utilizar a hashtag #ImersaoJava para seu projeto ter ainda mais alcance.

Ah, e não esqueça de colocar a tag ImersaoJava dentro do seu projeto no GitHub. É só clicar na engrenagem que aparece na seção About e colocar a tag ImersaoJava dentro do campo Topics. Queremos ver seu portfólio!

Discord

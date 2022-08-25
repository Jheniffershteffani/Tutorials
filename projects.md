### checklist
#### Básico
- [x] # Projeto1 (html) - hello world
    - [x] usando a tag `h1`
    - [x] usando a tag `img` com attribute `src` = `https://avatars.githubusercontent.com/u/111667610?v=4`
    - [x] usando a tag `h1` com attribute `style` para mudar a cor do texto

- [x] # Projeto2 (javascript) - hello world
    - [x] `console.log()`


- [x] # Projeto3 (html+css) - hello world
    - [x] usar um arquivo css ao invés do attribute `style`


- [ ] # Projeto4 (html+javascript) - hello world
    - [ ] criar um botão que mostra uma mensagem usando`alert()`


- [ ] # Projeto5 (html+css) - criar uma animação com uma tag `div`
    [documentação](https://www.w3schools.com/cssref/playdemo.asp?filename=playcss_animation), [outros exemplos](https://www.freecodecamp.org/portuguese/news/exemplos-de-transicao-em-css-como-usar-a-animacao-ao-passar-o-mouse-alterar-a-opacidade-e-mais/)
    - [ ] mudar de cor
    - [ ] arredondar às bordas
    - [ ] mudar de cor e arredondar às bordas quando o mouse passar em cima


- [ ] # [Projeto6](#projeto6) (html+javascript+css) - manipular outros elementos
    [exemplo1](https://stackoverflow.com/questions/58948543/how-to-chain-css-animation-on-different-elements) (html+css)
    [exemplo2](https://codepen.io/jorgecardoso/post/1-css-transitions-and-animations) (html+javascript+css)
    - [ ] (html+css) criar um botão que altera a cor e a forma de uma `div`
    - [ ] (html+javascript+css) criar um botão que altera a cor e a forma de uma `div`


##### Projeto6
![img](https://cdn-media-1.freecodecamp.org/images/aeLhzRqHdU1Gub7GL3WOvtgno7fMuRnwuy4H)


#### Intermediário (nodejs) 
##### - front-end
[tutorial - digitalocean](https://www.digitalocean.com/community/tutorials/how-to-create-a-web-server-in-node-js-with-the-http-module-pt);
[tutorial - js-server](https://github.com/vlang/v/tree/master/examples/js_dom_draw#js-server);
[exemplo - typescript_vanilla_typeorm](https://github.com/enghitalo/v/blob/examples/js_dom_draw_bechmark_chart/refactor/examples/js_dom_draw_bechmark_chart/typescript_vanilla_typeorm/src/server.js);
[documentação official](https://github.com/nodejs/node/blob/main/doc/api/http.md#event-connect);

- [ ] # Projeto7 (nodejs) - JS serve
    - [ ] mostrar um arquivo `index.html` na rota "/"
    com o html abaixo.
    ```js
    <h1>hello world</h1>
    ```
    - rota: req.url == "/"
- [ ] # Projeto8 (nodejs) - JS serve
    - Servir todos os projetos anteriores (Um em cada roda)
    - [ ] req.url == "/Projeto1"
    - [ ] req.url == "/Projeto2"
    - [ ] req.url == "/Projeto3"
    - [ ] req.url == "/Projeto4"
    - [ ] req.url == "/Projeto5"
    - [ ] req.url == "/Projeto6"
 
##### - back-end
- [ ] # Projeto9 (nodejs) criar um CRUD.
    - [ ] verbo: `GET`, 
            rota: `req.url == "/"`, 
            status: `200`, 
            response: [{'a':'a'},{'b':'b'},{'b':'b'}]
    - [ ] verbo: `POST`, 
            rota: `req.url == "/"`, 
            status: `201`, 
            response: ***req.body*** !!! Atenção, Jheniffer! Verificar oq isso significa
    - [ ] verbo: `PUT`, 
            rota: `req.url == "/"`, 
            status: `404`, 
            response: "Not found"
    - [ ] verbo: `DELETE`, 
            rota: `req.url == "/"`, 
            status: `401`, 
            response: "unauthorized"
##### - front-end + back-end
- [ ] # Projeto10 (nodejs) criar uma página que apresenta às informações dependendo da resposta do back-end (projeto 09).
[documentação html list](https://www.w3schools.com/html/html_lists.asp);
['exemplo' fetch](https://www.alura.com.br/artigos/revolucao-node-js-adeus-axios-fetch-api-versao-17-5-0);
[documentação fetch](https://developer.mozilla.org/pt-BR/docs/Web/API/Fetch_API/Using_Fetch);
    - rotas no front: `"/pega"`, `"/cria"`, `"/atualiza"`, `"/deleta"`
    - [ ] se o status for `404`, retorna um text: "Página não encontrada"
    - [ ] se o status for `401`, retorna um text: "Usuário sem permissão"
    - [ ] se o status for `201`, retorna um `alert()`: "Criado com sucesso", e retireciona para a rota "/" ou "/home"
    - [ ] se o status for `200`, retorna um html com uma lista usando às informações do `res.body`.
    Mais ou menos como a tabela abaixo:
     <table style="margin-top: 10px">
          <tr>
            <th>index</th>
            <th>coluna 1</th>
            <th>coluna 2</th>
          </tr>
          <tr>
            <td>0</td>
            <td>a</td>
            <td>a</td>
          </tr>
          <tr>
            <td>1</td>
            <td>b</td>
            <td>b</td>
          </tr>
          <tr>
            <td>2</td>
            <td>b</td>
            <td>b</td>
          </tr>
        </table>
- [ ] # Projeto11 - Mandar informações do front para o back usando a tag `form`
[Documentação](https://www.w3schools.com/html/html_forms.asp)
##### - front-end + back-end + banco de dados
- [ ] # Projeto12 -  usar o projeto anterior para pegar, salvar ou deletar informações no banco de dados.
#### Profisional - Já dá para trabalhar como estagiária ou Júnior (NestJS + React + TypeORM + SQLite)
[react_getstarted](https://www.w3schools.com/react/react_getstarted.asp)
[react_router](https://www.w3schools.com/react/react_router.asp)
[react_forms](https://www.w3schools.com/react/react_forms.asp)
[react_components](https://www.w3schools.com/react/react_components.asp)
[react_css_styling](https://www.w3schools.com/react/react_css_styling.asp)
- [ ] # Projeto13 - Login e cadastro de usuário
https://contactmentor.com/login-form-react-js-code/
![img](https://contactmentor.com/wp-content/uploads/2021/06/login6.gif)
![img](https://i.pinimg.com/originals/84/9d/e8/849de8715eb981f9a370d10dfdb774d4.gif)
https://blog.rocketseat.com.br/reactjs-autenticacao/
![img](https://blog.rocketseat.com.br/content/images/2018/12/airbnb-signup-1.gif)
![img](https://assets.materialup.com/uploads/a8b4f721-0940-432e-af96-0c60891ed15f/animated_teaser.gif)
https://github.com/MatheusPires99/gobarber-2.0
![img](https://camo.githubusercontent.com/63ee04f7a45c10249ec6614dcc93f1ca1f9f58c912a01e5a5806fab79a78fa9d/68747470733a2f2f7265732e636c6f7564696e6172792e636f6d2f6d61746865757370697265732f696d6167652f75706c6f61642f76313539313039393833322f676f6261726265725f7761647266632e676966)


### Pagina Login

Aqui estou fazendo uma documentação chamada README.md, nessa documentação estou anotando códigos da página de login em html, css e Js.


Começando com a tag``<Forms>`` para enviar um formulário do login

**Exemplo:**
```html

  <form>
    <label for="email">E-mail</label> <!--Aqui adiciona uma label pra mostrar email-->
    <input type="email" id="email" name="email" placeholder="Digite seu e-mail"> 


  </form>
</body>
</html>
```
---
Primeiro elemento adicionado foi o ***forms*** nele usamos pra preencher um formulário.

> essa tag `<forms>` usada para formulário 

Dentro do forms usamos o ***label*** ele serve para mostrar um texto na tela mas ela não é titulo e nem descrição mas sim uma label pra mostrar um texto com uma outra responsabilidade.

> essa tag `<label for = "email>Email</label>">` 

Aqui essa tag está dizendo que label está definindo um valor "email" que ainda vai  ser usado pelo *input* e definindo o nome da label como ">Email<"

> essa tag `<input type="email" id="email" name="email" placeholder="Digite seu e-email">` 

Aqui esse input é onde o usuário que vai digitar, **input** é o elemento de entrada de dados. **Type = "email** é do tipo Email, fala que esse campo é de e-mail, e o id identificador único do campo. Ele serve para ligar o label ao input. **"Name = email"** é o nome do dado quando o formulário for enviado. Exemplo quando o usuário enviar o email: **email=mateus@gmail.com**. esse **placeholder="Digite seu e-mail"** Serve para digitar dentro do campo como comentário pra ajudar o usuário a entender.

>type="password" required> type password deixa o dado escondido e required deixa obrigatório
---
OBS: Usei a div para separar diferentes conteúdos como login e descrição

---

Botão para enviar o formulário``<forms>``

> ``<button type="submit">Entrar</button>``



**FIM DO ``<FORMS>``**


### Tags estruturação
``<head>``

O head recebe informações da configuração do site

**Exemplo:**
    * Define o conjunto de carcteres 
>   ``"<meta charset="UTF-8">"``

Ele é uma codificação padrão para representar caracteres em sites e docimentos digitais. Ela permite letras, acentos, símbolos técnicos e até emojis sejam representados igualmente em qualquer navegador moderno, sistema operacional...

---
``<body>``

O  body é o corpo do site inteiro.

---
``<Header>``

O header é o cabeçalho, ele vem dentro do ``<body>``.

---

``<Div>``

As famosas divs que são usadas para separar elementos, nela usei para separar o conteúdo da esquerda como descrição e o conteúdo da direita como o login.

---

``<Main>``

Para definir o conteúdo princippal. Ela vem embaixo do header.








 

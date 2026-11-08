# 🚀 Orbit Tasks

Gerenciador de tarefas simples e responsivo, feito com HTML, CSS e JavaScript (jQuery) e estilizado com Bootstrap. As tarefas ficam salvas no navegador, então não precisa de servidor nem de banco de dados.

<!-- Adicione aqui um print ou GIF do projeto:
![Orbit Tasks](static/img/screenshot.png)
-->

## 📋 Sobre o projeto

O **Orbit Tasks** permite criar, editar, concluir e excluir tarefas com data de expiração. Tudo roda no front-end: os dados são guardados no `localStorage`, e as tarefas continuam lá quando você fecha e reabre a página.

Este projeto nasceu como atividade do curso **Entra21** e foi evoluído por mim para fazer parte do meu portfólio. Nele pratiquei manipulação do DOM com jQuery, validação de formulários, persistência de dados no navegador e construção de interfaces responsivas com Bootstrap.

## ✨ Funcionalidades

- ➕ **Adicionar tarefas** por um modal, com descrição e data de expiração
- ✅ **Validação do formulário**, com mensagens de erro e data mínima igual ao dia atual
- ✏️ **Editar tarefas** direto na lista, com botões de salvar e cancelar
- 🗑️ **Excluir tarefas**
- ☑️ **Marcar como concluída**, com o texto riscado
- 🙈 **Esconder e mostrar tarefas concluídas** com um botão
- 🔎 **Pesquisar tarefas** pela descrição
- 💾 **Persistência local** com `localStorage`
- 🔔 **Notificação (toast)** ao criar uma tarefa
- 📭 **Mensagem de lista vazia** quando não há tarefas
- 👤 **Painel de login** (offcanvas), por enquanto só a interface

## 🛠️ Tecnologias utilizadas

- [HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
- [jQuery 3.7.1](https://jquery.com/) e [jQuery UI](https://jqueryui.com/)
- [Bootstrap 5.3.2](https://getbootstrap.com/)
- [Bootstrap Icons 1.11.1](https://icons.getbootstrap.com/)
- [Day.js](https://day.js.org/) para manipulação e formatação de datas

## 📁 Estrutura do projeto

```
Orbit-Tasks/
├── index.html
└── static/
    ├── css/
    │   └── style.css
    ├── img/
    │   └── logo.png
    └── js/
        ├── jquery-3.7.1.min.js
        ├── jquery-ui.min.js
        └── script.js
```

## ▶️ Como executar

Não é preciso instalar nada. Basta clonar o repositório e abrir o arquivo no navegador:

```bash
# Clone o repositório
git clone https://github.com/AJGamer10/Orbit-Tasks.git

# Entre na pasta
cd Orbit-Tasks
```

Depois abra o `index.html` com um duplo clique. Se preferir um servidor local, use a extensão **Live Server** do VS Code ou o comando abaixo:

```bash
python -m http.server 8000
```

E acesse `http://localhost:8000`.

> **Obs.:** Bootstrap, Bootstrap Icons e Day.js são carregados por CDN, então é necessário ter conexão com a internet.

## 🧭 Como usar

1. Clique no botão **+** no canto inferior direito.
2. Preencha a descrição e a data de expiração e clique em **Salvar alterações**.
3. Use o checkbox para concluir a tarefa, o botão amarelo para editar e o vermelho para excluir.
4. Use o campo de pesquisa para filtrar e o botão **Esconder tarefas concluídas** para organizar a lista.

## 🗺️ Próximos passos

- [ ] Implementar a autenticação (login com e-mail, Google e Facebook)
- [ ] Sincronizar as tarefas com um back-end ou banco de dados
- [ ] Ordenar tarefas por data de expiração
- [ ] Destacar tarefas vencidas
- [ ] Adicionar categorias ou prioridades

## 🤝 Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch para a sua feature (`git checkout -b feature/minha-feature`)
3. Faça o commit das alterações (`git commit -m "Adiciona minha feature"`)
4. Envie para a sua branch (`git push origin feature/minha-feature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto ainda não possui uma licença definida. Adicione um arquivo `LICENSE` (por exemplo, MIT) se quiser permitir o uso por outras pessoas.

## 👤 Autor

Feito por [AJGamer10](https://github.com/AJGamer10).

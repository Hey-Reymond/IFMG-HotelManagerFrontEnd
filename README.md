# Sistema de Gerenciamento de Hotel

![Status do Projeto](https://img.shields.io/badge/status-em%20desenvolvimento-yellowgreen)
![Linguagem](https://img.shields.io/badge/WEB-HTML%20CSS%20JS-blue.svg)
![Licença](https://img.shields.io/badge/licen%C3%A7a-MIT-green)

> Projeto acadêmico da disciplina de Desenvolvimento WEB do IFMG - Campus Formiga. Um trabalho FrontEnd para ver, apreçar e reservar quartos em Hoteis e Pousadas, desenvolvido em HTML, CSS e JavaScript.

---

## 📖 Sobre o Projeto

O **SRH** é um sistema de front-end para o **Hotel Fênix** (fictício). O projeto foi dividido em duas partes principais:

1.  **Área do Cliente:** Página inicial (`index.html`), listagem de quartos, "Minhas Reservas" e login.
2.  **Área Administrativa:** Um painel para gerenciar quartos, reservas, mensagens e visualizar o contador de visitas.

## 🚀 Funcionalidades Implementadas

* **Sistema de Login:** A página `html/login.html` verifica os usuários:
    * Admin: `cpf: admin` / `senha: fenix` (Redireciona para o Dashboard).
    * Cliente: `cpf: 12345678900` / `senha: 123` (Redireciona para a Home).
* **Contador de Visitas:** Conta cada acesso à página inicial e exibe o total no Dashboard do Admin.
* **Dashboard do Admin:**
    * Cards de estatísticas (incluindo contador de visitas).
    * CRUD de quartos (Adicionar, Editar, Excluir).
    * Visualização de Reservas e Mensagens de Contato.
* **Persistência de Dados:** Todos os dados (quartos, reservas, visitas) ficam salvos no `localStorage`.
## 💻 Como Executar

1.  Clone este repositório:
    ```
    git clone https://github.com/Hey-Reymond/IFMG-HotelManagerFrontEnd.git
    ```
2.  Abra o arquivo `index.html` no seu navegador.
3.  Use um dos logins abaixo para testar:
    * **Admin:** `cpf: 1111` / `senha: fenix`
    * **Cliente:** `cpf: 12345678900` / `senha: 123`

## 📂 Estrutura de Arquivos

* `index.html`: **Página Inicial (Home)**
* `html/login.html`: Tela de Login
* `html/admin.html`: Dashboard do Administrador
* `html/quartos.html`: Listagem de quartos
* `js/`: Scripts de lógica e banco de dados simulado.
* `css/`: Estilos globais e específicos.
* `docs/`: Documentação e **laudo.pdf** (Checklist de Usabilidade).

---

## 👤 Autores

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/Hey-Reymond">
        <img src="https://github.com/Hey-Reymond.png?size=100" width="100px;" alt="Foto de Kaua Teixeira Nascimento no GitHub"/>
        <br />
        <sub>
          <b>Kaua Teixeira N.</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/CamilyLeal">
        <img src="https://github.com/CamilyLeal.png?size=100" width="100px;" alt="Foto de Camily Leal Silva no GitHub"/>
        <br />
        <sub>
          <b>Camily Leal S.</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

> Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

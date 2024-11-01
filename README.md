<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Silkscreen&size=20&duration=1500&pause=1000&center=true&vCenter=true&multiline=true&repeat=false&random=false&width=700&height=110&lines=CRUD_Carros+com+%2ENET+8+e+SQL+Server" 
    alt="Typing SVG" />
  </a>
  
<h5 align="center"> 
  <b>✅ Completo</b> | <b>✅ Responsivo
</h5>
    
</div>

Este projeto é uma aplicação CRUD (Create, Read, Update, Delete) desenvolvida utilizando **.NET 8** e **Entity Framework Core** com **SQL Server**. A aplicação implementa o padrão de repositório (Repository Pattern), promovendo um código mais limpo e desacoplado.

## Demonstração

<div align="center">
  <img alt="videoSite" title="videoSite"  src="Crud_Carros/assets/video-crudcarros.gif"/>
</div>
  
---

#### Funcionalidades
- **Resumo de Tarefas** - Visualização dos status das tarefas criadas.
- **CRUD - Dashboard** - É Possível criar, editar, ver detalhes e excluir tarefas.
- **Validação de Formulário** - Validação de formulário ao tentar criar ou editar uma tarefa sem o preenchimento correto dos dados.
- **Validação de exclusão** - Alerta ao tentar excluir uma tarefa.
- **Todas as tarefas** - É possível verificar todos os detalhes das tarefas.

#### Usabilidade
- Interface disponível para desktop, tablet e mobile (responsivo).

---

## Stacks

| Desenvolvimento Front-end              | Desenvolvimento Back-end                                       | IDE                                                         |
|----------------------------------------|----------------------------------------------------------------|-------------------------------------------------------------|
| HTML                                   | [ASP.NET Core](https://dotnet.microsoft.com/pt-br/apps/aspnet) | [Visual Studio ](https://visualstudio.microsoft.com/pt-br/) |
| CSS                                    | [C#](https://dotnet.microsoft.com/pt-br/languages/csharp)      | 
| [JavaScript](https://javascript.com)   |    
| [Jquery](https://jquery.com/)          |
| [BootStrap](https://getbootstrap.com/) |

---
### Entidades

- **User**
- **Login**
- **Staff**
- **Client**
- **ModelOfCar**
- **Car**
- **ClientOfStaff**
---
### Repositórios

O projeto implementa o padrão Repository para facilitar o gerenciamento de dados e promover um código mais desacoplado:

- **IRepository<T>**: Interface genérica que define operações CRUD básicas.
- **StaffRepository, ClientRepository, CarRepository**, etc: Repositórios específicos que implementam a lógica de acesso ao banco de dados.

---
### Data

- **ApplicationDbContext:** Classe de contexto do Entity Framework Core, responsável pela comunicação com o banco de dados SQL Server e mapeamento das entidades.
---
### Endpoints

A aplicação possui endpoints para realizar operações de CRUD nas diferentes entidades, como:

- `GET /api/staff`
- `POST /api/staff`
- `PUT /api/staff/{id}`
- `DELETE /api/staff/{id}`
---
### Relações Entre Entidades

- **Staff gerencia Modelos de Carros.**
- **Modelos de Carros possuem um Dono.**
- **O Dono é um Cliente de uma Empresa.**
- **Clientes e Staff possuem uma relação muitos-para-muitos.**

- ---

<div align="center">

## 👩🏻‍💻 Autor <br>

  <table>
    <tr>
      <td align="center">
        <a href="https://github.com/robsonlmds">
          <img src="https://avatars.githubusercontent.com/u/e?email=robsonlmds@hotmail.com&s=500" width="100px;" title="Autor Robson Lucas Messias" alt="Foto de Perfil do GitHub - Robson Lucas Messias"/><br>
          <sub>
            <b>Robson Lucas Messias</b>
          </sub>
        </a>
      </td>
    </tr>
  </table>
</div>
 
<h4 align="center">
  Made by: Robson Lucas Messias | <a href="mailto:robsonlmds@hotmail.com">Contato</a>
</h4>
<p align="center">
  <a href="[https://www.linkedin.com/in/r-lucas-messias/">
    <img alt="Robson Lucas Messias" src="https://img.shields.io/badge/LinkedIn-R.Lucas_Messias-0e76a8?style=flat&logoColor=white&logo=linkedin">
  </a>
</p>

<h1 align="center">
<img src="https://readme-typing-svg.herokuapp.com/?font=Silkscreen&size=35&center=true&vCenter=true&width=700&height=70&duration=5000&lines=Obrigado+pela+atenção!;" />
</h1>

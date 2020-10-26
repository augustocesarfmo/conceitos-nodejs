# Conceitos do Node.js

Esta aplicação reforça os conhecimentos básicos para construção de uma API (Application Programming Interface) na plataforma Node.js.

## Conhecimentos Obtidos

Entre os conhecimentos obtidos, pode-se destacar a importância da correta utilização dos Métodos HTTP e dos Tipos de Parâmetros, conforme as tabelas abaixo:

### Métodos HTTP

| Método    | Descrição                          |
| --------- | ---------------------------------- |
| GET       | Buscar informações do back-end.     |
| POST      | Criar uma informação no back-end.   |
| PUT/PATCH | Alterar uma informação no back-end. |
| DELETE    | Deletar uma informação no back-end. |

### Tipos de Parâmetros

| Tipo         | Descrição                                                   |
| ------------ | ----------------------------------------------------------- |
| Query Params | Utilizado para filtros e paginação.                          |
| Route Params | Utilizado para identificar recursos (atualizar/deletar).     |
| Request Body | Utilizado para enviar dados para criar ou editar um recurso. |

## Tecnologias

Este projeto foi desenvolvido com as seguintes tecnologias:

- [Express](https://expressjs.com/)
- [VS Code][vc]

## Executando

Para clonar e executar este aplicativo, você precisará de [Git](https://git-scm.com), [Node.js v12.13][nodejs] ou superior + [Yarn v1.19][yarn] ou superior instalado no seu computador.

Na sua linha de comando execute:

```bash
# Clonando este repositório
$ git clone https://github.com/augustocesarfmo/conceitos-nodejs

# Acessando o repositório
$ cd conceitos-nodejs

# Instalando as dependências
$ yarn install

# Executando o app
$ yarn dev
```

## 📝 Licença

Este projeto está sob a licença MIT. Consulte a [LICENÇA](https://github.com/fradeneto/devradar-mobile/blob/master/LICENSE) para obter mais informações.

---

by Augusto César

[nodejs]: https://nodejs.org/
[yarn]: https://yarnpkg.com/
[vc]: https://code.visualstudio.com/

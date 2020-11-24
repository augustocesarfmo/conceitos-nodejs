# <span id="head1">Conceitos do Node.js</span>

Esta aplicação reforça os conhecimentos básicos para construção de uma API (Application Programming Interface) na plataforma Node.js.

- [Conceitos do Node.js](#head1)
	- [🌎 Métodos HTTP](#head3)
	- [📚 Tipos de parâmetros](#head4)
	- [🚀 Tecnologias](#head5)
	- [ℹ️ Executando](#head6)
	- [📝 Licença](#head7)

### <span id="head3">🌎 Métodos HTTP</span>

| Método    | Descrição                          |
| --------- | ---------------------------------- |
| GET       | Busca informações do back-end.     |
| POST      | Cria uma informação no back-end.   |
| PUT/PATCH | Altera uma informação no back-end. |
| DELETE    | Deleta uma informação no back-end. |

### <span id="head4">📚 Tipos de parâmetros</span>

| Tipo         | Descrição                                                   |
| ------------ | ----------------------------------------------------------- |
| Query Params | Utilizado para filtros e paginação.                          |
| Route Params | Utilizado para identificar recursos (atualizar/deletar).     |
| Request Body | Utilizado para enviar dados para criar ou editar um recurso. |

## <span id="head5">🚀 Tecnologias</span>

Este projeto foi desenvolvido com as seguintes tecnologias:

- [Express](https://expressjs.com/)
- [VS Code][vc]

## <span id="head6">ℹ️ Executando</span>

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

## <span id="head7">📝 Licença</span>

Este projeto está sob a licença MIT. Consulte a [LICENÇA](https://github.com/fradeneto/devradar-mobile/blob/master/LICENSE) para obter mais informações.

---

by Augusto César Oliveira 👐🏼

[nodejs]: https://nodejs.org/
[yarn]: https://yarnpkg.com/
[vc]: https://code.visualstudio.com/

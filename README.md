
# Api de estacionamento.

Projeto desenvolvido no curso da [Michelli Brito](https://www.youtube.com/c/MichelliBrito).

#### Stack utilizada
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)

## Documentação da API

#### Retorna todos os itens

```http
  GET /parking-spot
```

#### Retorna um item

```http
  GET /parking-spot/${id}
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `UUID` | **Obrigatório**. O ID do item para buscar |


#### Atualiza um item

```http
  PUT /parking-spot/${id}
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `UUID` | **Obrigatório**. O ID do item para atualizar |

#### Deleta um item

```http
  DELETE /parking-spot/${id}
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `UUID` | **Obrigatório**. O ID do item para deletar |


## FinApi - Financeira

---

## Instalação, Dependências e Executando o Projeto

**1.** Clone este repositório

```
https://github.com/bertoldoklinger/fin-API-node.git
```

**2.** Vá até o diretório raiz do projeto

```
cd fin-API-node
```

**3.** Instale as dependências necessárias

```
yarn
ou
npm install
```

**4.** Execute a aplicação

```
yarn dev
ou
npm run dev
```

## Usando a Aplicação

Para realização de **requisições** na aplicação, deve ser utilizado o **Insomnia** ou **Postman**

### Requisitos

- [x] Deve ser possível criar uma conta
- [x] Deve ser possível buscar o extrato bancário do cliente
- [x] Deve ser possível realizar um depósito
- [x] Deve ser possível realizar um saque
- [x] Deve ser possível buscar o extrato bancário do cliente por data
- [x] Deve ser possível atualizar dados da conta do cliente
- [x] Deve ser possível obter dados da conta do cliente
- [x] Deve ser possível retornar o balanço
- [x] Deve ser possível deletar uma conta
- [x] Deve ser possível retornar o balanço
- [x] Deve ser possível retornar todos os clientes

---

### Regras de negócio

- [x] Não deve ser possível cadastrar uma conta com CPF já exístente
- [x] Não deve ser possível buscar extrato em uma conta não exístente
- [x] Não deve ser possível fazer depósito em uma conta não exístente
- [x] Não deve ser possível fazer saque em uma conta não exístente
- [x] Não deve ser possível fazer saque quando o saldo for insuficiente
- [x] Não deve ser possível excluir uma conta não exístente
- [x] Não deve ser possível retornar o balanço de uma conta não exístente

- **Desenvolvido** **por** [**Bertoldo Klinger**](https://www.linkedin.com/in/bertoldoklinger/)

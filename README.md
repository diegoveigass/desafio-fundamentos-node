<h1 align="center">
  <img src="https://camo.githubusercontent.com/d25397e9df01fe7882dcc1cbc96bdf052ffd7d0c/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f676f6c64656e2d77696e642f626f6f7463616d702d676f737461636b2f6865616465722d6465736166696f732e706e67">

  Desafio 05: Primeiro projeto Node.JS - Bootcamp Go Stack
</h1>

# Indice
- [Sobre](#-sobre)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Como baixar o projeto](#-como-baixar-o-projeto)

---

## 📖 Sobre

Desafio sobre fundamentos do node.js utilizando uma arquitetura **Data Mapper Patern** focado nos princípios do **SOLID** e **DDD**, onde é separado as responsabilidades da aplicação entre os arquivos de rotas, services e repositories



### **Rotas**
É onde fica as rotas da aplicação;

### **Services**
É onde fica a regra de negócio das rotas, possuindo apenas um método (ex.: execute()). Caso outra rota precise executar essa mesma ação, basta chamar esse Service, obedecendo assim o princípio DRY (Don't Repeat Yourself);

### **Repositories**
É onde fica toda fonte de dados da aplicação, seja ela um banco de dados, um arquivo físico ou qualquer outro meio de persistência de dados da aplicação.

---

## 🚀 Tecnologias utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias

- [Express](https://expressjs.com/pt-br/)
- [uuidv4](https://www.npmjs.com/package/uuidv4)
- [TypeScript](https://www.typescriptlang.org/)
- [jest](https://jestjs.io/)

---

## 💻 Como baixar o projeto

```bash
  # Clonar repositório
  $ git clone https://github.com/diegoveigass/desafio-fundamentos-node

  # Entrar no diretório
  $ cd desafio-fundamentos-node

  # Instalar as dependências via yarn
  $ yarn

  # Instalar as dependências via npm
  $ npm install

  # Iniciar o projeto
  $ yarn start

  # Iniciar os testes
  $ yarn test
```

---

Desenvolvido por Diego Veiga

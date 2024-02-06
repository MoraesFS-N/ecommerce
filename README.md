# Ecommerce

Aplicação Ecommerce que está sendo desenvolvida durante a **Mentoria Angular Pro 2.0**.

<a alt="Nx logo" href="https://nx.dev" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/nrwl/nx/master/images/nx-logo.png" width="45"></a>

✨ **Este workspace foi gerado pelo [Build System Nx.](https://nx.dev)** ✨

## Instalação do projeto

```
git clone https://github.com/MoraesFS-N/ecommerce.git
cd ecommerce
npm install
```

## Servir o projeto localmente

```
npm start
```

Ou

```
npx nx serve
```

O projeto será servido por padrão em http://localhost:4200/.
Caso a porta 4200 já esteja em uso basta aceitar para utilizar uma nova porta.

```
? Port 4200 is already in use.
Would you like to use a different port? Yes
```

## Executar tarefas independentes

```
npx nx <NOME_DA_TAREFA> <NOME_DO_MODULO>
```

Exemplos:

```
npx nx test ecommerce
npx nx lint modules-layout
```

## Visualizar Gráfico de dependências (Dependence Graph)

```
npx nx graph
```

## Executar tarefas somente do que foi afetado

```
npx nx affected:<NOME_DA_TAREFA>
```

Exemplos:

```
npx nx affected:test
npx nx affected:graph
```

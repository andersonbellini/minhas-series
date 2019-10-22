# Minhas Séries
> O projeto minhas séries é utilizado para gerenciamento de séries

Para esse projeto foram usado ReactJS no front-end e Node no Backend

## Instalação

Para instalação você pode usar o gerenciador de pacotes do node NPM ou o Yarn.

```shell
yarn install
```

Depois de realizar a instalação dos pacotes, você deve inicializar o projeto de backend diretamente com o node e depois iniciar com o "start".

```shell
node ./node_modules/minhas-series-server/index.js
yarn start
```

## Desenvolvimento

Se precisar realizar a atualização de desenvolvimento você deve :

```shell
git clone https://github.com/andersonbellini/minhas-series
cd minhas-serie/
yarn install
```

### Gerar aplicação para produção

Para gerar a versão de produção você pode gerar a versão própria para esse uso:

```shell
yarn build
```

### Publicação

Para publicação, você deve verificar as condições técnicas do seu provedor/hospedagem.
Como exemplo:

```shell
yarn deploy minhas-series -s server.com -u username -p password
```
## Links

Fonte disponível para baixar em:
- Repository: https://github.com/andersonbellini/minhas-series

## Licença

Liberado para uso e estudo.
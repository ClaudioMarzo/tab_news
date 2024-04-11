# TabNews

Bem-vindo ao TabNews! Este é um site focado na comunidade da área de tecnologia, destinado a debates e troca de conhecimentos por meio de publicações e comentários criados pelos próprios usuários.

## Instalação e Configuração do Ambiente de Desenvolvimento

Para começar a contribuir para o projeto TabNews, siga estas etapas para configurar o ambiente de desenvolvimento:

### Verificar a Versão do Node.js

Antes de iniciar, verifique se você tem o Node.js instalado em sua máquina. Você pode fazer isso executando o seguinte comando no terminal:

```
$ node -v
```

### Usar o Node Version Manager (nvm)

Para gerenciar diferentes versões do Node.js, recomendamos o uso do Node Version Manager (nvm). Siga as etapas abaixo para configurá-lo:

1. Instale o nvm seguindo as instruções fornecidas em: [Node Version Manager - Instalação](https://github.com/nvm-sh/nvm#installing-and-updating)
2. Após a instalação, verifique se o nvm está funcionando corretamente executando o seguinte comando no terminal:
```
$ nvm --version
```

### Instalar a Versão LTS do Node.js

Para garantir uma versão estável e com suporte a longo prazo do Node.js, recomendamos a instalação da versão LTS mais recente. Você pode fazer isso com o seguinte comando:

```
$ nvm install lts/hydrogen
```

### Definir a Versão Padrão

Após instalar a versão LTS, você pode definir essa versão como padrão no seu ambiente de desenvolvimento. Isso garantirá consistência em suas configurações. Execute o seguinte comando para fazer isso:

```
$ nvm alias default lts/hydrogen
```

### Arquivo .nvmrc

Para garantir que outros desenvolvedores saibam qual versão do Node.js o projeto está usando, crie um arquivo na raiz do projeto chamado `.nvmrc` e insira dentro dele a versão desejada. Por exemplo, você pode inserir `lts/hydrogen` no arquivo `.nvmrc` e deixar uma linha em branco no final.

## Contribuição

O TabNews é um projeto de código aberto e estamos abertos a contribuições de toda a comunidade de desenvolvedores. Se você gostaria de contribuir, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
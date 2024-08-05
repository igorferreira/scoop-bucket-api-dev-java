# Java Dev Toolkit Scoop Bucket

Este é um bucket personalizado para o [Scoop](https://scoop.sh/), um instalador de linha de comando para Windows. Este bucket contém manifestos para várias ferramentas essenciais de desenvolvimento, com foco em desenvolvimento Java e produtividade geral.

## Aplicações Incluídas

- Visual Studio Code
- Maven
- OpenJDK (versões 8, 11 e 17)
- IntelliJ IDEA Community Edition
- Notepad++
- Microsoft Teams
- Telegram
- Git
- cURL
- Make

## Como usar este bucket

1. Certifique-se de que você tem o Scoop instalado. Se não tiver, você pode instalá-lo seguindo as instruções em [scoop.sh](https://scoop.sh/).

2. Adicione este bucket ao seu Scoop:

   ```
   scoop bucket add java-dev-toolkit https://github.com/seu-usuario/scoop-bucket.git
   ```

   Substitua `seu-usuario` pelo seu nome de usuário do GitHub.

3. Agora você pode instalar qualquer uma das aplicações listadas usando o Scoop. Por exemplo:

   ```
   scoop install java-dev-toolkit/vscode
   scoop install java-dev-toolkit/openjdk17
   scoop install java-dev-toolkit/maven
   ```

## Atualizando as aplicações

Para atualizar uma aplicação instalada deste bucket, use:

```
scoop update nome-da-aplicacao
```

Para atualizar todas as aplicações instaladas:

```
scoop update *
```

## Contribuindo

Se você quiser contribuir para este bucket, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

Criado e mantido por [Seu Nome](https://github.com/seu-usuario).
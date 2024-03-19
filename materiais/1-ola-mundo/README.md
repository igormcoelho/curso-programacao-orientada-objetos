## Hello World

- Instale um SDK de Java, seja Java SE ou OpenJDK
- Considere um terminal estilo Bash, como do Ubuntu/Linux ou do WSL no Windows
- Nesse exemplo, consideramos openjdk v11

### Compilando e Executando Manualmente

```
$ java -version
openjdk version "11.0.22" 2024-01-16
OpenJDK Runtime Environment (build 11.0.22+7-post-Ubuntu-0ubuntu222.04.1)
OpenJDK 64-Bit Server VM (build 11.0.22+7-post-Ubuntu-0ubuntu222.04.1, mixed mode, sharing)
```

- Compilando o exemplo com `javac`

```
$ javac AloMundo.java
```

- Será gerado um arquivo `AloMundo.class`
- Executando o código

```
$ java AloMundo
Alo Mundo!
```

### Utilizando a IDE VSCode

No VSCode com openjdk instalado no sistema e a extensão de Java, basta apertar em "Run"

![](codigo-run.png)

O resultado deve sair no terminal:

![](codigo-terminal.png)

Erros são avisados em tempo real:

![](codigo-erro.png)

Para maior organização do código, lembre-se de habilitar o Auto-Formatador em `./vscode/settings.json`, opção: `"editor.formatOnSave": true`

## Licença

CC-BY 4.0 ou MIT License

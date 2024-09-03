# Java

Java é uma linguagem amplamente usada, principalmente em aplicações corporativas. Antes de começar a programar em Java, é importante entender alguns conceitos básicos, como projetos e a necessidade de que o nome do arquivo coincida com o nome da classe pública principal.

## Conceito de Projeto e Nomenclatura de Arquivo

Em Java, normalmente organizamos o código em projetos, que podem conter múltiplas classes. O arquivo que contém a classe pública principal deve ter o mesmo nome que essa classe, seguido da extensão `.java`. Por exemplo, se sua classe principal se chama `HelloWorld`, o arquivo deve ser nomeado `HelloWorld.java`.

## Instalação do JDK

### Windows, Linux & MacOS

Para compilar e executar arquivos Java, você precisa instalar o JDK (Java Development Kit). Ele pode ser baixado no site oficial da Oracle:

[JDK Downloads](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)

Após a instalação, é importante configurar a variável de ambiente `JAVA_HOME` e adicionar o diretório `bin` do JDK ao `PATH` do sistema.

## Verificar Instalação

Para verificar se o JDK foi instalado corretamente, execute o seguinte comando no terminal:

```sh
java --version
```

Você deve ver uma mensagem indicando a versão instalada.

## Compilação e Execução

### Arquivos Únicos

1. Navegue até o diretório onde o arquivo `.java` está localizado.
2. Compile o arquivo com o seguinte comando:

```sh
javac HelloWorld.java
```

3. Execute o arquivo compilado com:

```sh
java HelloWorld
```

### Projetos com Múltiplos Arquivos

Para projetos com múltiplos arquivos, o ideal é a utilização de uma IDE dedicada a Java para que a mesma consiga interpretar corretamente, visto que há muitos tipos de projetos e qualquer um deles pode ser selecionado pela COC para ser a base das questões.

Recomendação particular: [JetBrains IntelliJ](https://www.jetbrains.com/pt-br/idea/)

> ℹ️ Nota:
> Todos os alunos do IFFar podem usufruir da versão premium de várias IDEs da JetBrains gratuitamente através do e-mail institucional. Para mais detalhes de como fazer isso, consulte o coordenador do curso.

## Compilação Online

Se preferir, você pode utilizar um compilador Java online.

> **⚠️ Importante! ⚠️**
> Compiladores online são preferíveis para projetos de arquivo único, visto que é muito imporvável que o compilador online esteja configurado ou seja configurável para adequar à questão informada pela equipe da BugCup e qualquer alteração na estrutura do projeto possivelmente acarretará em anulação da questão.

[JDoodle Java Compiler](https://www.jdoodle.com/)
[GDB Online Compiler](https://www.onlinegdb.com/online_java_compiler#)

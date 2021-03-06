# **Kotlin**

## [Conceitos basicos do Kotlin](https://blog.teamtreehouse.com/absolute-beginners-guide-kotlin)
Kotlin é uma linguagem orientada objetos [open source](https://github.com/JetBrains/kotlin) fornecida pela **JetBrains**, focado para desenvolvimento Android . O Kotlin tem a sintaxe e conceitos semelhantes a outras linguagens de programação como **C#** e **Java**.

## Usando Kotlin
Para começar, a primeira coisa que você vai precisar vai ser um lugar para programar. Uma opção seria escrever Kotlin no website [try.kotlinlang.org](http://try.kotlinlang.org/) ou criando um projeto no **IntelliJ IDEA**, [para criar siga esses passos](https://developer.android.com/kotlin/get-started.html)

## Basicos Kotlin

### Variáveis
Para criar uma variavel em Kotlin se usa a expressão:
```var greeting: String = "Hello World!"```
ou
```var greeting = "Hello World!"```
neste caso o Kotlin já identifica qual tipo 

Depois de você criar você pode modifica-la usando:
```greeting = "Hello Kotlin!"```


#### Strings

Para juntar variaveis em uma string basta usar o prefixo ```+```:
```greeting = "Hello Kotlin!" + outraVariavel```

Tambem tem como usar variaveis dentro do texto usando ```$```:
```greeting = "Hello Kotlin! $outraVariavel"```


#### Numbers

Os tipos numericos que o Kotlin pode variar entre **Int, Long, Float e Double**. Int e Long são os mais usados, enquanto Float e Double são usados para valores decimais.
Por padrão, qualquer numero inteiro vai ser definido como **int**, e qualquer numero decimal vai ser definido como **double**:

```val num1 = 42 // Int```

```val num1 = 3.14 // Double```

Se você quiser definir uma variavel como Floar ou como Long, é só adicionar **'f'** ou **'L'** no final do numero:

```val num1 = 42L //Long```

```val num2 = 3.14f //Float```

Você tambem consegue converter diferente tipos de tipo numericos usando a função **toType**:

```val num1 = 42.toFloat()```

```val num2 = num1.toDouble()```

#### Booleans
Kotlin também possui o tipo booleano. uma variável booleana representa **true** ou **false**. 

```val isGoodDay = true```

```val isBadDay = false```

#### Nullabilitydsds
















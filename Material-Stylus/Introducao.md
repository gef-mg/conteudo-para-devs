![Logo-Stylus](stylus-logo.png)

# Sobre O Stylus

O Stylus é um pré-processador que tem como objetivo principal gerar folhas de estilo organizadas. Para usa-lo é necessário ter em sua máquina instalado NodeJS e o próprio Stylus.

## Instalação do Stylus

Abra o terminal ou CMD e digite o comando abaixo:
npm install stylus -g

## Compilando e observando

Para compilar e observar o processo, utilizamos o seguinte comando: stylus -w estilo.styl -o estilo.css 

### Criando nosso "Hello World"

Para criamos nosso “Hello World”, crie uma pasta de nome stylus, após criada a pasta crie um arquivo com nome de estilo.styl. Feito os processos anteriores abra o terminal e digite o comando: stylus -w estilo.styl -o estilo.css, por fim tecle enter para que possa começar a compilar. Caso tudo ocorra certo você verá um arquivo css criado. Em seu editor de código digite o seguinte código:

```Stylus
body{
    background-color: #333;
}
```

### Maneiras de escrita com Stylus

No Stylus você pode escrever de maneira simples, baseada no modelo do Sass ou até mesmo na maneira “clean” sem as chaves os dois pontos e ponto e vírgula, para que fique claro abaixo exemplos das formas citadas.

##### Maneira simples

```Stylus
h1{font-size: 1rem;}
h1 span{font-size: 0.5rem;}
```
##### Maneira com base no Sass
```Stylus
h1{
    font-size: 1rem;
    span{
        font-size: 0.5rem;
    }
}
```
##### Maneira clean
```Stylus
h1
    font-size 1rem
    span
        font-size 0.5rem
```


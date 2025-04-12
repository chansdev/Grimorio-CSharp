# Grimorio-CSharp
Coisas de C# na Unity

## Criando Variáveis
Para criar variáveis no C# é preciso indicar qual o tipo da variável _(podendo ser int, float, string ou bool)_, nomear e adicionar. e para fechar a linha de código basta adicionar um ponto e vírgula _(;)_ no final do cófigo.<br>
<br>**int**: Valor numeral inteiro.
```c#
  int vidaPlayer = 100;
```
**float**: Valor de número quebrado.
```c#
  float danoPlayer = 5.5;
```
**string**: Texto literal.
```c#
  string mensagemMorte = "Você morreu! Clique R para renascer.";
```
**bool**: Valor verdadeiro ou falso.
```c#
  bool playerMorto = false;
```
#### OBS
É possível adicionar mais de uma variável do mesmo tipo na mesma linha de código sem precisar indicar o seu tipo novamente.
```c#
  int vidaPlayer = 100 , vidaEnemy = 70;
```
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTDZdKsWm1Hsw_C37ZmcicGptfPrBl1YdwJ0A&s" width="400px" height="200px">

## Funções Príncipais da Unity
Quando se cria um arquivo C# novo na Unity ele vem pré-setado com 2 funções principais, a start e update.<br>
<br>**start**: Roda o código apenas quando o projeto é iniciado.
```c#
  string teste = "Hello World";

  private void start() {
    print(teste);
  }
```
**update**: Roda o código em loop, ou seja, fica se repetindo o tempo todo.
```c#
  string teste = "Hello World";

  private void update() {
    print(teste);
  }
```

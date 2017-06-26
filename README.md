# Desafio Muxi Android
O aplicativo deverá consumir o json obtido através de GET na URL https://raw.githubusercontent.com/muxidev/desafio-android/master/fruits.json e utilizar código nativo (C/C++) para realizar um processamento.

### O aplicativo deverá conter
 - Lista de frutas. 
 - Cada Item da lista deve exibir o nome da fruta e preço em dollar.
 - Quando ocorrer o click em item da lista, deverá ser apresentada uma tela de mais informações. Nela, uma foto, nome e preço em dollar e em real. 
  - A preço em real deverá ser calculado assincronamente através de um código nativo (C/C++), sendo que 1 dollar corresponde a 3,5 reais. 
  Exe: CalculeNative.java
  - ```java
    public class NativeConvert {
        public void native asyncConverteToReal(float valueToConvert);
        public void nativeCallBack(float convertedValue){
            // body
        }
    }
      ```
  
  
### A solução DEVE conter
- Sistema de build Gradle
-  Material Design

### Ganha + pontos se conter
- Framework para comunicação com API
- Testes no projeto (unitários e por tela)
- Testes funcionais (que naveguem pelo aplicativo como casos de uso)
- Cache de imagens e da API
- Suportar mudanças de orientação das telas sem perder estado
 


### **Processo de submissão** ###

O candidato deverrá implementar a solução e enviar um pull request para este repositório com a solução.
O processo de Pull Request funciona da seguinte maneira:
- Candidato farrá um fork desse repositório (não irá clonar direto!)
- Fará seu projeto nesse fork.
- Commitará e subirá as alterações para o __SEU__ fork.
- Pela interface do GitHub, irá enviar um Pull Request.

Se possível deixar o fork público para facilitar a inspeção do código.

### **ATENÇÂO** ###
Não se deve tentar fazer o PUSH diretamente para ESTE repositório!

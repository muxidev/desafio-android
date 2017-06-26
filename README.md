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
- Suporte a mudança de orientação das telas sem perder estado
- README com explicações sobre o projeto, decisões tomadas, como gerar o apk e como rodar os testes
 


### **Processo de submissão** ###
O tempo para executar pode variar, porém é esperado que o mesmo seja concluído em no máximo uma (01) semana. Procure atender os requisitos na sua totalidade

O candidato deverá criar um projeto no seu github e adicionar o usuário muxilabs para acompanhamento dos seus commits

### **ATENÇÂO** ###
Não se deve tentar fazer o PUSH diretamente para ESTE repositório!

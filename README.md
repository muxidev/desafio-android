# Desafio Muxi Mobile
O aplicativo deverá consumir o json obtido através de GET na URL https://raw.githubusercontent.com/muxidev/desafio-android/master/fruits.json e utilizar código C/C++ para realizar um processamento.

### O aplicativo deverá conter
 - [1] Lista de frutas. 
 - [2] Cada Item da lista deve exibir o nome da fruta e preço em dollar.
 - [3] Quando ocorrer o click em item da lista, deverá ser apresentada uma tela de mais informações. Nela, uma foto, nome e preço em dollar e em real. 
 - [4] O preço em real deverá ser calculado assincronamente através de um código nativo (C/C++), sendo que 1 dollar corresponde a 3,5 reais.
  - Exe: CalculeNative.java
	```java
    public class NativeConvert {
        public void native asyncConverteToReal(float valueToConvert);
        public void nativeCallBack(float convertedValue){
            // body
        }
    }
      ```
  

### Ganha + pontos se conter
- [5] Cache de imagens e da API
- [6] Framework para comunicação com API
- [7] Testes no projeto (unitários e por tela)
- [8] Testes funcionais (que naveguem pelo aplicativo como casos de uso)
- [9] Suporte a mudança de orientação das telas sem perder estado
- [10] Build do apk utilizando o Android.mk (Android)
- [11] Material Design
- [12] README com explicações sobre o projeto, decisões tomadas, como gerar o apk e como rodar os testes
 


### **Processo de submissão** ###
O tempo para executar pode variar, porém é esperado que o mesmo seja concluído em no máximo uma (01) semana. Procure atender os requisitos na sua totalidade

O candidato deverá criar um projeto no seu github. Após o término do desafio (no momento que seu código puder ser analisado), deverá adicionar o usuário Muxi Labs como colaborador para análise do código.
 - Para dar permissão ao usuário Muxi Labs, o candidato deve selecionar a opção "Settings" no seu repositório, depois clicar na opção "Collaborators" e buscar pelo usuário Muxi Labs, como na figura abaixo.
![Alt text](images/add-permission.jpg?raw=true "Exemplo de como dar permissão para o usuário Muxi Labs")
### **ATENÇÂO** ###
Não se deve tentar fazer o PUSH diretamente para ESTE repositório!

Código nativo significa um código escrito na mesma linguagem que o sistema operacional. No caso Android, C/C++ ([Android NDK](https://developer.android.com/ndk/index.html)).

Não serão analisados projetos que não contemplarem os requisitos: [1], [2] e [3].

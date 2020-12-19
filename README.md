# Trabalho TT_304 - Sistemas Operacionais
**VexorDevs** - Vinícius Fiorio Ribeiro dos Santos 167864

### Descrição do Trabalho
O trabalho consiste em desenvolver um código que por meio do uso de semáforos e da biblioteca pthread consiga "alinhar" os threads que estão sendo executados ao mesmo tempo e em loop infinito para que a saída do programa seja uma sequência de elementos químicos "HHSOOOO" e esse processo deve se repetir a quantidade de vezes que o usuário determinou.

- [x] Utilizar a biblioteca Pthreads
- [x] Utilizar semáforos
- [x] Não alterar a estrutura padrão dos threads (deixar em loop infinito)
- [x] Não adicionar nenhuma estrutura de repetição

Você pode visualizar o codigo que foi desenvolvido e executá-lo, para isso você deve seguir alguns passos:
### Instalando o GCC
1. Baixe o arquivo **main.c** que está disponível nesse mesmo repositório.
2. Após isso em seu terminal execute os seguintes comandos para podermos compilar o nosso arquivo sem problemas.
3. Para atualizar os pacotes do seu terminal ``` sudo apt update ```
4. Para instalar o gcc (Gnu Compiler Collection)  ``` sudo apt install build-essential ```. Confirme digitando 'Y'.
5. Para verificarmos se o gcc foi corretamente instalado degite em seu terminal ``` gcc --version ```.

### Compilando e Executando o arquivo
1. Encontre o local do arquivo que foi baixado.
2. Compile o programa da seguinte forma ```gcc main.c -pthread -o prog```. Em algumas distribuições possa ser que vc tenha que alterar a flag ```-pthread``` para  ```-lpthread```. 
3. Isso irá criar um arquivo chamado **prog**.
4. Para executar esse arquivo digite ```./prog```.
5. Caso não apareça nenhuma mensagem de erro, quer dizer que o programa foi compilado e executado com sucesso.

### Utilizando o programa
1. Logo após o programa ser executado na primeira linha aparecerá o seguinte: 
> Numero de repeticoes: 
2. Onde você deverá digitar um número inteiro positivo qualquer.
3. Por exemplo, se você digitar o número **3**, O programa deve responder como saída o seguinte:
> HHSOOOO  
> HHSOOOO  
> HHSOOOO  
4. Após imprimir a sequência o programa é encerrado, caso queira utilizar novamente basta refazer os passos anteriores de execução.

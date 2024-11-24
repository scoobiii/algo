# algo
Estrutura de dados e algoritmos para crianças

Aqui está uma versão melhorada e organizada do enunciado, com explicações para cada etapa, utilizando linguagem simples e explicando os conceitos necessários para uma criança de 10 anos (complementando conforme necessário). Também incorpora conceitos como design patterns XP e JIT.


---

README - Como Entender e Testar Código

Este README explica como testar e entender o código usando várias tecnologias e abordagens. Vamos aprender passo a passo!


---

Código Base

Aqui está o código que usaremos para testar:

var num = 1;  // {1}
console.log('num : ' + num);

num = 3; // {2}
var price = 1.5; // {3}
var Myname = 'Packt'; // {4}
var trueValue = true; // {5}
var nullVar = null; // {6}
var und; // {7}

console.log('num : ' + num);
console.log('Myname : ' + Myname);
console.log('trueValue : ' + trueValue);
console.log('nullVar : ' + nullVar);
console.log('und :' + und);


---

O Que Vamos Fazer?

1. Entender o Código:

Esse código cria variáveis diferentes: números, texto, valores "verdadeiros" e "nulos".

Mostra os valores dessas variáveis no console (uma espécie de tela de resultados no computador).



2. Executar o Código em diferentes linguagens e ambientes (como navegadores ou Node.js).


3. Medir Performance:

Quanto tempo leva para rodar.

Quanto de memória e CPU ele usa.



4. Usar um RAMDisk:

Um tipo de disco mais rápido feito na memória do computador.

Comparar se é mais rápido executar o código nele.





---

Como Executar?

Passo 1: Em Vários Ambientes

Vamos rodar o código em diferentes tecnologias. Aqui está o plano:

1. Bash (Linha de Comando):

Não dá para rodar diretamente em bash porque o código é JavaScript.

Mas podemos rodar um comando como node script.js.


2. C:

Traduzir o código para C (precisa entender bem como cada linha funciona no JavaScript).


3. Java:

Criar um applet Java que simula o mesmo código.

Adicionar no navegador para teste.


4. TypeScript:

Adaptar o código para TypeScript e rodar usando tsc (TypeScript Compiler).


5. WebAssembly (WASM):

Transformar o código para WASM usando um compilador.


6. JavaScript Dentro de HTML:

Colocar o código dentro de uma página HTML com <script> e abrir no navegador.


7. Node.js:

Criar um arquivo script.js e executar com node script.js.


8. Rodar no Navegador Como URL:

Criar uma URL com o código e abrir no navegador.



---

Medir Tempo e Recursos

1. Node.js:

Medir:

Tempo de execução.

Consumo de memória e CPU.




2. Navegador (Chrome no Android):

Medir o mesmo que acima.



3. Java Applet no Navegador:

Medir o mesmo que acima.



4. JVM (Java Virtual Machine):

Rodar e medir tempo, memória e CPU.





---

RAMDisk

1. Criar um RAMDisk de 100 MB:

No Linux, use:

sudo mount -t tmpfs -o size=100M tmpfs /mnt/ramdisk

Torne permanente adicionando no arquivo /etc/fstab:

tmpfs /mnt/ramdisk tmpfs size=100M 0 0



2. Crie uma pasta variaveis no RAMDisk:

Mova o código e documentos para /mnt/ramdisk/variaveis.



3. Execute o código no RAMDisk e compare:

Tempo de execução.

Memória usada.

CPU consumida.





---

O Que É Máquina Virtual?

Uma máquina virtual é um ambiente que simula um computador dentro de outro. Por exemplo:

JVM (Java Virtual Machine) roda programas Java.

Node.js roda JavaScript fora de navegadores.


RAMDisk pode ser usado para simular memórias rápidas e testar performance.


---

Design Patterns e XP

Usamos o padrão XP (Extreme Programming):

Testes pequenos e frequentes.

Melhorias contínuas (JIT - Just In Time).


No código:

Simplicidade e clareza para ser mais rápido e fácil de entender.



---

Execute os testes e documente os resultados para aprender mais sobre performance e tecnologias!


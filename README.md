![Bash](/images/header.jpg)

<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/Claudenir-Nojosa/Bash-Course.svg?style=social&label=Star&maxAge=2592000)](https://github.com/Claudenir-Nojosa/Bash-Course/stargazers/)

</div>

# 🌌 Fato: Aprenda Bash da maneira mais fácil possível (até sua Vó aprenderia) 🌌

## 👣 Passo-a-passo

<p>
<strong>	1.</strong> Entender o que é Bash/Shell <br>
<strong>	2.</strong> Porque é importante saber sobre <br>
<strong>	3.</strong> Tipos de Shell <br> 
<strong>	4.</strong> Quais são os comandos e atalhos <br>
<strong>	5.</strong> Considerações finais

<table>
  <tr>
    <td>   
        <img height="150em" src="/images/t1.png"/>
    </td>
    <td>     
        <img height="150em" src="/images/t2.png"/>
    </td>
        <td>     
        <img height="150em" src="/images/t3.jpg"/>
    </td>
     <td>      
        <img height="150em" src="/images/t4.jpg"/>
    </td>
    <td>      
        <img height="150em" src="/images/t5.jpg"/>
    </td>
  </tr>
</table>
</p>

---
<p align="center">
<img height="250em" src="/images/children.jpg"/>
</p>
<h2> 🎃 O que é Bash/Shell (PARA UMA CRIANÇA ENTENDER) 🎃 
</h2>

<p>
Bash é um acrônimo para “Bourne Again Shell”, desenvolvido em 1989. É um programa Shell executado em uma interface de linha de comando e tem como principal função controlar sistemas operacionais.

Mas antes de falar sobre o que é Bash, precisamos falar sobre o Shell, o que nada mais é do que um programa que controla sistemas operacionais, é como se fosse a ponte de comunicação entre o núcleo do Sistema Operacional e o usuário/aplicações.

Esse núcleo do Sistema Operacional se chama Kernel, é ele que gerencia as operações do computador e do hardware.

Por fim, Shell funciona de duas maneiras:
<ul>
<li>Ou por meio de uma <strong>GUI (Graphical User Interface)</strong> 
</li>
<li>
Ou de uma <strong>CLI (Command Line Interface)</strong>
</li>
</ul>

Um exemplo de Shells GUI é, no Windows 10, a possibilidade do usuário controlar o sistema operacional do dispositivo clicando nos botões da barra de tarefas e em menus.

Entretanto, o Bash é um Shells CLI, então para que ele funcione, o usuário precisa escrever comandos.

🍊 Analogia básica para entender o que é Shell 🍊

<p align="center">
<img height="250em" src="/images/orange.jpg"/>
</p>

<p>
<div align="center">Imagine uma laranja</div> <br>
Essa laranja tem a parte da casca (Shell), que é a camada que faz a ponte entre a gente (usuário) e a parte de dentro (Kernel).
</p>

<h3>Diferenças entre Shell e Kernel</h3>
<ul>
<li>
Shell: Permite que o usuário se comunique com o kernel <br>
Kernel: Controla todas as tarefas do sistema
</li>
<li>
Shell: É a interface entre o kernel e o usuário <br>
Kernel: É o núcleo do sistema operacional
</li>
<li>
Shell: Executa comandos em um grupo de arquivos <br>
Kernel: Executa o gerenciamento de memória
</li>
<li>
Shell: É a camada externa do Sistema Operacional <br>
Kernel: É a camada interna do Sistema Operacional
</li>
<li>
Shell: Interage com o usuário interpretando a linguagem da máquina <br>
Kernel: Interage diretamente com o hardware
</li>

</p>

---

<h2> 🔮 Porque é importante saber sobre 🔮 </h2>

<p>
Aprender Bash irá te permitir controlar o sistema operacional como um programador deve. Mas não é uma habilidade apenas para programadores, pode ser utilizado por qualquer um que trabalhe com <i>data</i>.

<ul>
<li>
Bash é popular, e paga bem 💵
<p> De acordo com "2020’s Stack Overflow’s Developer Survey", Bash/Shell é a sexta linguagem mais utilizada mundialmente, estando na frente de Python e R. Ela também foi associada com salários maiores, de acordo com a pesquisa.
</p>
</li>
<li>
Linhas de comando ajudam em processos repetitivos de data 💾
<p> Parte do trabalho de um cientista de dados é ter a certeza constante que certa informação está disponível, muitas vezes diariamente. A maioria do <i>data</i> é adquirido, processado e disponibilizado na mesma maneira.
A linha de comando serve muito bem para esse propósito pois os comandos são facilmente automatizados e replicados.
</p>
</li>
<li>
Trabalhar com arquivos de texto é mais fácil ⌨
<p> Arquivos de texto é uma das maneiras mais comuns de armazenar arquivos de <i>data</i>. 
</p>
</li>
<li>
Necessita de menos recursos da máquina 🖥
<p> Quanto você está trabalhando com um computador de recursos limitados, e simplesmente deseja aumentar a velocidade de processamento, o uso de linhas de comando vai ser sempre melhor do que usar um GUI, pois o GUI irá dedicar mais recursos para renderizar a parte visual gráfica.
Isso funciona tanto localmente como remotamente. Quando conectado remotamente, GUI's consomem muito mais recursos do que CLI's.
</p>
</li>
<li>
Você provavelmente consegue digitar mais rápido do que clicar 🖱
<p> Mesmo se você achar que é mais rápido clicando, há uma boa chance de que pelo menos em algumas tarefas, você vai ser mais eficiente via linha de comando.
</p>
</li>
<li>
Você pode se acordar colocando um alarme 🕰
<p> 

```
sleep 20m && madplay song.mp3
```

</p>
</li>

---

<h2> 🛰 Tipos de Shell 🛰 </h2>
<div align="center">
<table>
    <thead>
        <tr>
            <th>
            Linux
            </th>
            <th>
            Windows
            </th>
            <th>
            UNIX
            </th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
            Bourne-Again
            </td>
            <td>
            Aston 
            </td>
            <td>
            Korn  
            </td>
        </tr>
        <tr>
            <td>
            Tcsh 
            </td>
            <td>
            Window Blinds
            </td>
            <td>
            The C 
            </td>
        </tr>
        <tr>
            <td>
            ---
            </td>
            <td>
            Xoblite 
            </td>
            <td>
            Bourne-Again 
            </td>
        </tr>
    </tbody>
</table>
</div>
</p>

---

<h2> 🛸 Comandos e atalhos 🛸 </h2>

<p>
Dentro do Bash há vários comandos e atalhos para conseguir agilizar os procedimentos, alguns deles são:

| Comandos | Resultado |
| -------- | --------- |
| pwd | Print working directory, mostra o diretório que você está atualmente |
| cd + nome do diretório | Muda para o diretório |
| cd ~ | Volta para o diretório raíz |
| cd .. | Volta um diretório |
| ls | Lista os arquivos do diretório atual |
| mkdir + nome da pasta | Make directory, cria uma nova pasta |
| touch + nome do arquivo | Cria um novo arquivo |
| node + nome do arquivo | Faz a leitura do arquivo Js |
| cls | Limpa a tela de comando |
| start + nome do arquivo | Inicia o arquivo |
| rm + nome do arquivo | Remove o arquivo |
| rm * | Remove tudo do diretório |
| rm -r + nome da pasta | Remove uma pasta do diretório |
| CTRL + A | Move o cursor para o início da linha |
| CTRL + E | Move o cursor para o fim da linha |
| CTRL + L | Limpa o conteúdo da tela (igual ao <i>clear</i>) |
| TAB | Completa o comando que estamos escrevendo, caso haja possibilidades de completar |

</p>

---

#####  De todos os Shells disponíveis, o Bash é um dos mais populares, amigáveis e consegue superar em muitos aspectos os Shells anteriores. Estando em conformidade com o padrão POSIX P1003.2/ISO 9945.2 e permite configurar softwares, extrair dados do sistema, manipular arquivos, automatizar processos de compilação de código, monitorar rotinas, entre outras funções. A documentação do Bash está disponível no [site oficial](https://www.gnu.org/software/bash/manual/).
# Iniciando Linux na sua Maquina

1) Utilizando o interactive Mode

<img src="https://github.com/JosiTubaroski/Iniciando_Linux_Maquina/blob/main/Img/Executar_Linux.png">

### O que faz o comando docker run -it ubuntu?

O comando docker run -it ubuntu é utilizado para iniciar um novo contêiner a partir da imagem Docker do Ubuntu, com duas opções importantes:

-i (ou -interactive): Mantém a entrada padrão (stdin) do contêiner aberta, mesmo que você não esteja anexado a ele. Isso é útil para interagir com o contêiner.
-t (ou -tty): Aloca um terminal TTY para o contêiner. Isso é necessário para rodar um shell interativo dentro do contêiner.

### Comando Completo: docker run -it ubuntu

<b>docker run:</b> Este comando cria e inicia um novo contêiner a partir de uma imagem Docker especificada.

-it: Combinação das opções interativas -i e -t.
-i: Interativo, mantém o stdin aberto.
-t: Aloca um terminal TTY.
ubuntu: A imagem Docker base a ser usada para criar o contêiner. Neste caso, é a imagem oficial do Ubuntu.

### O que Acontece
Quando você executa docker run -it ubuntu, o Docker faz o seguinte:

Download da Imagem (se necessário): Se você ainda não tem a imagem ubuntu localmente, o Docker a baixa do Docker Hub.
Criação do Contêiner: O Docker cria um novo contêiner baseado na imagem ubuntu.
Execução do Contêiner: O contêiner é iniciado e um terminal interativo é aberto.
Shell Interativo: Por padrão, o comando padrão (entrypoint) da imagem ubuntu é /bin/bash. Isso significa que você terá um shell Bash interativo dentro do contêiner.

<img src="https://github.com/JosiTubaroski/Iniciando_Linux_Maquina/blob/main/Img/Dentro_Do_Linux.png">

2) Primeiro comando, verificando quem é meu usuário;

<img src="https://github.com/JosiTubaroski/Iniciando_Linux_Maquina/blob/main/Img/1_Primeiro_Comando.png">

3) Utilizando o comando apt update para fazer download dos pacotes mais recentes

<img src="https://github.com/JosiTubaroski/Iniciando_Linux_Maquina/blob/main/Img/2_Apt_Update.png">

4) Instalando um pacote

<img src="https://github.com/JosiTubaroski/Iniciando_Linux_Maquina/blob/main/Img/3_Instalando_NovoPacote.png">

### Sistema de Arquivos do Linux

<img src="https://github.com/JosiTubaroski/Iniciando_Linux_Maquina/blob/main/Img/04_Estrutura_Arquivos_Linux.png">

<img src="https://github.com/JosiTubaroski/Iniciando_Linux_Maquina/blob/main/Img/05_Estrutura_Arquivos2.png">

### Navegando no Linux

1) ls (Listando)

<img src="https://github.com/JosiTubaroski/Iniciando_Linux_Maquina/blob/main/Img/05_Comando_ls.png">

2) Acessando o diretório etc

<img src="https://github.com/JosiTubaroski/Iniciando_Linux_Maquina/blob/main/Img/06_Diretorio_ETC.png">

3) O que tem dentro do diretorio etc?

<img src="https://github.com/JosiTubaroski/Iniciando_Linux_Maquina/blob/main/Img/07_Dentro_Diretorio_ETC.png">

### Criando arquivos e diretorios

<img src="https://github.com/JosiTubaroski/Iniciando_Linux_Maquina/blob/main/Img/08_Criar_Diretorio.png">   

01 - Criando e removendo arquivos 



<img src="https://github.com/JosiTubaroski/Iniciando_Linux_Maquina/blob/main/Img/09_Criando_Arquivos.png">   

Executando multiplos comandos

<img src="https://github.com/JosiTubaroski/Iniciando_Linux_Maquina/blob/main/Img/10_Executando_Multiplos_Comandos.png">  

Gerenciando Processos

<img src="https://github.com/JosiTubaroski/Iniciando_Linux_Maquina/blob/main/Img/11_Comando_Verifica_Processos.png">  






   





   
   



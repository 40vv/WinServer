<img src="https://upload.wikimedia.org/wikipedia/commons/2/26/Windows_Server_logo.svg" width="500" height="70"/>

## Comandos de Windows Server

**echo** > mostrar se o echo está ativo

**echo off** ocultar exibições de comandos quando executar em um script (.bat por exemplo)

**echo [...]** > mostrar o que você digitou em uma linha separada

**cls / clear** > limpar o cmd

**mkdir pasta** > cria uma pasta com o nome tal (só isso)

**ver** > mostra a versão do windows (kernel e codinome)

**winver** > mostra a versão do windows (em janela e outras informações úteis)

**help** > lista de comandos disponiveís no cmd / ajuda no cmd

**netstat** > ver conexões 

**ping** > testar a comunicação entre um servidor ou computador

**whoami** > "quem sou eu" mostra qual(is) usuário(s) está(ão) conectado(s) na máquina

**whoami /user** > mostra seu usuário e seu identificador de segurança (algo como A-X-X-XX-XXXXXXXXX-XXXXXXXXX-XXXXXXXXXX-XXXX se criptografado)

**color <cor>** > muda a cor do cmd (color help pra poder ver as cores disponivel)

**doskey** > permite recurso de edição e histórico dos comandos

**doskey /history** > mostra o histórico de comandos que você executou

**shutdown** > desiga o computador, só isso kkk. se quiser ver mais comandos dele: **shutdown /?**

**shutdown /a** > cancela o desligamento do computador (coloquei esse separado porque é útil as vezes)

**ipconfig** > mostra os adaptadores de redes conectados no computador e informações gerais

**ipconfig /renew** > solicita um novo ip pro servidor dhcp

**type arquivo.txt** > basicamente o "cat" no linux
  
**date /t** > mostra a data atual

**time /t** > mostra o horário atual

**find "..." arquivo.txt** > procura a palavra especificada dentro do arquivo alvo

**findstr "..." arquivo.txt** > procura no pc inteiro o nome do arquivo especificado com a palavra tal  

**... | more** > exibe comandos grandes em página (por exemplo: **dir | more**)

**hostname** > mostrar o nome do computador ou servidor
  
**systeminfo** > informações do computador, auto-explicativo

**dir / ls** > mostrar oque contém no diretório

**help dir** > mostra os comandos disponíveis no "dir" 

**ping** > envia pacotes para tal destino, útil pra poder testar a comunicação entre si

**cd** > altera o diretório ou mostra o diretório atual

**rd pasta** > exclue uma pasta vazia

**nslookup** > mostrar informações do servidor dns conectado ao computador

**getmac** > mostrar informações do endereço MAC e interfaces de rede

**route print** > mostrar tabela com informações do roteamento do servidor

**tracert** > mostra e rastreia o caminho percorrido por pacotes de dados em sites ou ips
exemplo: tracert microsoft.com

*- Gabriel* ;) 

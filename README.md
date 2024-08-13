# Delphi-7---Atualiza-o-de-.Exe-via-FTP
Projeto para aplicações que para a atualização necessitam Atualizar o executavel

Fiz este projeto com o seguinte problema: 
Possuiamos um aplicativo Em delphi que Necessitava de Atualizações constantes que mudavam regras de negocio, correção de bugs e entre outros.
Foi desenvolvido um app que via FTP, Se conecta ao servidor e tranfere o novo arquivo .EXE para substituir na maquina local.

Processo:
- Requer instalação, caso arquivo que contenha dados do usuario não exista.
- Requer um caminho de app fixo 'C:\pasta\appExemplo.exe'
- Requer Servidor FTP , 'FTP//EndereçoAqui'

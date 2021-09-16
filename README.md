# DesafioSensorville
 
 Este projeto consiste em uma página web/site desenvolvido por mim contando um pouco da minha trajetória pessoal e profissional.
 Escolhi utilizar o framework Django por ser uma ferramenta utilizada na Sensorville. Apesar de nunca ter utilizado este framework antes, já tinha uma noção de HTML, CSS e Js e realizei um curso nesses 6 dias onde pude aprender um pouco sobre o Django e um pouco das suas ferramentas. 
 
No curso que realizei foi utilizado como exemplo a criação de um blog com o Django, portanto adaptei para a minha aplicação. Por este motivo existem apenas dois arquivos html principais, um deles referente a página inicial (home) e o outro com a formatação da página dos "posts", onde inseri as páginas da trajetória pessoal e da trajetória profissional.

                                                    INSTRUÇÕES PARA RODAR A APLICAÇÃO

- É necessário ter instalado o python (de preferência a versão 3.9.7)
- Após o download do zip do projeto e extração dos arquivos, abrir o cmd do windows (ou terminal em caso de distribuições linux) e navegar até a pasta onde se encontra o arquivo manage.py (cd ...\Site_Sensorville-master)
- Instalar as bibliotecas necessárias que estão dentro do arquivo requirements (pip install requirements.txt)
- Abrir o shell via terminal (python manage.py shell)
- Dentro do console interativo do shell importar o django (import django)
- Sair do console interativo (quit())
- Mandar rodar o servidor via terminal (python manage.py runserver)

Obs: Caso já possua alguma aplicação na porta default (127.0.0.1:8000) basta fixar uma porta qualquer no comando. Ex:python manage.py runserver 127.0.0.1:2021

Obs: Para rodar a aplicação não é necessário uma IDE mas é recomendado para uma melhor visualização do codigo fonte.

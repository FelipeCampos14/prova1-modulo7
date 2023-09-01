Tem dois dockerfiles: um pro front, outro pro back;

o do back possui ```pip install requirements```, o do front não tem porque não rodou o mesmo comando, então fiz um pip freeze, achei a versão do nodeenv, e criei um requirements manualmente;

Depois disso foram criadas duas imagens, um para cada dockerfile, sendo a do back a ```prova-felipe``` e a do front a ```prova-felipe-frontend```;

Foram criados dois containers os quais o dados de criação esta no docker-compose;

Com base nelas foi criado o docker-compose, com o dados de cração de ambas - redundante, eu sei;

Apesar de tudo, não consegui subir para o dockerhub, obtive o erro de que não existe uma imagem localmente com a tag ou não tinha permissão para entrar fazer o push, mesmo fazendo login.


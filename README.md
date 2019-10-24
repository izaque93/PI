# PI

git config --global user.name "izaque"
git config --global user.mail "izaquemalta93@gmail.com"
git config --global core.editor vim            <--define um editor
git config --list                              <--Lista tudo

#gerar ssh
ssh-keygen -t rsa -b 4096 -C "izaquemalta93@gmail.com"
enter em tudo
cd ~/.ssh/
copiar o coteudo do arquivo .pub e colar no github em settings /ssh

#parte online
adicionar arquivo para github
git push -u origin master

#fluxo de trabalho
-> modificar arquivo
-> preparar para a proxima versão
git add nome_do_arquivo
-> salvar versão localmente
git commit -am "descrição"
-> subir para github
git push -u origin master

#outros
git log

git clone git@github.com:izaque93/PI.git destino


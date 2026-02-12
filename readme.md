#projeto colaborativo 

Para realizado para fixar aprendizado de branch, merge, checkout  no github.
// verificar se está linkado com o git com o git remote;

$ git config --global user.name

// verificar o email

$ git config --global user.email "brenoach@gmail.com"

git init

git add .  (ou apertar o '+');

git commit -m "commit inicial"

escrever texto do commit sobre o botão assim

git push

adicionar os colaboradores



$ git pull --all

//o pull de todas as branches

git branch -r | grep -v '\->' | while read remote; do git branch --track "${remote#origin/}" "$remote"; done

// 
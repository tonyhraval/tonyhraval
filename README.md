## Hi there 👋

<!--
**tonyhraval/tonyhraval** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

ALIAS
git config --global alias.tree "log --graph --decorate --all --oneline"

git config --global alias.commitvacio "commit --allow-empty -m 'Commit update changes'"

TAG
git tag clase_1

git stash list
git stash pop
git stash drop

Mover entre commits donde deseas que inicie tanto atras para adelante
git reflog // muestra todos commits aunque hallas ejecutado reset
git reset --hard 7e18b2112f2eef9699079fdd28feab6a28398a29

---- Agregar alias en linux
// Ingresar y buscas # some more ls aliases
nano ~/.bashrc 
// colocas tus alias tal cual ejem  - guardas
alias kubeprod='kubectl config use....
//Final ejecutas source
source ~/.bashrc

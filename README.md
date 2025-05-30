# 🚀 Comandos Git Essenciais

---

# ✅ **Configuração inicial**

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"

🔄 Criar e Clonar Repositórios
git clone https://github.com/usuario/repositorio.git
git init

💾 Salvar Alterações
git status
git add .
git commit -m "Mensagem descritiva da alteração"

🔀 Trabalhar com Branches
git checkout -b nome-da-branch
git checkout nome-da-branch
git branch

⬆️ Enviar Alterações para o GitHub
git remote add origin https://github.com/usuario/repositorio.git
git push -u origin main
git push origin nome-da-branch

⬇️ Atualizar Projeto com Mudanças do GitHub
git pull origin main

🔁 Mesclar Branches
git checkout main
git merge nome-da-branch

🧽 Cancelar Alterações
git checkout -- nome_do_arquivo
git reset nome_do_arquivo

🔧 Outros Comandos Úteis
git log
git diff
git --help
git comando -h




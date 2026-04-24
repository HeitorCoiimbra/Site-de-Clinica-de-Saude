# Site-de-Clinica-de-Saude
Repositório para o trabalho "02.Site de Clínica de Saúde" de Criação de Sites

**O que precisa:**
- Git -> https://git-scm.com/ 
- IDE -> O recomendado é o VScode ou o Antigravity, vai do seu gosto.
- Ia  -> É recomendado o uso de IA, sejam elas nativas da IDE ou separadas.

**Como usar:**
**1. Clone o Repositório:**

Use o comando para clonar o repositório e salvar ele:
git clone https://github.com/HeitorCoiimbra/Site-de-Clinica-de-Saude.git 
(use na pasta que deseja salvar o projeto)

**2. Crie e use sua própria Branch:**
A branch é a sua versão do código, cada um terá a sua. 
**Não edite a branch main diretamente.** A branch main é a versão final, edite a sua e quando achar que está bom faça um commit (salvar a sua branch no Github) e então um pull request (salva suas mudanças na branch main)

Para criar sua branch use o comando:
git checkout -b nome-da-branch

Exemplo:
git checkout -b heitor

**3. Commit:**
O commit é a forma de salvar suas alterações no Github.

Comandos:

git add .
(Junta os arquivos)

git commit -m "descrição do que foi feito"
(Cria um commit localmente com os arquivos e uma descrição)

git push -u origin nome-da-branch
(Salva o commit no github)

Exemplo
git commit -m "Criação do README.md"
git push -u origin heitor

**4. Pull Request:**
O pull request serve para você passar suas alterações salvas na sua branch do github para a branch main.

Antes de fazer o pull request e de começar a editar alguma coisa, é bom fazer essa sequência de comandos:
git checkout main
git pull
git checkout sua-branch
git merge main

Assim você mantém seu progresso e seu pull request sempre atualizado com o main.

Como fazer:
1. Vá até o repositório no GitHub
2. Clique em Compare & pull request
3. Adicione uma descrição
4. Clique em Create pull request

Depois disso ainda não será alterado. Outro membro do grupo deve revisar antes de juntar tudo com o main.


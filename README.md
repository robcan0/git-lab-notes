# 📚 Guia Essencial de Comandos Git & Fluxo GitHub

---

## 1. Criar um repositório local e enviar para o GitHub

* Inicialize o repositório no computador com `git init`.
* Adicione os arquivos e faça o primeiro commit.
* Crie um repositório no GitHub e conecte-o ao local com `git remote add origin <URL_DO_REPOSITORIO>`.
* Envie os arquivos com `git push -u origin main`.

---

## 2. Clonar um repositório remoto para o computador

* Use `git clone <URL_DO_REPOSITORIO>` para baixar o repositório do GitHub para sua máquina.

---

## 3. Editar arquivos e registrar alterações

* Faça mudanças nos arquivos.
* Adicione ao stage com `git add .` (ou `git add <nome_do_arquivo>`).
* Crie um commit com `git commit -m "Sua mensagem de commit"`.
* Envie para o GitHub com `git push`.

---

## 4. Criar uma nova branch

* Crie e mude para a branch com `git checkout -b nome-da-nova-branch`.
* Trabalhe nela e envie com `git push -u origin nome-da-nova-branch`.

---

## 5. Abrir um Pull Request e realizar o Merge

* No GitHub, abra um Pull Request comparando sua branch com a principal.
* Após revisão, faça o merge para integrar as alterações.

---

## 6. Criar um Fork

* No GitHub, clique em **Fork** para copiar um repositório de outra conta para a sua.
* Assim você pode modificar livremente sem afetar o projeto original.
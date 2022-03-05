# *Anotações do Git*

### Comandos

> **git config --global user.name "Nome" <br>
> git config --global user.email "Email"**
> <p>Esses comandos são usados para configurar o usuario responsavel pela crianção e modificação de todos os respositorios, ele tambem aparecerá github. (sem o --global o usuario só será resposavel pelo respositorio que for configurado).<p> 

><code>**git init**</code> Inicia o git no repositório atual.

> <code>**git add .**</code> Esse comando adiciona todos as pastas e subpastas e arquivos <br>
> **<code> git add * </code>** Esse comando adiciona todos os arquivos tambem com a opção de adicionar todos os arquivos com extensão especifica  <code> "git add *.cs" </code>
> <code>**git add Arquivo.extensão** </code> Adiciona um unico arquivo.
  
><code>**git status**</code> mostra os arquivos em unmodified, untracked e modified.<br>
><code>**git rm -rf "nome do arquivo"** </code> remove os arquivos do repositório.
 
><code>git commit -m "Mensagem"</code> O comando commit salva no .git o estado atual dos arquivos com uma mensagem.
  
><code>git log</code> mostra todos os commits, seus titulos, com o hash, data e hora e autor.
><code>git log --author="nome do autor"</code> Aqui mostra os commits filtrado por autor.
><code>git shortlog </code> Mostra por ordem de autor todos os commits feito pelo autor. <code>git shortlog -sn</code> com esse adicional do -sn voce consegue só os nomes com a numeração de quantos commits cada um fez. 
><code>git config -l</code> lista as configurações.

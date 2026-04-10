# Commands Basics

## The ls Command

**EN:** Lists files and directories.
**PT:** Lista arquivos e diretórios.

**Syntax:**
ls [options] [directory]

**Example:**
ls -l /home

---

## The cd Command

**EN:** Changes the current directory.
**PT:** Muda o diretório atual.

**Syntax:**
cd [directory]

**Example:**
cd /home/user

---

## The pwd Command

**EN:** Shows the current directory path.
**PT:** Mostra o caminho do diretório atual.

**Syntax:**
pwd

**Example:**
pwd

---

## The su Command

**EN:** Switches user (usually to root).
**PT:** Troca de usuário.

**Syntax:**
su [username]

**Example:**
su root

---

## The sudo Command

**EN:** Runs a command as administrator.
**PT:** Executa comando como administrador.

**Syntax:**
sudo [command]

**Example:**
sudo apt update

---

## The chmod Command

**EN:** Changes file permissions.
**PT:** Altera permissões de arquivos.

**Syntax:**
chmod [permissions] [file]

**Example:**
chmod 755 script.sh

---

## The chown Command

**EN:** Changes file owner.
**PT:** Altera o dono do arquivo.

**Syntax:**
chown [user]:[group] [file]

**Example:**
chown user:group file.txt

---

## The cat Command

**EN:** Displays file content.
**PT:** Mostra o conteúdo do arquivo.

**Syntax:**
cat [file]

**Example:**
cat file.txt

---

## head and tail Commands

**EN:** Show beginning or end of a file.
**PT:** Mostram início ou final do arquivo.

**Syntax:**
head [file]
tail [file]

**Example:**
head file.txt
tail file.txt

---

## more and less Commands

**EN:** View file content page by page.
**PT:** Visualizam arquivos por partes.

**Syntax:**
more [file]
less [file]

**Example:**
less file.txt

---

## The cp Command

**EN:** Copies files or directories.
**PT:** Copia arquivos ou diretórios.

**Syntax:**
cp [source] [destination]

**Example:**
cp file.txt backup.txt

---

## The dd Command

**EN:** Copies and converts data.
**PT:** Copia e converte dados (baixo nível).

**Syntax:**
dd if=input of=output

**Example:**
dd if=file.iso of=/dev/sdb

---

## The mv Command

**EN:** Moves or renames files.
**PT:** Move ou renomeia arquivos.

**Syntax:**
mv [source] [destination]

**Example:**
mv file.txt newfile.txt

---

## The rm Command

**EN:** Removes files or directories.
**PT:** Remove arquivos ou diretórios.

**Syntax:**
rm [file]

**Example:**
rm file.txt

---

## The grep Command

**EN:** Searches text using patterns.
**PT:** Procura texto usando padrões.

**Syntax:**
grep [pattern] [file]

**Example:**
grep "hello" file.txt

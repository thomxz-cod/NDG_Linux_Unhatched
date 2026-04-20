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





```
C:\> ping
 
Usage: ping [-t] [-a] [-n count] [-l size] [-f] [-i TTL] [-v TOS]
            [-r count] [-s count] [[-j host-list] | [-k host-list]]
            [-w timeout] [-R] [-S srcaddr] [-c compartment] [-p]
            [-4] [-6] target_name
 
Options:
    -t             Ping the specified host until stopped.
                   To see statistics and continue - type Control-Break;
                   To stop - type Control-C.
    -a             Resolve addresses to hostnames.
    -n count       Number of echo requests to send.
    -l size        Send buffer size.
    -f             Set Don't Fragment flag in packet (IPv4-only).
    -i TTL         Time To Live.
    -v TOS         Type Of Service (IPv4-only. This setting has been deprecated
                   and has no effect on the type of service field in the IP
                   Header).
    -r count       Record route for count hops (IPv4-only).
    -s count       Timestamp for count hops (IPv4-only).
    -j host-list   Loose source route along host-list (IPv4-only).
    -k host-list   Strict source route along host-list (IPv4-only).
    -w timeout     Timeout in milliseconds to wait for each reply.
    -R             Use routing header to test reverse route also (IPv6-only).
                   Per RFC 5095 the use of this routing header has been
                   deprecated. Some systems may drop echo requests if
                   deprecated. Some systems may drop echo requests if
    -S srcaddr     Source address to use.
    -c compartment Routing compartment identifier.
    -p             Ping a Hyper-V Network Virtualization provider address.
    -4             Force using IPv4.
    -6             Force using IPv6.
```
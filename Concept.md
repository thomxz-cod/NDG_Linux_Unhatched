# Linux Concepts

## Arguments

**EN:** Arguments are values passed to a command.
**PT:** Argumentos são valores passados para um comando.

**Example:**
ls /home

→ "/home" is the argument.

---

## Options

**EN:** Options modify how a command works. Usually start with `-`.
**PT:** Opções modificam o comportamento do comando.

**Example:**
ls -l

→ "-l" is an option (long format).

---

## Administrative Access

**EN:** Some commands require root privileges.
**PT:** Alguns comandos precisam de permissão de administrador.

**Use:**
sudo command

**Example:**
sudo rm file.txt

---

## Permissions

**EN:** Define who can read, write, or execute a file.
**PT:** Definem quem pode ler, escrever ou executar.

**Types:**

* r (read)
* w (write)
* x (execute)

**Example:**
chmod 755 file.sh

---

## Regular Expressions

**EN:** Patterns used to match text.
**PT:** Padrões usados para encontrar texto.

**Example:**
grep "a.*b" file.txt

→ Matches text starting with "a" and ending with "b"

---

## Basic Patterns

### .

**EN:** Any single character
**PT:** Qualquer caractere

Example:
a.b

---

### *

**EN:** Zero or more characters
**PT:** Zero ou mais caracteres

Example:
ab*

---

### [ ]

**EN:** Any character inside brackets
**PT:** Qualquer caractere dentro dos colchetes

Example:
[a-z]

---

### [^ ]

**EN:** NOT the characters inside
**PT:** NÃO os caracteres dentro

Example:
[^0-9]

---

## How to Use (Resumo prático)

**EN:**

* Use arguments to specify target
* Use options to modify behavior
* Combine with pipes and grep for power

**PT:**

* Use argumentos para indicar alvo
* Use opções para modificar
* Combine com grep para buscas avançadas

# Terminal-Ubuntu

Criando a Estrutura 

# 🖥️ Projeto Web — Domínio do Terminal Ubuntu

Projeto desenvolvido como atividade prática de laboratório, com o objetivo de construir a estrutura de um site completo utilizando **exclusivamente a linha de comando** no Ubuntu.

---

## 📋 Sobre o Projeto

Este projeto demonstra o uso de comandos fundamentais do terminal Linux para criar, organizar, editar e versionar arquivos de um site simples — sem utilizar interface gráfica ou gerenciador de arquivos.

---

## 📁 Estrutura de Pastas
projeto_web/
├── index.html
├── README.md
├── backup_projeto.txt
├── css/
│   └── style.css
├── js/
└── img/

---

## ⚙️ Comandos Utilizados

### Navegação e Reconhecimento

| Comando | Descrição |
|--------|-----------|
| `pwd` | Mostra o caminho completo da pasta atual |
| `ls` | Lista arquivos e pastas no diretório |
| `ls -R` | Lista recursivamente toda a estrutura de pastas |
| `cd pasta` | Entra em uma pasta |

### Criação de Arquivos e Pastas

| Comando | Descrição |
|--------|-----------|
| `mkdir projeto_web` | Cria a pasta raiz do projeto |
| `mkdir css js img` | Cria múltiplas subpastas de uma vez |
| `touch index.html` | Cria um arquivo vazio |

### Cópia, Movimentação e Remoção

| Comando | Descrição |
|--------|-----------|
| `cp arquivo.txt copia.txt` | Copia um arquivo |
| `mv arquivo.txt novo_nome.txt` | Move ou renomeia um arquivo |
| `rm arquivo.txt` | Remove um arquivo ⚠️ |

### Editores de Terminal

| Comando | Descrição |
|--------|-----------|
| `nano index.html` | Abre o arquivo no editor Nano |
| `vim css/style.css` | Abre o arquivo no editor Vim |

---

## ✏️ Editores Utilizados

### Nano (index.html)
Editor simples e intuitivo. Os principais atalhos usados foram:
- **Salvar:** `Ctrl + O` → `Enter`
- **Sair:** `Ctrl + X`

### Vim (css/style.css)
Editor avançado com modos distintos de operação:
- **Entrar no modo de inserção:** `i`
- **Salvar e sair:** `Esc` → `:wq` → `Enter`

---

## 🌐 Tecnologias

- HTML5
- CSS3
- Terminal Ubuntu (Bash)
- Git & GitHub

---

## 🚀 Como Reproduzir o Projeto

```bash
# 1. Clone o repositório
git clone https://github.com/miguelbneto/projeto_web.git

# 2. Entre na pasta
cd projeto_web

# 3. Visualize a estrutura completa
ls -R
```

---

## 📤 Versionamento

O projeto foi enviado ao GitHub via terminal com os seguintes comandos:

```bash
git init
git add .
git commit -m "Projeto finalizado via terminal"
git remote add origin [https://github.com/miguelbneto/Terminal-Ubuntu]
git branch -M main
git push -u origin main
```

---

## 💡 Dificuldades Encontradas

- **Vim:** A curva de aprendizado inicial foi desafiadora, especialmente entender a diferença entre os modos de inserção e comando.
- **Nano:** Mais acessível para iniciantes, porém com menos recursos avançados.
- **Atenção ao `rm`:** O comando remove arquivos permanentemente, sem confirmação — exige cuidado.

---

## 🏆 Desafio Concluído

Utilizado o comando `ls -R` para visualizar toda a estrutura antes do push final, confirmando que todos os arquivos foram criados corretamente.

---

*Projeto criado totalmente via terminal Ubuntu* 🐧

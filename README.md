# 📜 Get Next Line - Leitura de Linhas em Arquivos

![Get Next Line](https://img.shields.io/badge/Language-C-blue) ![Makefile](https://img.shields.io/badge/Tool-Makefile-yellow) ![Norminette](https://img.shields.io/badge/Style-Norminette-green)

O projeto **Get Next Line** tem como objetivo implementar uma função em C que lê uma linha de um descritor de arquivo (file descriptor) de maneira eficiente. Este projeto ajuda os alunos a explorar a manipulação de memória, o gerenciamento de arquivos e o uso de variáveis estáticas, abordando problemas práticos comuns em sistemas operacionais.

---

## 📋 Objetivo do Projeto

🔹 Criar uma função capaz de ler **uma linha por vez** de um arquivo ou entrada padrão.  
🔹 Gerenciar múltiplos descritores de arquivo simultaneamente.  
🔹 **Otimizar a alocação dinâmica de memória** para leitura eficiente.  
🔹 Compreender o uso de **variáveis estáticas** para armazenar informações entre chamadas da função.

---

## 📚 Conceitos Principais

- 🧠 **Manipulação de Memória**: uso eficiente de alocação dinâmica para armazenar dados.  
- 📂 **Manejo de Arquivos**: leitura de dados por meio de descritores de arquivos (file descriptors).  
- 📌 **Variáveis Estáticas**: persistência de dados entre chamadas consecutivas da função.  
- 🔄 **Gestão de Buffers**: leitura em blocos para melhorar o desempenho da função.  
- 🔗 **Múltiplos Descritores**: suporte para diferentes arquivos sendo lidos simultaneamente.

---

## ✨ Funcionalidades Implementadas

### 🔤 Leitura de Linhas
- Leitura de **uma linha completa** de cada vez, incluindo o caractere de nova linha (`\n`).  
- Retorno do conteúdo lido em uma string alocada dinamicamente.  

### 🛠️ Suporte Avançado
- **Múltiplos descritores de arquivo**: a função gerencia vários arquivos ou entradas simultaneamente.  
- **Manuseio eficiente de memória**: evita vazamentos de memória ao liberar buffers alocados após o uso.  
- **Gerenciamento de erros**: tratamento de situações como descritores inválidos ou final inesperado de arquivo.  

### 🔄 Arquitetura e Otimização
- **Uso de buffers configuráveis**: tamanho do buffer ajustável com a macro `BUFFER_SIZE`.  
- **Persistência com variáveis estáticas**: armazenamento dos dados restantes entre chamadas sucessivas da função.  

---

## 🛠️ Ferramentas e Padrões

| Ferramenta/Padrão      | Descrição                                               |
|-------------------------|-------------------------------------------------------|
| **GIT**                | Controle de versão para organizar o progresso do código. |
| **Makefile**           | Automação da compilação e geração de arquivos.          |
| **Norminette**         | Verificação de conformidade com os padrões de estilo da 42. |

---

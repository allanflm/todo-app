# Todo App CLI

Este é um aplicativo de linha de comando (CLI) para gerenciar tarefas (todos), desenvolvido em Golang.
![{B66FED5D-4885-4D81-A973-A41E3FA37B73}](https://github.com/user-attachments/assets/9fe74d14-3911-4da5-92a7-e7d6d7665dd4)


## Funcionalidades

- Adicionar nova tarefa
- Listar todas as tarefas
- Marcar tarefa como concluída
- Remover tarefa

## Tecnologias Utilizadas

- Golang

## Como Executar

1. Clone o repositório:
    ```bash
    git clone https://github.com/allanflm/todo-app.git
    ```
2. Compile o projeto:
    ```bash
    go build
    ```
3. Execute o programa:
    ```bash
    go run ./
    ```

## Exemplo de Uso

```bash
# Adicionar nova tarefa
go run ./ -add "Go for a walk" 

# Listar todas as tarefas
go run ./ -list

# Marcar uma tarefa como concluída
go run ./ -toggle 2 -> este o indice da tarefa

# Remover uma tarefa
go run ./ -del 2



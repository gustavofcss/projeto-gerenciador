# Gerenciador de Tarefas (Python)

Projeto simples de um gerenciador de tarefas rodando no terminal. A ideia é praticar lógica de programação usando Python, manipulando listas, dicionários e interação com o usuário.

## Funcionalidades

* Adicionar tarefa
* Listar tarefas
* Atualizar nome de tarefa
* Marcar como concluída
* Remover tarefas concluídas
* Sair do programa

## Como rodar

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

Entre na pasta:

```bash
cd seu-repositorio
```

Execute o arquivo:

```bash
python nome_do_arquivo.py
```

## Como funciona

O programa roda em loop mostrando um menu no terminal. Você escolhe uma opção digitando um número e segue as instruções.

As tarefas são armazenadas assim:

```python
{
  "tarefa": "Estudar Python",
  "completada": False
}
```

## Melhorias futuras

* Salvar as tarefas em arquivo (json ou txt)
* Interface gráfica
* Melhor validação de entrada
* Filtros (ex: mostrar só tarefas concluídas)

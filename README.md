# API de Chamados — Semana 01

**Estudante:** Onofre Simiao de Araujo

## Objetivo

O objetivo desta atividade é criar o inicio de uma API de chamados usando Python e Flask. Por enquanto, ela terá apenas uma rota para verificar se está funcionando corretamente.

## Como instalar

Para instalar as dependências do projeto:

```bash
uv sync --locked
```

## Como executar

No terminal do Codespaces:

```bash
uv run flask --app app run --host=0.0.0.0 --port=5000
```

## Como acessar

Depois de iniciar a aplicação, use:

http://localhost:5000/

Se estiver tudo certo, aparecerá a seguinte mensagem:

```json
{
  "mensagem": "API de chamados em funcionamento"
}
```

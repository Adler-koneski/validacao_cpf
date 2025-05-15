# 🔎 Validador de CPF (HTML, CSS e JavaScript)

Este é um projeto simples de **validação de CPF (Cadastro de Pessoa Física)** feito com **HTML, CSS e JavaScript puro**, sem bibliotecas externas. O objetivo é permitir que o usuário digite um CPF e verifique se ele é válido de acordo com as regras do algoritmo oficial da Receita Federal.

---

🌐 [Clique aqui para ver a validação de CPF](https://adler-koneski.github.io/validacao_cpf/)

---

## 💡 Funcionalidades

- Campo para digitar o CPF
- Botão para validar
- Validação em tempo real ou ao clicar no botão
- Exibição de mensagem: CPF válido ou inválido
- Estilização simples e responsiva

---

## 🧪 Como funciona a validação

A validação é feita em três etapas:

1. **Remoção de caracteres não numéricos** (como pontos e traços)
2. **Verificação de CPFs inválidos conhecidos**, como `111.111.111-11`
3. **Cálculo dos dígitos verificadores** com base nos 9 primeiros dígitos


# 📌 Sobre esta organização

Esta é a organização oficial da disciplina de **Desenvolvimento Front-end** do Senac Contagem.
Aqui vamos centralizar os repositórios dos **exercícios e atividades práticas** da turma, além de
alguns **materiais de apoio** disponibilizados ao longo do curso.

O objetivo é usar o GitHub como ele é usado no mercado de trabalho: um espaço de **controle de
versão** e **colaboração**, onde cada entrega fica registrada, organizada e visível para consulta
a qualquer momento — inclusive depois de formados, como parte do seu portfólio.

[Cadastro de Usuários](https://forms.gle/AsgDcE9E5BjZU2q28)

---

## 📚 Materiais de apoio

Slides, resumos e exemplos usados em aula ficam disponíveis no repositório
[`materiais-de-apoio`](https://github.com/facsenac-contagem-front-end/materiais-de-apoio).

---

## 🗂️ Como os repositórios estão organizados

Cada **exercício ou atividade** proposta em aula tem o **seu próprio repositório**, compartilhado
por toda a turma. Ou seja: **não existe um repositório por aluno** — todos enviam suas soluções
dentro do mesmo repositório da atividade, cada um na sua pasta.

```
facsenac-contagem-front-end/
├── atividade-01-estrutura-html/
├── atividade-02-css-basico/
├── atividade-03-git-github/
├── projeto-final-front-end/
└── materiais-de-apoio/
```

Dentro de cada repositório de atividade, a organização segue **um padrão fixo**: uma branch por
aluno, identificada com nome e sobrenome. Exemplo: `tamara-simoes`.

> 🔎 Sempre leia o `README.md` de cada repositório antes de começar — é lá que está o enunciado,
> os critérios de avaliação e a data de entrega da atividade.

---

## 🚀 Primeiros passos: como acessar e enviar sua atividade

1. **Aceite o convite** para a organização (você recebe por e-mail ou link enviado em aula).
2. **Clone** o repositório da atividade indicada pelo professor:
   ```bash
   git clone https://github.com/facsenac-contagem-front-end/NOME-DA-ATIVIDADE.git
   cd NOME-DA-ATIVIDADE
   ```
3. **Crie uma branch** com seu nome para trabalhar isoladamente:
   ```bash
   git checkout -b nome-sobrenome
   ```
4. **Execute a sua atividade** dentro da sua branch.
   
6. **Acompanhe o status, adicione e registre suas mudanças:**

   ```bash
   git status
   git add .
   git commit -m "Resolve atividade 03 - nome-sobrenome"
   ```
   
8. **Envie sua branch para o repositório remoto:**

   ```bash
   git push origin nome-sobrenome
   ```
   
10. **Abra um Pull Request** no GitHub, da sua branch para a `main`, para que o professor revise e
   aceite sua entrega.

> **Atenção!** NÃO FAÇA O MERGE. Faça apenas quando for solicitado.

---

## ✅ Boas práticas e regras da turma

**Nomenclatura**
- Branch sempre em `nome-sobrenome`, minúsculo e sem acentos (ex: `joao-pereira`).
- Nunca edite ou apague a pasta de outro colega.

**Commits**
- Mensagens claras e no infinitivo/imperativo: `"Adiciona estrutura HTML da página inicial"`.
- Prefira **vários commits pequenos** a um único commit gigante no final.
- Nunca faça commit de pastas como `node_modules/` ou arquivos de sistema (`.DS_Store`, etc.).

**Entregas**
- Toda atividade é entregue via **Pull Request** — envios diretos na `main` não são aceitos.
- Respeite o **prazo informado no `README.md`** de cada atividade; PRs abertos após o prazo podem
  ser considerados entrega em atraso.
- Só marque a atividade como concluída depois que o PR for **revisado e aprovado**.

**Colaboração**
- Dúvidas técnicas podem ser registradas como **Issues** no repositório da atividade — isso ajuda
  a turma toda a ver a pergunta e a resposta.
- Sempre confira o `git status` antes de commitar, para não enviar arquivos por engano.

---

## 👨‍🏫 Contato

Dúvidas sobre acesso à organização ou aos repositórios: fale com a professora durante a aula ou
pelo canal oficial da turma, no AVA ou pelo fórum desta organização.

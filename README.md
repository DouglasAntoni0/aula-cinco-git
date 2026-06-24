# Aula Cinco Git

![HTML](https://img.shields.io/badge/HTML5-estrutura-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Git](https://img.shields.io/badge/Git-versionamento-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-rastreabilidade-181717?style=for-the-badge&logo=github&logoColor=white)

Repositório de prática inicial com Git e HTML, criado para consolidar o ciclo básico de trabalho em um projeto versionado: criar arquivos, alterar conteúdo, registrar histórico e manter uma documentação mínima compreensível para qualquer pessoa que acesse o repositório.

Apesar de ser um exercício introdutório, ele tem um papel importante dentro de uma trilha de Quality Engineering. Antes de automatizar testes, configurar pipelines ou escrever cenários robustos, é necessário dominar o fluxo de versionamento e a disciplina de documentação. Este repositório registra exatamente essa base.

> A proposta aqui não é apresentar uma aplicação complexa. A proposta é demonstrar fundamento: organização, versionamento, rastreabilidade e comunicação técnica desde os primeiros passos.

## Objetivo do projeto

O objetivo principal é praticar um fluxo simples, porém essencial:

1. Criar uma estrutura básica de projeto.
2. Versionar arquivos no Git.
3. Publicar o repositório no GitHub.
4. Manter um README que explique o que existe no projeto e por que ele existe.
5. Tratar até um exercício pequeno como entrega rastreável.

Esse tipo de cuidado é relevante em QA porque documentação ruim, histórico confuso e arquivos sem contexto dificultam investigação de falhas, revisão de código, auditoria de evidências e colaboração com outros profissionais.

## O que este projeto demonstra

| Competência | Evidência no repositório | Valor para QA/Engenharia |
| --- | --- | --- |
| Versionamento com Git | Projeto publicado e versionado no GitHub | Permite rastrear evolução e entender mudanças ao longo do tempo |
| Estrutura HTML | Arquivo `index.html` como base de página estática | Ajuda a reconhecer elementos, estrutura de DOM e base de aplicações web |
| Organização mínima | Separação entre README e artefato executável | Facilita leitura e manutenção do projeto |
| Documentação técnica | README com objetivo, comandos e contexto | Reduz ambiguidade para quem acessa o repositório |
| Mentalidade de entrega | Exercício simples tratado com padrão profissional | Mostra atenção a detalhes, consistência e comunicação |

## Estrutura do repositório

```text
.
├── README.md      # Documentação do projeto
└── index.html     # Página HTML base usada no exercício
```

A estrutura é propositalmente simples. Ela permite focar no essencial: entender onde está o arquivo principal, como abrir o projeto e qual aprendizado o exercício registra.

## Como visualizar localmente

Clone o repositório:

```bash
git clone https://github.com/DouglasAntoni0/aula-cinco-git.git
cd aula-cinco-git
```

Abra o arquivo `index.html` no navegador. Em sistemas com interface gráfica, também é possível abrir o arquivo diretamente pelo explorador de arquivos.

## Fluxo Git praticado

Um fluxo típico de prática para este repositório seria:

```bash
git status
git add index.html README.md
git commit -m "Atualiza estrutura da aula cinco"
git push
```

Esse fluxo reforça três hábitos importantes:

- verificar o estado do repositório antes de commitar;
- adicionar apenas os arquivos desejados;
- usar mensagens de commit objetivas;
- enviar o histórico para o GitHub.

## Resultado técnico

Este projeto registra uma etapa de fundação: domínio do ciclo mínimo de trabalho com GitHub, edição de arquivos, organização de repositório e publicação de uma base HTML simples.

Para um perfil de QA Automation/SDET, esse fundamento é mais importante do que parece. Um profissional que entende versionamento consegue investigar regressões, comparar mudanças, revisar histórico, organizar evidências e colaborar melhor com times de desenvolvimento.

## Competências evidenciadas

- Noções iniciais de Git e GitHub.
- Organização de projeto simples.
- Leitura básica de estrutura HTML.
- Documentação objetiva de escopo.
- Cuidado com rastreabilidade desde exercícios iniciais.

## Possíveis evoluções

Este repositório pode evoluir de forma natural para:

- adicionar conteúdo semântico ao `index.html`;
- incluir um arquivo CSS para separar estrutura e estilo;
- publicar a página com GitHub Pages;
- criar uma pequena checklist de validação manual;
- usar o projeto como alvo inicial para inspeção de DOM e seletores.

## Conclusão

A força deste repositório está no básico bem feito. Ele mostra o início da trilha: versionar, documentar, organizar e entregar. Esses hábitos sustentam projetos mais avançados de automação, testes de API, performance, mobile e CI/CD presentes no restante do perfil.

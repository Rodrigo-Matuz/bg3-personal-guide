[English](README.md) | [Português](README.pt-BR.md)
# Baldur's Gate 3 — Guia Pessoal

Um guia de referência pessoal para **Baldur's Gate 3**, focado em entender classes, subclasses, talentos, mecânicas, missões, itens e outras informações úteis enquanto jogo com uma **configuração fortemente modificada**.

O objetivo não é ser um wiki completo ou universalmente preciso de BG3. Este repositório existe principalmente como um **guia de referência rápida para mim e para amigos** que jogam com a mesma [lista de mods](https://www.nexusmods.com/games/baldursgate3/collections/pns4qv), para que eu possa consultar algo depois sem ter que redescobrir como tudo funciona.

## Propósito

Este repositório serve para responder perguntas como:

- _O que essa classe realmente faz?_
- _Qual subclass eu deveria escolher?_
- _Quais atributos são importantes para essa build?_
- _Quais talentos valem a pena pegar?_
- _Como essa mecânica realmente funciona?_
- _Quais itens são particularmente úteis para esse personagem?_
- _Existem escolhas ou consequências importantes que eu deveria lembrar?_

Em vez de tentar memorizar tudo, a ideia é manter informações úteis em um só lugar e facilitar a consulta durante uma jogatina.

## Classes & Subclasses

As páginas de classes contêm explicações e recomendações para classes individuais e suas subclasses.

Dependendo da classe, as anotações podem incluir:

- Descrição
- Estilo de jogo
- Observações de uso
- Atributos e perícias sugeridos
- Talentos recomendados
- Considerações sobre multiclasse
- Dicas gerais de jogabilidade
- Observações específicas da build

As subclasses ficam dentro das pastas de suas respectivas classes. Por exemplo:

```text
Classes/
├── Cleric/
│   ├── Life Domain.md
│   ├── Light Domain.md
│   └── ...
├── Wizard/
│   ├── Evocation.md
│   ├── Necromancy.md
│   └── ...
└── ...
```

O objetivo é **compreensão**, e não simplesmente listar o que cada feature faz.

## Talentos

Os talentos são documentados com explicações práticas de quando são úteis.

Em vez de assumir que todo talento tem o mesmo valor, as recomendações podem incluir:

- Altamente recomendado
- Geralmente útil
- Depende da build
- Defensivo / situacional
- Geralmente não vale a pena

**As recomendações não são regras absolutas**. Um talento que é medíocre para um personagem pode ser excelente para outro.

## Mecânicas do Jogo

O repositório também contém explicações das mecânicas subjacentes de BG3.

Exemplos podem incluir:

- Valores de Habilidade
- Modificadores de Habilidade
- Proficiência
- Bônus de Proficiência
- CD de Resistência a Magia
- Vantagem e Desvantagem
- Tipos de Dano
- Resistência e Vulnerabilidade
- Testes de Resistência contra a Morte

Essas páginas são escritas como referências para quando eu esquecer **como algo realmente funciona**, em vez de assumir que o leitor já entende a terminologia de D&D.

## Missões & Escolhas

Anotações de missões são mantidas para situações em que lembrar de uma decisão, NPC, local ou consequência é útil.

Isso pode incluir:

- Escolhas importantes em missões
- Recompensas de missões
- Conteúdo que pode ser perdido
- Interações com NPCs
- Consequências das decisões
- Informações úteis sobre ordem ou momento ideal
- Pontos importantes para futuras jogadas

Algumas entradas podem conter **spoilers**.

## Itens

Itens úteis ou notáveis podem ter suas próprias anotações.

Exemplos:

- Equipamentos particularmente poderosos
- Itens específicos para builds
- Armas únicas
- Armaduras úteis
- Acessórios
- Itens com efeitos incomuns
- Itens que vale a pena lembrar para personagens futuros

O foco é no **porquê um item é útil**, e não simplesmente registrar seus stats.

## Conteúdo Modado

Este guia é mantido especificamente em torno da minha **configuração modada de BG3**.

A lista de mods principal usada neste projeto é **Difficulty, Immersion, Quality**:

#### [Difficulty, Immersion, Quality — Nexus Collections](https://www.nexusmods.com/games/baldursgate3/collections/pns4qv)

As informações neste repositório podem **não se aplicar ao BG3 vanilla**.

Se algo diferir entre o BG3 vanilla e o jogo modado, as informações aqui devem ser entendidas no contexto da lista de mods **Difficulty, Immersion, Quality**.

## Estrutura

O repositório é organizado em anotações separadas para que a informação possa ser acessada rapidamente, sem ter que ler um guia grande de uma vez.

```text
/
├── Classes/
│   ├── Cleric/
│   │   ├── Life Domain.md
│   │   ├── Light Domain.md
│   │   └── ...
│   ├── Wizard/
│   │   ├── Evocation.md
│   │   ├── Necromancy.md
│   │   └── ...
│   └── ...
│
├── talentos/
│   ├── War Caster.md
│   ├── Savage Attacker.md
│   └── ...
│
├── Mechanics/
│   ├── Ability Scores.md
│   ├── Proficiency.md
│   ├── Saving Throws.md
│   └── ...
│
├── Items/
│   └── ...
│
├── Quests/
│   └── ...
│
└── README.md
```

A estrutura exata pode mudar conforme o guia cresce.

## Filosofia

Este é um **guia de referência, não um livro de regras**.

As recomendações são baseadas em utilidade prática, experimentação e no ambiente modado específico em que se está jogando.

Quando algo é particularmente importante, as anotações devem explicar **por quê**, em vez de simplesmente dizer:

> "Pega isso."

Por exemplo:

> **War Caster — Precisa ter.**

é menos útil do que:

> **Conjurador de Combate (War Caster):** Excelente para conjuradores que dependem muito de concentração. O talento ajuda a manter a Concentração e aumenta a confiabilidade de magias que a exigem, tornando-o especialmente valioso para personagens que frequentemente mantêm magias de melhoria (*buffs*), penalização (*debuffs*) ou dano contínuo.

O objetivo é facilitar decisões futuras, mesmo depois de eu ter esquecido os detalhes.

## Obsidian

As anotações são escritas para funcionar bem com o **Obsidian**, usando links internos como:

```md
[[War Caster]]
[[Sculpt Spells]]
[[Proficiency]]
[[Saving Throws]]
```

Isso permite que conceitos relacionados sejam conectados diretamente, em vez de duplicar a mesma explicação em várias páginas.

**Plugins Recomendados:**
- Iconize
- Link Embed
- Linter
- Omnisearch
- Symbols Prettifier

## Spoilers

Como este repositório contém informações de missões, locais de itens, escolhas e outras anotações de gameplay, **spoilers são esperados**.

Se você estiver usando este guia enquanto joga pela primeira vez (por que você faria isso?), tenha cuidado ao navegar nas seções de `Quests` e `Items`.

## Status

Este é um projeto pessoal em andamento.

As informações podem estar:

- Incompleto
- Sujeito a alterações
- Específico para a lista de mods atual
- Baseado em testes pessoais
- Atualizado conforme novas descobertas são feitas

O guia vai crescer naturalmente junto com a playthrough, em vez de tentar documentar tudo desde o início.

---

## Sobre traduções

**Importante:** Este guia **não será traduzido** para português (pt-BR). Todo o conteúdo permanece em inglês.

Este arquivo `README.pt-BR.md` é apenas a versão localizada do README, para facilitar a compreensão do propósito e da estrutura do repositório.

No futuro, é possível que seja criado um site contendo traduções de todo o conteúdo deste guia.

---

### TL;DR

**Uma base de conhecimento pessoal de BG3 para uma jogatina fortemente modada.**

Classes. Subclasses. talentos. Mecânicas. Itens. Missões. Builds. Coisas aleatórias que eu inevitavelmente vou esquecer.

Se eu tiver que pesquisar a mesma mecânica de BG3 no Google três vezes, provavelmente ela pertence aqui.
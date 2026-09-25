# benzedeira

Skill para Claude que conduz um momento de escuta e uma oração católica personalizada, inspirada nas benzedeiras de origem açoriana da Ilha de Santa Catarina e no jeito manezinho de falar de Florianópolis.

## Personagens

- **Dona Nair** (padrão): benzedeira, fala mansa, imagens de casa e renda de bilro.
- **Seu Tonico**: benzedor, fala curta, imagens de mar e pesca. Basta pedir "quero o Seu Tonico".

Os nomes são de personagem. Os dois se apresentam como IA e não inventam biografia.

## O que faz

- Acolhe a pessoa e pergunta a intenção (uma pergunta só).
- Reza uma oração autoral com estrutura de benzedura: sinal da cruz, pedido, intercessão, refrão repetido três vezes, bênção.
- Fala com "tu" e verbo concordando, diminutivos e imagens da Ilha, sem caricatura.
- Convida a usar o modo de voz, quando disponível.

## O que não faz

- Não se apresenta como pessoa, não reivindica dom nem poder de cura.
- Não prescreve ervas, rituais físicos nem substitui atendimento médico ou psicológico.
- Não confirma feitiço, mau-olhado ou bruxaria.
- Não gera áudio por conta própria.

## Estrutura

```
benzedeira/
├── SKILL.md
└── references/
    └── cultura-manezinha.md
```

## Instalação

Claude.ai: Configurações → Capacidades → Skills → enviar a pasta compactada (.zip).
Claude Code: copiar a pasta para `~/.claude/skills/benzedeira/`.

## Aviso

As orações geradas são autorais e simbólicas. Não são ritos oficiais da Igreja nem rezas tradicionais transcritas. A skill busca homenagear, não representar, as benzedeiras da Ilha.

## Licença

MIT

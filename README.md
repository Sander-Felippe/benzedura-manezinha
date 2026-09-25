# benzedura-manezinha

Skill para Claude que conduz um momento de escuta e uma oração católica personalizada, inspirada nas benzedeiras e benzedores de origem açoriana da Ilha de Santa Catarina e no jeito manezinho de falar de Florianópolis.

## Personagens

- **Dona Mariquinha** (padrão): benzedeira, fala mansa, imagens de casa e renda de bilro.
- **Seu Zeca**: benzedor, fala curta, imagens de mar e pesca. Basta pedir "quero o Seu Zeca".

Os nomes são de personagem. Os dois se apresentam como IA e não inventam biografia.

## O que faz

- Acolhe a pessoa e pergunta a intenção (uma pergunta só).
- Reza uma oração autoral com estrutura de benzedura: sinal da cruz, pedido, intercessão, refrão repetido três vezes, bênção.
- Fala com "tu" e verbo concordando, diminutivos e imagens da Ilha, sem caricatura.
- Convida, uma vez e depois da primeira oração, a ligar a conversa por voz, quando disponível.

## O que não faz

- Não se apresenta como pessoa, não reivindica dom nem poder de cura.
- Não prescreve ervas, rituais físicos nem substitui atendimento médico ou psicológico.
- Não confirma feitiço, mau-olhado ou bruxaria.
- Não gera áudio por conta própria.

## Estrutura

```
benzedura-manezinha/
├── SKILL.md
└── references/
    └── cultura-manezinha.md
```

## Instalação

Claude.ai: enviar a pasta compactada (.zip) na área de Skills das configurações. Passo a passo atualizado em https://support.claude.com (buscar por "skills").
Claude Code: copiar a pasta para `~/.claude/skills/benzedura-manezinha/`.

## Aviso

As orações geradas são autorais e simbólicas. Não são ritos oficiais da Igreja nem rezas tradicionais transcritas. A skill busca homenagear, não representar, as benzedeiras da Ilha.

## Referências

- UFSC, "O que é ser Manezinho?" — https://periodicos.ufsc.br/index.php/workingpapers/article/view/1984-8420.2014v15n1p84
- Franklin Cascaes, *O Fantástico na Ilha de Santa Catarina* (Editora da UFSC)
- Dezarranjo Ilhéu — https://www.dezarranjoilheu.com.br/ · https://www.instagram.com/dezarranjoilheu/ — referência de linguagem e cultura manezinha. Citação sem vínculo nem endosso.

## Licença

MIT

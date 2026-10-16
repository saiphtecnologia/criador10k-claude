# Criador 10K · Máquina de Conteúdo para Claude

Skill editorial para transformar conteúdos, links, transcrições e insights em carrosséis para Instagram com o método Criador 10K.

## O que faz

A Skill conduz briefing, headlines, espinha dorsal, copy por slide, fechamento e revisão editorial.

A montagem visual, imagens e identidade final permanecem na Máquina de Conteúdo:
https://maquina.criador10k.com.br

## Instalação

Baixe `criador10k-claude-skill.zip` na release mais recente deste repositório.

No Claude, abra:

Personalização → Skills → Adicionar Skill → Fazer upload de Skill

Selecione o ZIP baixado e confirme a instalação.

Envie o arquivo de `dist/` ou da release, sem extraí-lo. O ZIP automático **Code → Download ZIP** do GitHub contém o repositório inteiro e não serve para esta instalação.

O pacote deve conter exatamente uma pasta principal:

```text
criar-carrosseis-criador10k/
  SKILL.md
  references/
    01-metodo-editorial.md
    02-modelos-e-densidade.md
    03-qualidade-e-revisao.md
```

Não inclua a pasta `skills/` no ZIP. Para empacotar com Python, a partir da raiz do repositório:

```sh
python -m zipfile -c dist/criador10k-claude-skill.zip skills/criar-carrosseis-criador10k
```

A Skill personalizada pode ser usada inclusive no plano Free do Claude quando a execução de código estiver habilitada.
## Exemplos

- "Quero transformar um conteúdo existente em carrossel."
- "Tenho um insight e quero criar uma narrativa."
- "Revise esta copy com o método Criador 10K."

## Privacidade

A Skill não possui MCP, API externa, autenticação própria, tracking ou coleta de dados.

Ela contém somente instruções editoriais e arquivos de referência.

## Suporte

Problemas e sugestões:
https://github.com/saiphtecnologia/criador10k-claude/issues

Mantido pela Saiph Tecnologia para o Criador 10K.

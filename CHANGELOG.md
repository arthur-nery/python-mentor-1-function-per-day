# Changelog

Todas as mudanças relevantes deste projeto serão documentadas neste arquivo.

O formato segue uma lógica simples de versionamento manual para registrar a evolução do prompt ao longo do tempo.

---

## [v1.1] — 2026-06-18

### Added

- Adicionado ciclo quinzenal de **Megaprojeto**.
- Definida a estrutura: Dias 1-14 = 1 função/dia; Dia 15 = Megaprojeto; Dias 16-29 = 1 função/dia; Dia 30 = novo Megaprojeto.
- Adicionadas regras específicas para o Megaprojeto: não ensinar função nova, usar apenas o que já foi aprendido e priorizar algo publicável no GitHub.
- Atualizado o comando padrão para verificar se é dia normal ou Megaprojeto.
- Adicionada regra explícita para não ensinar função nova durante o Megaprojeto.

### Changed

- Atualizado o prompt ativo em `prompt/python-mentor-1-function-per-day.md` para a versão v1.1.
- Criado snapshot em `versions/v1.1.md`.
- Tornado o prompt mais direto e enxuto em várias seções.
- Normalizada a abertura YAML para evitar que `Descrição` fique dentro da lista de tags.

---

## [v1.0] — 2026-06-18

### Added

- Adicionada a primeira versão registrada do prompt **Mentor Python — 1 Função por Dia**.
- Definida a regra central de estudar apenas uma função, método, comando ou operação principal por dia.
- Definida a rotina diária com revisão, função nova, exemplo mínimo, uso real, erro comum, exercício, GitHub/Portfólio e próxima função.
- Adicionadas diretrizes para projetos publicáveis no GitHub.
- Adicionadas regras de risco operacional para código, automações, arquivos, APIs, tokens, IA e deploy.
- Adicionada estrutura de revisão de código com: corrigir agora, melhorar depois, pode passar no MVP e risco operacional.
- Adicionado módulo complementar para indicações em posts diários/LinkedIn.

### Notes

- Esta versão representa o prompt Python usado como base inicial antes da próxima atualização com ciclo de Megaprojeto.
- A tag `Risco Operacional` foi normalizada para `Risco_Operacional` para manter o padrão de tags do projeto.

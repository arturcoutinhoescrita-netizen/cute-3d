# BÍBLIA DO PROJETO — CUTE 3D

> Fonte principal de continuidade do projeto. Sempre ler este arquivo **antes de programar** e atualizá-lo **após cada etapa comprovada**.
> Atualizado em: 2026-11-06. Estado: estrutura inicial criada localmente. Publicação remota do repositório: **pendente**.

## 1. Identidade e visão

- **Nome:** Cute 3D.
- **Formato:** jogo RPG em 3D.
- **Direção visual confirmada:** estilo *cute* (fofo, estilizado).
- **Motor:** Godot 4.7.2 (versão encontrada no Mac na criação).
- **Linguagem técnica inicial:** GDScript, sujeito a validação conforme necessidade.
- **Plataforma-alvo, câmera, combate, história, personagens, mapa, inventário e sistemas:** **a definir com a direção criativa**. Não inventar decisões para preencher lacunas.
- **Perfil de colaboração:** a pessoa criadora é iniciante no Godot. Explicar as ações em linguagem simples, em etapas, sem exigir programação manual.

## 2. Repositório e caminhos

- **Nome solicitado no GitHub:** cute 3d. **Slug técnico pretendido:** `cute-3d` (GitHub não utiliza espaços nos nomes de URL).
- **Proprietário pretendido:** `arturcoutinhoescrita-netizen`.
- **URL pretendida (NÃO CONSIDERAR CRIADA até confirmar):** `https://github.com/arturcoutinhoescrita-netizen/cute-3d`.
- **Situação GitHub:** pendente de criação/publicação por ferramenta com permissão apropriada.
- **Pasta local:** `/Volumes/Extreme SSD/MEUS JOGOS/Godot/Cute 3D`.
- **Cena inicial:** `res://cenas/principal.tscn`.
- **Bíblia:** `res://documentacao/BIBLIA_DO_PROJETO.md`.
- **Plugin de integração:** `res://addons/godot_mcp`, copiado do projeto de laboratório já existente; o funcionamento do servidor/conexão ainda exige teste.

## 3. Estado atual (ler em toda sessão)

**Marco atual: P0 — Fundação do projeto.**

O que foi preparado em 2026-11-06:
1. Confirmado Desktop Commander conectado ao Mac `Arturs-Mac-mini.local`.
2. Confirmado Godot `4.7.2.stable`.
3. Localizado projeto de laboratório anterior com plugins Godot MCP, Grass Stamp, Home Builder e Terrain3D.
4. Criada uma pasta independente para Cute 3D, sem alterar o laboratório antigo.
5. Criado `project.godot`, cena inicial com chão, luz, câmera e ambiente, e plugin Godot MCP incluído e habilitado.
6. Criada esta bíblia e uma estrutura mínima para versionamento.
7. **Testes realizados:** Godot abriu o projeto em modo editor headless (exit 0), iniciou o plugin Godot MCP, registrou 173 comandos e encerrou normalmente. A cena principal também iniciou em modo headless (exit 0). A conexão MCP externa e a inspeção visual ainda estão pendentes.
8. **GitHub:** remoto ainda não criado. Repositório Git local inicializado em `main`; commit inicial `65bf56b`. Godot aberto no Mac pelo Desktop Commander.

### Próxima ação prioritária
- Validar a abertura do projeto no Godot e a integração MCP.
- Criar o repositório privado `cute-3d` no GitHub e enviar esta estrutura após autenticação adequada.
- Definir com a direção criativa o primeiro pequeno marco jogável (ex.: personagem movimentável numa área de teste).

## 4. Princípios de produção

1. **Não apagar nem sobrescrever trabalho autoral** (cenas, modelos, texturas, mapas, saves).
2. Trabalhar em alterações pequenas, testáveis, preferindo branches para mudanças relevantes.
3. Antes de editar: ler a bíblia, verificar `git status`, identificar cena, dependências e resultado esperado.
4. Depois de editar: executar testes possíveis, verificar erros, registrar exatamente o que passou e o que permanece pendente.
5. Não publicar funcionalidades como prontas sem validação. Evitar alterar cenas principais sem motivo.
6. Usar Desktop Commander para programação e validação no Mac; usar o Godot MCP quando conectado e operacional. Não confundir plugin instalado com conexão ativa.
7. Manter linguagem acessível: explicar ao criador onde clicar no editor e qual será o resultado de cada etapa.
8. Preservar a estética cute e decisões aprovadas; não migrar o projeto inteiro do 3D Companion automaticamente.

## 5. Estrutura prevista

```text
Cute 3D/
├── project.godot
├── cenas/
│   └── principal.tscn
├── addons/
│   └── godot_mcp/
├── documentacao/
│   └── BIBLIA_DO_PROJETO.md
├── README.md
└── .gitignore
```

Pastas futuras (`personagens/`, `cenarios/`, `scripts/`, `interfaces/`, `assets/`, `testes/`) devem ser criadas quando necessárias, sem estrutura fictícia.

## 6. Escopo e roadmap

- **P0 — Fundação:** projeto abrindo, GitHub, bíblia, testes básicos, conexão com Godot. **Em andamento**.
- **P1 — Protótipo navegável:** personagem provisório, deslocamento e câmera apropriados ao RPG. **Não iniciado**.
- **P2 — Ambiente cute:** terreno, vegetação e elementos de cenário com direção visual consistente. **Não iniciado**.
- **P3 — Mecânicas RPG essenciais:** a definir após decisões de gameplay. **Não iniciado**.
- **P4 — Conteúdo e progressão:** missões, personagens e interface conforme escopo aprovado. **Não iniciado**.

Roadmap é preliminar e adaptável.

## 7. Registro de decisões

| Data | Decisão | Situação |
|---|---|---|
| 2026-11-06 | Novo projeto em Godot, separado do 3D Companion | Confirmada |
| 2026-11-06 | Nome Cute 3D, RPG 3D em estilo cute | Confirmada |
| 2026-11-06 | Documentação central no GitHub, atualizada após cada etapa | Confirmada |
| 2026-11-06 | Usar Desktop Commander e explorar plugin Godot MCP | Confirmada |
| 2026-11-06 | Primeira cena mínima com chão, luz e câmera | Base técnica, a testar |
| — | Estilo preciso, personagem, câmera, mecânicas | Pendentes |

## 8. Registro de trabalho — formato obrigatório

Para cada etapa nova, adicionar:

### AAAA-MM-DD — Nome da atividade
- **Objetivo:**
- **Arquivos alterados:**
- **Implementação:**
- **Validação realizada:**
- **Limitações/problemas:**
- **Commit/branch:**
- **Próximo passo:**

Jamais registrar teste ou commit como concluído sem confirmação.

## 9. Protocolo ao iniciar uma nova conversa

1. Localizar repositório `cute-3d` e abrir este arquivo.
2. Ler **Estado atual**, **Registro de decisões** e entradas recentes do **Registro de trabalho**.
3. Verificar o diretório local e `git status` via Desktop Commander; confirmar qual projeto está aberto no Godot.
4. Comunicar um resumo curto: etapa atual, o que já funciona, riscos e próxima ação.
5. Só então implementar alterações, testar, versionar e atualizar esta bíblia.

## 10. Questões criativas ainda abertas

- Câmera: terceira pessoa livre, isométrica ou outra?
- Personagem: estilo, proporção, movimentação e animações?
- Jogo: exploração, combate, quests, construção, diálogo ou combinação?
- Mundo: pequenas áreas conectadas, mundo aberto ou hubs?
- Plataformas-alvo: desktop, mobile, console?
- Referências visuais e direção artística aprovadas.

Nenhuma dessas decisões deve ser presumida apenas a partir de protótipos anteriores.

### 2026-11-06 — Primeira validação do projeto
- **Objetivo:** verificar se Godot carrega a estrutura inicial sem erros.
- **Arquivos alterados:** `project.godot`, `cenas/principal.tscn`, `addons/godot_mcp/`, documentação.
- **Implementação:** cena com chão de teste, luz direcional, câmera e ambiente; plugin MCP configurado.
- **Validação realizada:** editor headless exit 0, log `[Godot MCP] Plugin started` e `Registered 173 commands`; runtime headless exit 0.
- **Limitações/problemas:** não houve teste visual, nem confirmação de canal MCP externo aberto; repositório remoto GitHub ainda não criado.
- **Commit/branch:** primeiro commit local `65bf56b` na branch `main`; atualização posterior da bíblia ainda sem commit.
- **Próximo passo:** publicação privada do repo e primeira definição criativa do personagem/câmera.

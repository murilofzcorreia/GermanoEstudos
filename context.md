# 🌸 Contexto da Plataforma de Estudos - Ana Paula Germano de Oliveira

Este documento define as diretrizes, o perfil da aluna, a arquitetura da plataforma e a identidade visual para o desenvolvimento de todas as páginas e materiais de estudo gerados no projeto **AnaEstudos** com o auxílio do **Antigravity**.

---

## 👩‍🎓 1. Perfil da Estudante

- **Nome:** Ana Paula Germano de Oliveira
- **Curso:** Educação Física
- **Instituição:** UNESP – Faculdade de Ciências e Tecnologia (FCT), Câmpus de Presidente Prudente
- **Momento Acadêmico:** 2º Semestre
- **Propósito:** Uma plataforma de estudos online, organizada, intuitiva e acolhedora, criada especialmente para acompanhar sua trajetória acadêmica na faculdade.

---

## 🎯 2. Visão Geral da Plataforma

A plataforma funciona como um **hub central de aprendizagem**, permitindo navegar entre semestres, disciplinas e tópicos aprofundados.

### Principais Objetivos:
1. **Centralizar o Conhecimento:** Reunir todas as matérias da faculdade em um único local acessível e visualmente agradável.
2. **Crescimento Modular:** Através do Antigravity, criar e adicionar facilmente novas páginas, resumos, simulados, tabelas e flashcards interativos para cada novo tema estudado.
3. **Facilidade de Navegação:** Navegar de forma fluida da tela principal para a disciplina e, dela, para qualquer subpágina de conteúdo específico.

---

## 🏛️ 3. Arquitetura da Informação

A estrutura do projeto segue uma hierarquia em 3 níveis:

```
[Plataforma Principal (Dashboard / Home)]
  │
  ├── 📚 [Páginas de Disciplinas] (ex: Neuroanatomia, Fisiologia, Biomecânica, etc.)
  │     │
  │     ├── 📄 [Subpáginas por Tema / Módulo] (Resumos conceituais detalhados)
  │     ├── 🎴 [Ferramentas de Fixação] (Flashcards, Quizzes, Mapas Mentais)
  │     └── 📝 [Práticas & Fichamentos] (Roteiros de laboratório e relatórios)
  │
  └── 🗓️ [Recursos Globais] (Cronograma de provas, metas de estudo, frase motivacional)
```

### Detalhamento dos Níveis:
- **Nível 1 - Página Principal (Home / Dashboard):**
  - Boas-vindas personalizadas para a Ana.
  - Indicador do semestre em curso (2º Semestre).
  - Grade com cards visuais de todas as disciplinas ativas.
  - Acesso rápido a conteúdos recentes e revisão recomendada.
- **Nível 2 - Página da Disciplina:**
  - Ementa organizada por unidades ou semanas de aula.
  - Links para cada tema e submódulo daquela matéria.
  - Informações de avaliações, materiais de apoio e anotações gerais.
- **Nível 3 - Subpáginas de Conteúdo:**
  - Aprofundamento teórico didático com foco em Educação Física e Saúde.
  - Ilustrações esquemáticas, tabelas comparativas, mnemônicos e destaques coloridos.
  - Atividades práticas e interativas (como flashcards de memorização).

---

## 💜 4. Identidade Visual & Design System

A estética é personalizada de acordo com os gostos da Ana, combinando delicadeza, romantismo e alta legibilidade para longas sessões de estudo.

### 🏷️ 4.1 Logo Oficial da Plataforma
- **Arquivo Principal:** [`public/logo-germano-estudos.png`](file:///c:/Users/User/Desktop/AnaEstudos/public/logo-germano-estudos.png) (1254 × 1254 px, alta resolução)
- **Composição da Marca:**
  - Ilustração artística personalizada da estudante Ana (óculos pretos, cabelos escuros, blusa preta sem mangas, apoiando o queixo em atitude de foco e estudo).
  - Mesa de estudos com livro aberto de folhas brancas com marcador rosa, pilha de cadernos roxos/rosas, porta-canetas com canetas lilás e rosa e detalhe de coração, e notebook lavanda com coração no verso.
  - Halo/aura circular lavanda com pequenos corações rosa e estrelas de brilho roxas.
  - Tipografia editorial *"Germano"* em fonte serifada encorpada em roxo ameixa escuro, capelo de formatura acadêmico na letra *G*, sublinhado curvado em magenta/fúcsia, e subtítulo *"— Estudos — CADERNO DA ANA —"* com corações delimitadores.
- **Aplicações Obrigatórias nas Páginas:**
  1. **Favicon do Navegador:** `<link rel="icon" type="image/png" href="public/logo-germano-estudos.png">` em todas as páginas HTML.
  2. **Topbar / Navbar:** Emblema em `.wordmark-mark` com avatar circular (`object-position: center 20%`), borda suave e sombra sutil.
  3. **Hero Principal (`index.html`):** Moldura artística editorial (`.arch`) destacando a arte da logo oficial em tamanho grande, com tag personalizada de aluna da UNESP.
  4. **Pílulas de Disciplinas e Subpáginas:** Mini badge ou tag pill (`.deck-tag-pill`) acompanhado do avatar do logo para reforçar o pertencimento ao caderno.
  5. **Rodapé (Footer):** Mini avatar com assinatura de carinho em todas as telas da plataforma.

### 🎨 4.2 Paleta de Cores Oficial
- **Roxo Ameixa / Principal:** `#4A1F6E` / `#3B0764` / `#581C87` (títulos, botões principais e lettering da marca)
- **Lilás / Lavanda:** `#A855F7` / `#C9B1E4` / `#E6D9F2` (cards, badges, auras e superfícies)
- **Fundo / Papel Acolhedor:** `#FBF8F5` (papel quente) / `#FAF5FF` (lavanda suave) / `#FFFFFF` (branco puro)
- **Magenta / Rosa Intenso / Blush:** `#C95683` / `#DB2777` / `#F2C4D4` / `#F7E3EB` (corações, linhas de destaque e tags)
- **Texto & Legibilidade:** `#24132F` (tinta escura para leitura) e `#4E3D5C` / `#8A7B96` (suave para apoios e legendas)

### 🌿 4.3 Elementos Gráficos & Estilo
- **Flores & Lírios:** Ícones, ilustrações sutis e divisores temáticos inspirados em lírios e flores delicadas.
- **Corações Sutis:** Detalhes carinhosos em cabeçalhos, rodapés, tags de páginas e mensagens motivacionais.
- **Formas & Sombras:** Cantos arredondados suaves (`rounded-2xl`, `rounded-3xl` / 28–36px), sombras leves e difusas (`shadow-sm`, `shadow-md`), sem cantos duros.
- **Atmosfera Geral:** Delicada, feminina, serena, encorajadora, personalizada para a Ana e focada na excelência acadêmica.

---

## 🤖 5. Diretrizes para o Antigravity

Sempre que novas páginas, componentes ou conteúdos forem gerados para este projeto:
1. **Respeitar o Tom & Estilo:** Manter a paleta roxo/lilás, os detalhes florais delicados e o carinho no visual.
2. **Didática na Área de Saúde/Educação Física:** Apresentar termos técnicos com clareza, utilizando analogias, tabelas anatômicas e destaques que facilitem a memorização.
3. **Conexão Modular:** Criar caminhos claros de retorno para a página da disciplina e para a página inicial da plataforma.

---

## 📂 6. Fonte da Verdade, Gestão de Assets e Organização Automática de PDFs

A pasta `assets/` é o coração do projeto e a fonte primária de verdade de todos os resumos, páginas e flashcards.

### 🛡️ Prevenção de Alucinação & Foco Curricular
- Todas as informações conceituais, anatômicas e teóricas devem ser extraídas **estritamente dos materiais e PDFs das aulas** disponibilizados em `assets/`.
- Não inventar ou adicionar temas divergentes que não foram passados pelos professores da UNESP (FCT), garantindo que o estudo da Ana seja 100% direcionado para o que é cobrado nas avaliações.

---

### 🗂️ Protocolo Obrigatório de Ingestão e Organização de PDFs
Sempre que novos PDFs forem adicionados em `assets/` (na raiz ou em pastas soltas), o **Antigravity** deve seguir compulsoriamente os seguintes passos:

1. **Reconhecimento Inteligente de Tópico e Conteúdo:**
   - Inspecionar e ler o conteúdo do PDF (títulos, subtítulos, ementa e conceitos abordados).
   - Identificar a **Disciplina Macro** (ex: `anatomia`, `fisiologia`, `biomecanica`, etc.).
   - Identificar a **Subdisciplina / Eixo Temático** (ex: `neuroAnato`, `locomotor`, `cardiovascular`, etc.).
   - Identificar o **Tema / Assunto Específico** da aula (ex: Encéfalo e Núcleos da Base, Medula Espinal, etc.).

2. **Estrutura Hierárquica Padrão:**
   - Todos os arquivos devem ser arquivados seguindo estritamente a estrutura:
     ```
     assets/<disciplina>/<subdisciplina>/<NOME_DO_ARQUIVO_PADRONIZADO>.pdf
     ```
   - Exemplo implementado: `assets/anatomia/neuroAnato/`

3. **Criação Automática de Pastas e Subpastas:**
   - **Se a pasta da disciplina não existir:** O Antigravity deve criá-la imediatamente.
   - **Se a subpasta da subdisciplina (tema) não existir:** O Antigravity deve criá-la imediatamente dentro da disciplina correspondente, espelhando a organização adotada (ex: `anatomia/neuroAnato`).

4. **Higienização e Padronização de Nomes:**
   - Arquivos com nomes genéricos (ex: `Inserir um título (1).pdf`, `download.pdf`, `aula2.pdf`) devem ser renomeados para o nome real e descritivo do tema abordado (ex: `ENCÉFALO E NÚCLEOS DA BASE.pdf`).
   - Remover espaços residuais antes da extensão e caracteres corrompidos.

5. **Manutenção do Catálogo Vivo no `context.md`:**
   - Sempre que novos arquivos forem inseridos ou movidos, a seção de inventário do `context.md` deve ser atualizada para refletir a árvore atualizada de materiais.

---

### 📚 Catálogo Ativo de Materiais e Disciplinas

#### 🦴 Disciplina: Anatomia (`assets/anatomia/`)
- **Subdisciplina:** Neuroanatomia (`assets/anatomia/neuroAnato/`)
  1. `INTRODUÇÃO AO SNC.pdf`:
     - *Tópicos:* Divisão anatômica (SNC vs SNP) e funcional (Somático vs Visceral - Simpático e Parassimpático); Tecido nervoso (Neurônios, Células da Glia: Astrócitos, Oligodendrócitos, Micróglia, Células Ependimárias, Células Satélites, Células de Schwann); Mielinização e Nódulos de Ranvier; Sinapses e tipos de neurônios.
  2. `MEDULA ESPINAL E NERVOS ESPINAIS.pdf`:
     - *Tópicos:* Localização, limites e intumescências (cervical e lombossacral), cone medular e cauda equina; Morfologia em H medular (colunas anterior, posterior e lateral); Substância cinzenta e branca (funículos e tratos ascendentes/descendentes); Envoltórios/Meninges e líquor; Segmentos medulares e raízes; Bainhas conjuntivas (Endoneuro, Perineuro, Epineuro); Plexos nervosos (Cervical, Braquial, Lombar e Sacral).
  3. `ENCÉFALO E NÚCLEOS DA BASE.pdf` *(anteriormente Inserir um título (1).pdf)*:
     - *Tópicos:* Divisão do encéfalo (Telencéfalo, Diencéfalo, Tronco Encefálico, Cerebelo); Sulcos e giros cerebrais; Lobos cerebrais (Frontal, Parietal, Temporal, Occipital, Ínsula) e áreas funcionais (Broca, Wernicke, córtex motor/somatossensorial); Meninges encefálicas, seios da dura-máter, foice do cérebro e tenda do cerebelo; Ventrículos encefálicos e circulação do líquor (LCR); Fibras de substância branca (Comissurais, Associação e Projeção); Núcleos da base (Caudado, Lentiforme: Putâmen e Globo Pálido); Diencéfalo (Tálamo, Hipotálamo, Epitálamo, Subtálamo); Tronco encefálico (Mesencéfalo, Ponte, Bulbo); Cerebelo (Lobos anterior, posterior e floculonodular); Sistema Límbico (Giro do cíngulo, Hipocampo, Amígdala, Fórnix).
- **Subdisciplina:** Sistema Circulatório (`assets/anatomia/sistemaCirculatorio/`)
  1. `INTRODUÇÃO AO SISTEMA CIRCULATÓRIO.pdf`:
     - *Tópicos:* Sangue (plasma e elementos figurados: hemácias, leucócitos, plaquetas); Líquido intersticial e linfa; Sistema sanguífero (coração, artérias, capilares e veias; sistema fechado; trocas nos capilares; homeostase); Sistema linfático (sistema aberto, vasos, linfa e órgãos linfoides: linfonodos e tonsilas); Órgãos hematopoéticos (medula óssea vermelha, timo, baço); Posicionamento do coração (mediastino médio, base e ápice, faces, dimensões); Pericárdio fibroso e seroso (lâminas parietal e visceral, cavidade pericárdica); Paredes (epicárdio, miocárdio, endocárdio) e histologia do músculo cardíaco (sarcômeros, discos intercalares); Sulcos e septos; Câmaras (átrios e ventrículos), veias cavas e seio coronário; Valvas atrioventriculares (tricúspide, mitral) e semilunares (pulmonar, aórtica), cordas tendíneas e músculos papilares; Artérias coronárias; Ciclo cardíaco (sístole, diástole e sons "tum" e "tá").

---

## 🎴 7. Mecânica dos Flashcards & Sistema de Dificuldades

Os flashcards são um dos métodos favoritos de estudo da Ana e devem sempre contar com:
- **Classificação por Dificuldade:**
  - 🟢 **Fácil:** Conceitos básicos, definições diretas e identificações imediatas.
  - 🟡 **Médio:** Relações funcionais, processos fisiológicos e classificações intermediárias.
  - 🔴 **Difícil:** Questões detalhadas, vias neurais/anatômicas complexas, diagnósticos e integrações de múltiplos conceitos.
- **Filtros e Modos de Revisão:**
  - Permitir que a Ana filtre o baralho por nível (ex: revisar apenas os cartões classificados como "Difícil" antes da prova).
  - Permitir autoavaliação durante o estudo (marcar se achou o cartão Fácil, Médio ou Difícil) para salvar seu progresso.


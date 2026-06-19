# 📚 Guia Regional ENCCEJA 2026 — Grande Florianópolis

O **Guia Regional ENCCEJA 2026** é um site informativo responsivo desenvolvido em HTML5 e CSS3 para auxiliar jovens e adultos da Grande Florianópolis a obterem a certificação escolar. Reúne diretrizes oficiais do INEP, regras de isenção, materiais de estudo e os endereços das unidades certificadoras locais (CEJAs), tudo num portal moderno e fluido.

---

## 👩‍💻 Autora
* **Tainá Machado da Cunha**

---

## 🚀 Funcionalidades e Páginas do Projeto

O site possui uma estrutura semântica dividida nas seguintes secções:

* **Página Inicial (`index.html`):** Apresenta uma introdução ao exame, os objetivos educacionais e os pré-requisitos de idade mínima exigidos para o Ensino Fundamental (15 anos) e Ensino Médio (18 anos). O título do cabeçalho funciona como um link para retornar a esta página.
* **Locais na Grande Floripa (`locais.html`):** Informa os endereços, telefones e e-mails das unidades do CEJA (São José e Florianópolis) num formato de cartões compactos e otimizados para leitura rápida.
* **Inscrição (`inscricao.html`):** Explica o passo a passo para aceder à Página do Participante e traz um alerta detalhado sobre a taxa de ressarcimento de R$ 40,00 para quem faltou na edição anterior.
* **Materiais & Simulados (`materiais.html`):** Centraliza os links de download dos Livros do Estudante oficiais do INEP, histórico de exames anteriores (2023 a 2025) e canais recomendados de videoaulas.
* **O Dia da Prova (`prova.html`):** Reúne orientações indispensáveis sobre o Cartão de Confirmação de Inscrição, horários dos portões e materiais obrigatórios.
* **Depoimentos (`depoimentos.html`):** Espaço motivacional contendo links para relatos e histórias reais de superação de candidatos aprovados publicados no YouTube.
* **FAQ (`faq.html`):** Central de Perguntas Frequentes utilizando a nova imagem de destaque `homemEstudando.jpg`, focada nas regras de gratuidade e pontuações mínimas.

---

## 🛠️ Tecnologias Utilizadas

O desenvolvimento utilizou tecnologias web puras (*Vanilla Web*), com foco em performance e acessibilidade:

* **HTML5:** Estruturação de tags semânticas e navegação interativa (links integrados na logo).
* **CSS3:** Estilização visual unificada (`css/estilo.css`) com sistema de grelhas (*grids*), efeito visual de destaque por cor no menu ativo e design responsivo para dispositivos móveis.

---

## 📂 Estrutura de Pastas
```text
├── css/
│   └── estilo.css          # Arquivo de estilo global otimizado do site
├── index.html              # Página inicial (Apresentação do Exame)
├── locais.html             # Centros de atendimento (CEJAs) com cartões compactos
├── inscricao.html          # Guia de inscrição e regras de taxas por falta
├── materiais.html          # Links das apostilas oficiais e provas anteriores
├── prova.html              # Instruções e checklists para o dia do exame
├── depoimentos.html        # Vídeos e relatos de alunos aprovados
├── faq.html                # Central de dúvidas integrada com nova imagem
└── homemEstudando.jpg      # Imagem ilustrativa da seção FAQ

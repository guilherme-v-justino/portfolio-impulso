# Portfólio Impulso

Projetos de software desenvolvidos por **Guilherme Vicente Justino**, médico-veterinário e estudante de Ciência de Dados, a partir de problemas do dia a dia da Impulso Fisioterapia Veterinária, em Curitiba.

| Projeto | O que resolve | Tecnologias | Onde ver |
| --- | --- | --- | --- |
| Site da Impulso e Guia do Tutor | Apresenta os serviços da clínica e reúne conteúdo educativo para tutores. | HTML, CSS, JavaScript, Cloudflare | [Site em produção](https://impulsofisiovet.com.br/) · [Código-fonte](https://github.com/guilherme-v-justino/impulso-site) |
| Impulso Gestão | Reúne agenda, cadastros e atendimento em um aplicativo para Windows, com agenda sincronizada no celular. | Python, Flask, SQLite, JavaScript, Firebase | [Estudo de caso](impulso-gestao.md) |
| NutriVet | Organiza avaliação nutricional, alternativas alimentares e acompanhamento de cães e gatos. | Python, FastAPI, SQLite, JavaScript, ReportLab | [Estudo de caso](nutrivet.md) |
| Gerador de orçamentos | Compara até três opções de tratamento e prepara uma proposta para impressão ou WhatsApp. | HTML, CSS, JavaScript, localStorage | [Código da demonstração](orcamentos.html) |
| Receituário e requisição de exames | Reaproveita os dados do atendimento e gera um documento imprimível a partir da aba ativa. | HTML, CSS, JavaScript, IndexedDB | [Código da demonstração](documentos.html) |

## Como experimentar os HTMLs

Baixe o repositório pelo menu **Code → Download ZIP**, extraia os arquivos e abra um dos dois arquivos HTML no Chrome ou Edge. Os dois arquivos rodam localmente e usam configurações de demonstração próprias.

- **Orçamentos.** Digite “Marina Exemplo” e “Luna”, adicione uma alternativa e compare os totais por forma de pagamento. Os preços e descontos da demonstração são fictícios.
- **Documentos.** Escolha “Profissional Demo A”, use “Marina Exemplo” como tutora, “Luna” como paciente e preencha um endereço fictício. A aba **Requisição de exames** permite escolher um item e conferir a prévia. Os documentos são marcados como demonstração e os cadastros de teste ficam no navegador.

Os estudos de caso descrevem as decisões de produto e arquitetura. O repositório reúne as duas demonstrações em HTML e aponta para o código do site institucional.

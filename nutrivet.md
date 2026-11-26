# NutriVet

Ferramenta local de apoio ao planejamento alimentar de cães e gatos. Consolida avaliação, metas de peso, alternativas de alimentação e acompanhamento em um fluxo que gera PDFs para o tutor e para o profissional.

## Como foi construído

O aplicativo roda no Windows com interface no navegador, backend em Python e FastAPI, SQLite para armazenamento e ReportLab para os PDFs. O profissional escolhe o peso de referência para a estimativa energética, monta as alternativas e confere a distribuição por refeições.

O motor converte a participação energética dos itens em porções e ajusta o arredondamento por refeição. O total diário exibido corresponde à soma das porções servidas. O catálogo registra a fonte dos dados energéticos e impede o cálculo com entradas ainda pendentes de confirmação. Quando um plano aprovado precisa de ajuste, a ferramenta cria uma nova versão e preserva o histórico.

## Validação

O código local inclui testes de cálculo, composição, alteração de planos e geração de relatórios. O manual registra a validação clínica com casos conhecidos como uma etapa pendente.

[Voltar ao portfólio](README.md)

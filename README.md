# Analise-de-Dados-Restaurante-KI-delicia-via-Testes-de-Hipotese.
Análise de Dados Aplicada à Redução de Desperdiço de Alimentos: Um Estudo de Caso no Restaurante KI-delicia via Testes de Hipótese.

# Otimização de Processos Operacionais e Redução de Desperdício via Estatística Inferencial: Estudo de Caso no Restaurante KI-delicia

Este repositório contém os conjuntos de dados, scripts de análise preditiva/inferencial e a documentação técnica do projeto de extensão universitária desenvolvido no **Restaurante KI-delicia** (Razão Social: *Delicatessen e Panificadora Ki Delicia Ltda.*), localizado em Camaçari/BA. 

O objetivo central do projeto foi aplicar técnicas de ciência de dados e modelagem estatística para validar a eficácia de uma intervenção física no buffet *self-service*, visando a redução do desperdício de alimentos ("resto-ingestão").

---

## 📌 Visão Geral do Problema

A operação de almoço do restaurante enfrentava um volume acentuado de desperdício de alimentos deixados nos pratos pelos clientes após o término das refeições. Até a execução deste projeto, a gerência avaliava essas perdas de forma puramente empírica e visual. 

A investigação do layout identificou que os utensílios de servir (colheres e conchas) possuíam capacidade volumétrica industrial excessiva, enviesando a percepção do cliente e induzindo-o a servir porções maiores do que sua saciedade real. 

A Intervenção
Para mitigar o problema, propôs-se uma intervenção baseada em economia comportamental: substituir todos os utensílios do buffet por modelos com capacidade volumétrica reduzida em aproximadamente 30%. Este projeto foi desenhado para provar matematicamente se a troca causou um impacto real na média de descarte ou se qualquer oscilação foi fruto do acaso.


Estrutura do Repositório

text
├── data/
│   ├── amostra_antes.csv       # Dataset do Grupo de Controle (Utensílios Antigos)
│   └── amostra_depois.csv      # Dataset do Grupo Experimental (Utensílios Novos)
├── scripts/
│   └── analise_hipotese.py     # Script Python para limpeza, testes e gráficos
├── docs/
│   ├── dem_diretrizes.md       # Diretrizes de Engenharia e Modelagem
│   ├── relatorio_final.pdf     # Relatório Gerencial de Resultados
│   └── avaliaca_parceiro.pdf   # Formulário de Avaliação preenchido pelo restaurante
└── README.md                   # Documentação principal do repositório

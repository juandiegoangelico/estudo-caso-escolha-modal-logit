# Modelagem da Escolha Modal de Viagens Urbanas — Regressão Logística Binária

Estudo de caso aplicado para prever a
probabilidade de escolha do Transporte Público vs. Carro Particular, com base
em atributos socioeconômicos, da viagem e da oferta de transporte.

> **Nota metodológica:** os dados utilizados são **simulados** (n = 600),
> gerados para fins didáticos. Os coeficientes e Odds Ratio aqui reportados
> não devem ser extrapolados para decisões reais de política pública.

## Conteúdo

| Arquivo | Descrição |
|---|---|
| `Estudo_de_Caso_Escolha_Modal.docx` | Relatório completo: metodologia, resultados, interpretação de coeficientes/Odds Ratio, implicações e limitações |
| `Estudo_de_Caso_Escolha_Modal.xlsx` | Base de dados, estatísticas descritivas, tabela de coeficientes e avaliação do modelo |
| `dados_escolha_modal_logit.csv` | Base de dados bruta simulada (600 observações) |

## Resumo dos resultados

- Acurácia (teste, n=180): 68,9%
- AUC: 0,695
- Pseudo-R² (McFadden): 0,138
- Variáveis estatisticamente significativas (p<0,05): posse de carro, tempo de
  viagem por transporte público, acesso a estação/ponto próximo

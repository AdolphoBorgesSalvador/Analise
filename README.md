# Projeto de Análise de Forecast e Classificação ABC

Este repositório contém notebooks Jupyter desenvolvidos para análise de previsão de dados, classificação ABC e manipulação de grandes volumes de dados em arquivos Excel. As ferramentas utilizadas incluem Python, `pandas` e outras bibliotecas voltadas para análise e automação de tarefas repetitivas.

## Estrutura do Repositório

### Diretórios e Arquivos Principais

- **Notebooks**:
  - `analise_forecast.ipynb`: Contém análises detalhadas de previsão de dados (Forecast) e cálculo de métricas como Erro Relativo Normalizado (ERN) e acurácia.
  - `analise_previsao.ipynb`: Complementa a análise de previsões com detalhamento de saídas.
  - `classificacao_abc.ipynb`: Implementação da análise ABC para categorização de produtos ou materiais.
  - `analise.ipynb` e `analise2.ipynb`: Processamento adicional de dados e geração de relatórios.
  - `zmb51.ipynb`: Manipulação de dados históricos provenientes do sistema ZMB51.

- **Pasta Ignorada**:
  - `Arquivos/`: Contém os dados sensíveis utilizados nos notebooks, como arquivos Excel com informações de forecast, saídas e classificações. Esta pasta não é rastreada pelo Git.

---

## Funcionalidades

1. **Análise de Forecast**:
   - Cálculo de métricas de acurácia e precisão, incluindo MAPE, ERN e análise por canal de distribuição.
   - Geração de tabelas dinâmicas para sumarização de dados.

2. **Classificação ABC**:
   - Identificação de itens de maior impacto (classe A), impacto médio (classe B) e menor impacto (classe C).
   - Automatização para categorização com base em critérios definidos.

3. **Manipulação de Dados**:
   - Leitura e transformação de grandes volumes de dados em arquivos Excel.
   - Geração de relatórios consolidados em novos arquivos Excel.

4. **Automação de Processos**:
   - Processos automatizados para análise de múltiplos arquivos simultaneamente.
   - Relatórios finais exportados em formatos prontos para uso.

---

## Como Usar

### Requisitos
- **Python**: 3.x
- **Bibliotecas necessárias**:
  - `pandas`
  - `numpy`
  - `openpyxl`
  - `matplotlib` (opcional, para gráficos)

### Configuração
1. Clone o repositório:
   ```bash
   git clone https://github.com/AdolphoBorgesSalvador/Analise.git

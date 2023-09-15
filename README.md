# Teste de Personalidade Big Five

Este repositório contém código para analisar os dados do Teste de Personalidade Big Five. O Teste de Personalidade Big Five mede traços de personalidade em cinco dimensões: Extroversão, Amabilidade, Conscienciosidade, Neuroticismo e Abertura à Experiência.

## Conjunto de Dados

O conjunto de dados usado neste projeto é `data-final.csv`, que contém respostas ao Teste de Personalidade Big Five. O conjunto de dados inclui as seguintes colunas:

- `EXT1` a `EXT10`: Perguntas relacionadas à Extroversão.
- `EST1` a `EST10`: Perguntas relacionadas à Amabilidade.
- `AGR1` a `AGR10`: Perguntas relacionadas à Conscienciosidade.
- `CSN1` a `CSN10`: Perguntas relacionadas ao Neuroticismo.
- `OPN1` a `OPN10`: Perguntas relacionadas à Abertura à Experiência.
- `dateload`: Data e hora da carga da pesquisa.
- `screenw` e `screenh`: Largura e altura da tela.
- `introelapse`: Tempo necessário para a introdução da pesquisa.
- `testelapse`: Tempo necessário para concluir o teste.
- `endelapse`: Tempo necessário para o término da pesquisa.
- `IPC`: Classe do Protocolo de Internet.
- `country`: País onde a pesquisa foi realizada.
- `lat_appx_lots_of_err` e `long_appx_lots_of_err`: Latitude e longitude aproximadas.

## Primeiros Passos

Para executar o código deste repositório, você precisará das seguintes bibliotecas Python:

- numpy
- pandas
- matplotlib
- seaborn

Você pode instalar essas bibliotecas usando o pip:

```bash
    pip install numpy pandas matplotlib seaborn
```
## Limpeza de Dados

O código realiza a limpeza e pré-processamento dos dados, incluindo:

- Carregamento do conjunto de dados a partir de `data-final.csv`.
- Remoção de colunas desnecessárias (colunas 50 a 110) para focar nas respostas dos traços de personalidade.
- Limpeza dos dados e formatação das colunas.
- Descrição do conjunto de dados com estatísticas resumidas.

## Análise

O código fornece uma análise básica do conjunto de dados, incluindo:

- Exibição da contagem de respostas para cada valor na coluna `EXT1` como exemplo.
- Identificação e análise de linhas em que todas as respostas dos traços de personalidade são 0.00.

Observe que esta é uma análise básica, e você pode expandi-la para realizar análises mais profundas ou construir modelos preditivos com base nos traços de personalidade.

Sinta-se à vontade para explorar e modificar o código de acordo com suas necessidades específicas de análise e pesquisa.

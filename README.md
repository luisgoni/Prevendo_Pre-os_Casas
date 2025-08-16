# Sistema de Precificação Imobiliária com Machine Learning

Este projeto utiliza regressão linear para prever o valor de imóveis a partir de suas características, como área, distância da praia e distância de farmácia. O objetivo é criar um sistema simples de avaliação imobiliária utilizando técnicas de ciência de dados.

## Estrutura do Projeto

- **Exploração de Dados:** Análise estatística e visualização das variáveis.
- **Transformação dos Dados:** Aplicação de logaritmo para aproximar a distribuição normal.
- **Modelagem:** Regressão linear com `statsmodels` e `scikit-learn`.
- **Avaliação:** Métricas de desempenho e análise dos resíduos.
- **Simulador:** Previsão do preço de imóveis com dados fictícios.

## Como Executar

1. Instale as dependências:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
    ```

2. Execute o notebook `Modelo_Precificacao_imobiliaria.ipynb` no Jupyter Notebook ou VS Code.

3. Altere o arquivo `dataset.csv` para utilizar seus próprios dados.

## Principais Resultados

- O modelo log-linear permite prever o preço dos imóveis com boa precisão.
- As variáveis mais relevantes são área e distância da praia.
- O simulador permite estimar o valor de imóveis com diferentes características.

## Melhorias Futuras

- Testar outros algoritmos de regressão.
- Implementar validação cruzada.
- Criar uma interface web para o simulador.

## Autor

Luis Gustavo 

---

**Observação:** Este projeto é educativo e pode ser adaptado para diferentes bases de dados e cenários imobiliários.
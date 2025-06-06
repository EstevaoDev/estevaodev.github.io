# 📊 Análise de Desempenho das Lojas do Senhor João

## Introdução
Este projeto visa analisar o desempenho de quatro lojas com base em diversos fatores como faturamento, categorias de produtos mais vendidas, avaliações dos clientes, produtos com maior e menor saída e custo médio do frete. A partir dessas análises, buscamos identificar qual loja apresenta menor potencial de lucratividade e pode ser vendida para otimizar os investimentos.

## Objetivos do Projeto
- Calcular o **faturamento total** de cada loja.
- Identificar as **categorias de produtos mais e menos vendidas**.
- Avaliar a **satisfação dos clientes** com base nas avaliações médias.
- Analisar os **produtos mais vendidos e menos vendidos**.
- Examinar o **custo médio de frete** de cada loja.
- Explorar **dados geográficos** para entender padrões de vendas por localização.
- **Gerar visualizações gráficas** para facilitar a interpretação dos dados.

## Tecnologias Utilizadas
- **Python 3.x**
- **Pandas** (Manipulação e análise de dados)
- **Matplotlib & Seaborn** (Visualização de dados)
- **Folium** (Mapeamento interativo)
- **Jupyter Notebook** (Ambiente de execução)

## Instalação e Configuração
Para executar o projeto, siga os passos abaixo:

1. Clone este repositório:
   ```sh
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Instale as dependências:
   ```sh
   pip install pandas matplotlib seaborn folium
   ```
3. Baixe os datasets:
   Os arquivos CSV das lojas estão disponíveis nos seguintes links:
   - Loja 1: [Download](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_1.csv)
   - Loja 2: [Download](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_2.csv)
   - Loja 3: [Download](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_3.csv)
   - Loja 4: [Download](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_4.csv)

4. Execute o script de análise:
   ```sh
   python analise_lojas.py
   ```

## Visualizações Geradas
O projeto gera gráficos para facilitar a análise dos dados. Alguns dos gráficos disponíveis incluem:
- **Gráfico de Barras**: Comparação do faturamento total de cada loja.
- **Gráfico de Pizza**: Distribuição das categorias de produtos mais vendidos.
- **Gráfico de Dispersão**: Correlação entre preço e avaliações dos clientes.
- **Heatmap Geográfico**: Distribuição das vendas por coordenadas de latitude e longitude.

## Análise Geográfica (Opcional)
Caso queira explorar padrões de vendas por localização, utilize o script adicional para gerar mapas interativos. Execute:
```sh
python analise_geografica.py
```

## Conclusão
Com base nas análises realizadas, a loja **Loja 4** apresenta menor faturamento e demanda, indicando menor viabilidade econômica. A recomendação final é que essa loja seja vendida, permitindo otimizar os investimentos nas demais.

## Contribuições
Se desejar contribuir para o projeto, siga os passos:
1. Faça um fork do repositório.
2. Crie uma branch nova (`git checkout -b feature-nova`).
3. Envie um pull request.

## Licença
Este projeto está sob a licença MIT - sinta-se livre para utilizá-lo e modificá-lo conforme necessário.

---
**Desenvolvido para análise e tomada de decisão estratégica.**

# Análise Espacial para o Rolê Perfeito

Organizar um encontro com amigos pode parecer simples, mas encontrar um ponto justo para todos – considerando distâncias e meios de transporte – é um desafio. Este projeto utiliza conceitos de análise de dados e geoprocessamento para calcular o "centro ideal" do rolê de forma justa e eficiente. Um problema cotidiano resolvido com ciência de dados e uma pitada de descontração.

## Objetivo

Determinar o ponto ideal para um encontro em grupo, levando em conta:
- A localização dos participantes.
- A distância ponderada pelo meio de transporte de cada um.
- Uma visualização clara e interativa do resultado.

## Etapas do Projeto

1. **Coleta de Dados**: Construiu-se uma base com informações dos participantes (bairros, coordenadas geográficas e pesos baseados no meio de transporte).

2. **Cálculo do Centro Ideal**: Utilizou-se médias ponderadas para identificar o ponto central mais justo.

3. **Cálculo das Distâncias**: Mediu-se a distância de cada participante ao centro ideal.

4. **Visualização**: 
   - Gráfico de dispersão para análise das localizações.
   - Mapa interativo destacando os pontos de origem e o centro ideal.

## Ferramentas Utilizadas

- **Python**: Linguagem principal do projeto.
- **Pandas**: Manipulação de dados.
- **Geopy**: Cálculo de distâncias geográficas.
- **Matplotlib**: Visualização gráfica.
- **Folium**: Criação de mapas interativos.

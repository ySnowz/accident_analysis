# Análise de Acidentes de Trânsito com Pandas e Seaborn <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Bar%20Chart.png" alt="Bar Chart" width="25" height="25" />

Este é um projeto em Python que utiliza as bibliotecas **Pandas** e **Seaborn** para analisar dados fictícios de acidentes de trânsito. O código demonstra como criar um DataFrame a partir de um conjunto de dados, realizar análises exploratórias e gerar visualizações gráficas para identificar padrões e tendências.

## Funcionalidades <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Sparkles.png" alt="Sparkles" width="25" height="25" />

- **Criação de DataFrame:** Transforma uma lista de dicionários em um DataFrame para análise.
- **Análise Exploratória:** Realiza análises estatísticas e explora os dados para identificar padrões.
- **Visualização de Dados:** Gera gráficos interativos e informativos utilizando **Seaborn** e **Matplotlib**.
  - Acidentes por dia da semana.
  - Gravidade dos acidentes por dia da semana.
  - Acidentes por bairro.
  - Causas dos acidentes.
  - Acidentes por condições climáticas.
  - Relação entre número de veículos e gravidade dos acidentes.
  - Acidentes por faixa de horário.

## Como Funciona <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Gear.png" alt="Gear" width="25" height="25" />

1. **Estrutura dos Dados:**
   - Os dados são armazenados em uma lista de dicionários, contendo informações como data, horário, bairro, causa, gravidade, número de veículos envolvidos, feridos, fatais e condições climáticas.
   - O DataFrame é criado diretamente a partir da lista de dicionários.

2. **Operações Realizadas:**
   - **Análise por Dia da Semana:** Identifica os dias com maior ocorrência de acidentes.
   - **Gravidade dos Acidentes:** Analisa a gravidade dos acidentes em relação ao dia da semana.
   - **Bairros Mais Afetados:** Identifica os bairros com maior número de acidentes.
   - **Causas dos Acidentes:** Mostra as principais causas dos acidentes.
   - **Condições Climáticas:** Analisa a relação entre as condições climáticas e os acidentes.
   - **Relação entre Número de Veículos e Gravidade:** Explora como o número de veículos envolvidos afeta a gravidade dos acidentes.
   - **Acidentes por Faixa de Horário:** Divide os acidentes em faixas de horário para identificar períodos críticos.

3. **Visualização:**
   - Gráficos interativos e informativos são gerados para cada análise, facilitando a interpretação dos dados.

## Por que Este Projeto? <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Thinking%20Face.png" alt="Thinking Face" width="25" height="25" />

Este projeto é ideal para:
- Aprender conceitos avançados de manipulação e análise de dados com a biblioteca Pandas.
- Praticar a criação de visualizações gráficas com Seaborn e Matplotlib.
- Entender como transformar dados brutos em insights valiosos.
- Servir como base para projetos mais complexos, como análise de grandes conjuntos de dados ou integração com outras bibliotecas de machine learning.

## Como Executar <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Symbols/Play%20Button.png" alt="Play Button" width="25" height="25" />

1. Clone o repositório: <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Weary%20Cat.png" alt="Weary Cat" width="25" height="25" />
   ```bash
   git clone https://github.com/seu-usuario/analise-acidentes.git
   ```

2. Navegue até a pasta do projeto:
   ```bash
   cd analise-acidentes
   ```

3. Instale as dependências:
   ```bash
   pip install pandas matplotlib seaborn
   ```

4. Execute o programa:
   ```bash
   python analise_acidentes.py
   ```

## Exemplo de Saída <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Chart%20Increasing.png" alt="Chart Increasing" width="25" height="25" />

Ao executar o código, você verá gráficos como:
- **Acidentes por Dia da Semana:** Um gráfico de barras mostrando a distribuição de acidentes ao longo da semana.
- **Gravidade dos Acidentes:** Um gráfico de barras empilhadas mostrando a gravidade dos acidentes por dia da semana.
- **Bairros com Mais Acidentes:** Um gráfico de barras destacando os bairros mais afetados.
- **Causas dos Acidentes:** Um gráfico de barras horizontais mostrando as principais causas.
- **Acidentes por Condições Climáticas:** Um gráfico de barras mostrando a relação entre condições climáticas e acidentes.
- **Relação entre Número de Veículos e Gravidade:** Um gráfico de caixa (boxplot) mostrando a distribuição do número de veículos por gravidade.
- **Acidentes por Faixa de Horário:** Um gráfico de barras mostrando a distribuição de acidentes por faixa de horário.

## Contribuição <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Handshake.png" alt="Handshake" width="25" height="25" />

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias, correções ou novas funcionalidades.

## Licença <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Symbols/Copyright.png" alt="Copyright" width="25" height="25" />

Este projeto está licenciado sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

### Estrutura do Projeto
```
analise-acidentes/
├── analise_acidentes.py   # Código principal
├── README.md              # Este arquivo
├── LICENSE                # Arquivo de licença
└── requirements.txt       # Dependências do projeto
```

---

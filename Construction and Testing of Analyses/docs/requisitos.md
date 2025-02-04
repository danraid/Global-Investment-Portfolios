## 📌 Engenharia de Requisitos para Construção e Testes das Análises

### 🔹 Visão Geral
O objetivo desta fase do projeto é desenvolver e validar modelos estatísticos e de inteligência artificial para análise e previsão de rentabilidade de ativos financeiros. A abordagem inclui a coleta e tratamento de dados financeiros e geopolíticos, a aplicação de testes estatísticos avançados e a construção de carteiras teóricas de investimento baseadas em diferentes perfis de investidores.

### 🔹 Requisitos Funcionais
| ID  | Requisito | Prioridade |
|----|-------------|------------|
| RF01 | O sistema deve classificar os ativos em categorias (Stocks, ETFs, Bonds, Treasuries, Cryptocurrencies, Moedas). | Alta |
| RF02 | O sistema deve buscar dados financeiros (P/Y, DY, Beta, correlação) em tempo real. | Alta |
| RF03 | O sistema deve coletar e estruturar dados de risco geopolítico. | Média |
| RF04 | O sistema deve permitir análises exploratórias e estatísticas sobre os ativos. | Alta |
| RF05 | O sistema deve construir modelos de Machine Learning para previsão de rentabilidade e risco. | Alta |
| RF06 | O sistema deve montar **três carteiras teóricas diferentes** baseadas no perfil do investidor e em teorias modernas de investimento. | Alta |
| RF07 | O sistema deve seguir regras específicas para a criação das carteiras teóricas. | Alta |
| RF08 | O sistema deve demonstrar claramente a composição da carteira sugerida. | Alta |
| RF09 | A sugestão de investimento deve ser o resultado da predição em Machine Learning. | Alta |
| RF10 | O sistema deve permitir ajuste de parâmetros para personalização das sugestões de investimento. | Média |

### 🔹 Requisitos Não Funcionais
| ID  | Requisito | Prioridade |
|----|-------------|------------|
| RNF01 | O sistema deve atualizar os dados financeiros em tempo real (latência < 2s). | Alta |
| RNF02 | Os modelos de Machine Learning devem ser testados com dados históricos antes da implementação final. | Alta |
| RNF03 | O sistema deve permitir auditoria dos dados geopolíticos antes da tomada de decisão. | Média |
| RNF04 | A interface deve ser intuitiva e responsiva para facilitar a navegação do investidor. | Média |
| RNF05 | O sistema deve ser modular para permitir futuras expansões e atualizações. | Média |

### 🔹 Casos de Uso
1. **Classificação de Ativos**: O usuário acessa o sistema e visualiza os ativos organizados por categorias.
2. **Coleta de Dados Financeiros**: O sistema se conecta às APIs financeiras para buscar dados em tempo real.
3. **Estruturação de Dados Geopolíticos**: Notícias e eventos são transformados em variáveis quantitativas.
4. **Análise Estatística**: O usuário pode visualizar distribuições, histogramas e correlações dos ativos.
5. **Construção de Modelos de Machine Learning**: Algoritmos são treinados para prever rentabilidade e risco.
6. **Sugestão de Carteiras de Investimento**: O sistema gera três carteiras teóricas e apresenta ao investidor.
7. **Validação das Predições**: O usuário pode comparar previsões com dados históricos.

### 🔹 Regras de Negócio
- As carteiras devem ser ajustadas para otimizar retorno e minimizar risco.
- O sistema deve permitir integração com dados externos de risco político.
- A personalização das carteiras deve ser baseada em perfis de investidores predefinidos.
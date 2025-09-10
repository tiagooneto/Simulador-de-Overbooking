# Sistema de Análise de Overbooking
<div align=center>Olá! Eu sou o Tiago Alves. Seja Bem-vindo(a) ao meu repositório! 🖐️ </div>
<br>
Este projeto consiste em um sistema completo de análise de overbooking para companhias aéreas. O sistema calcula probabilidades de overbooking em tempo real, determina limites seguros de venda de passagens e analisa o retorno sobre investimento (ROI) de sistemas de informação. 

#### 
**Link da Atividade**: 

## 📋 Funcionalidades:

- [x] Cálculo em Tempo Real: Probabilidade de overbooking atualizada instantaneamente conforme os parâmetros são ajustados 
- [x] Análise de Risco: Determinação do número máximo de passagens que podem ser vendidas mantendo o risco abaixo de 7%
- [x] Medidor Visual de Risco: Representação gráfica colorida do nível de risco (verde/amarelo/vermelho)
- [x] Cálculo de Estatísticas: 
- Passageiros esperados
- Passageiros barrados (esperado)
- Passageiros embarcados (efetivo)
- Assentos vazios
- [x] Análise de ROI: Cálculo do retorno sobre investimento para sistemas de informação
- [x] Recomendações de Viabilidade: Análise automatizada com recomendações estratégicas

## 🛠️ Tecnologias Utilizadas:
- [x] **Frontend:** HTML5, CSS3, JavaScript
- [x] **Backend**: Flask (Python) para API RESTful
- [x] Cálculos Estatísticos: Implementações personalizadas de distribuição binomial e normal
- [x] Design: Interface responsiva com CSS moderno e gradientes

## 📊 Parâmetros Configuráveis
- [x]  Capacidade da Aeronave: Número de assentos disponíveis (50-400)
- [x] Probabilidade de Comparecimento: Percentual de passageiros que comparecem ao embarque (50-100%)
- [x] Passagens à Venda: Quantidade de passagens vendidas (50-500)


## 📈 Exemplos de Uso
#### Cenário 1: Análise Básica
- Capacidade: 135 assentos
- Probabilidade de Comparecimento: 88%
- Passagens Vendidas: 149
- Resultado: 13,27% de chance de overbooking

#### Cenário 2: Limite Seguro
- Capacidade: 120 assentos
- Probabilidade de Comparecimento: 88%
- Limite Seguro: 125 passagens (0.05% de risco)

#### Cenário 3: ROI do Sistema
- Investimento Inicial: R$ 50.000,00
- Receita Adicional: R$ 80.000,00
- Custo Operacional Anual: R$ 10.000,00
- ROI: 140%

## 🧮 Metodologia de Cálculo

#### Probabilidade de Overbooking
##### Utiliza distribuição binomial para calcular P(X > capacidade), onde:
- X ~ Binomial(n, p)
- n = número de passagens vendidas
- p = probabilidade de comparecimento

#### Estatísticas de Passageiros
##### Aproximação normal para estimar:
- Passageiros esperados: n × p
- Passageiros barrados: E[max(0, X - capacidade)]
- Passageiros embarcados: min(X, capacidade) - passageiros barrados
- Assentos vazios: capacidade - passageiros embarcados

#### ROI do Sistema
##### Fórmula padrão de retorno sobre investimento:
- ROI = [(Receita Adicional - Custos Operacionais) / Investimento Inicial] × 100%
## 📋 Resultados e Recomendações
##### O sistema fornece análises completas incluindo:
- Probabilidade de overbooking em percentual
- Número máximo recomendado de passagens
- Estatísticas detalhadas de ocupação
- Análise de viabilidade com recomendações
- Cálculo de ROI para sistemas de informação

## 🎯 Aplicações Práticas
- Gestão de Capacidade: Determinar limites seguros de venda de passagens
- Análise de Risco: Avaliar probabilidades de overbooking em diferentes cenários
- Tomada de Decisão: Base para decisões estratégicas sobre políticas de venda
- Investimento em TI: Avaliação de retorno sobre investimento em sistemas de informação

## 📝 Personalização
##### O sistema pode ser facilmente personalizado para:
- Diferentes limites de risco (além do padrão de 7%)
- Outras métricas de desempenho
- Integração com sistemas existentes
- Visualizações adicionais e relatórios

## 🔍 Insights Obtidos
- Pequenos aumentos na venda de passagens podem elevar significativamente o risco de overbooking
- Sistemas de informação adequados podem proporcionar ROI substancial
- A probabilidade de comparecimento é o fator mais crítico para o cálculo de risco


## Tecnologias Usadas
<div style="display: inline_block" align = center>
  <a href="https://html.com/" target="_blank">
    <img align="center" alt="html5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  </a>
  <a href="https://www.w3.org/Style/CSS/Overview.en.html" target="_blank">
    <img align="center" alt="css" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  </a>
  <a href="https://developer.mozilla.org/pt-BR/docs/Web/JavaScript" target="_blank">
    <img align="center" alt="js" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  </a> </div> <br>
  
  <div align = center>
  O site foi desenvolvido utilizando as tecnologias HTML, CSS e JavaScript, garantindo uma experiência interativa e responsiva para os usuários em diferentes dispositivos.</div><br>
  
  Acesse aqui: https://tiagooneto.github.io/Overbooking/
  

  <div align = center>
  Este sistema foi desenvolvido para fins educacionais e de análise. Recomenda-se validação adicional para uso em ambientes de produção.</div><br>

  
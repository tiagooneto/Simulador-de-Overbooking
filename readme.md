

<div align="center">
  <h1> Sistema de Análise de Overbooking e ROI</h1>
</div>
<div align="center">
  <img src="./assets/logo_UNB.png" alt="Logo UNB" width="200">
  <h3>Tiago Alves dos Santos Neto - 202014762</h3>
  <p>SISTEMAS DE INFORMAÇÃO EM ENGENHARIA DE PRODUÇÃO</p>
</div>

## 📋 Visão Geral

Sistema completo de análise de overbooking para companhias aéreas que calcula probabilidades em tempo real, determina limites seguros de venda de passagens e analisa o retorno sobre investimento (ROI) de sistemas de informação.

**🔗 Link da Aplicação**: https://tiagooneto.github.io/Simulador-de-Overbooking/

## ✨ Funcionalidades Principais

- **Cálculo em Tempo Real**: Probabilidade de overbooking atualizada instantaneamente
- **Análise de Risco**: Determinação do número máximo de passagens com risco controlado (≤7%)
- **Visualização Interativa**: Gráficos dinâmicos e medidor visual de risco
- **Estatísticas Detalhadas**:
  - Passageiros esperados e embarcados
  - Passageiros barrados (expectativa)
  - Assentos vazios (previsão)
- **Análise de ROI**: Cálculo do retorno sobre investimento para sistemas de informação
- **Recomendações Estratégicas**: Análise de viabilidade com orientações personalizadas

## 🎮 Como Utilizar

1. Ajuste os parâmetros usando os controles deslizantes:
   - **Capacidade da Aeronave**: Número de assentos (50-400)
   - **Probabilidade de Comparecimento**: Percentual de passageiros (50-100%)
   - **Passagens à Venda**: Quantidade de passagens (50-500)

2. Observe os resultados atualizados em tempo real:
   - Probabilidade de overbooking
   - Limite seguro de vendas
   - Estatísticas de ocupação
   - Recomendações de viabilidade

3. Analise o ROI do sistema de informação na seção dedicada



## 📊 Metodologia de Cálculo

### Probabilidade de Overbooking
Utiliza distribuição binomial para calcular P(X > capacidade), onde:
- X ~ Binomial(n, p)
- n = número de passagens vendidas
- p = probabilidade de comparecimento

### Estatísticas de Passageiros
Aproximação normal para estimar:
- Passageiros esperados: n × p
- Passageiros barrados: E[max(0, X - capacidade)]
- Passageiros embarcados: min(X, capacidade) - passageiros barrados
- Assentos vazios: capacidade - passageiros embarcados

### ROI do Sistema
Fórmula padrão de retorno sobre investimento:
- ROI = [(Receita Adicional - Custos Operacionais) / Investimento Inicial] × 100%

## 📈 Exemplos de Cenários

### Cenário 1: Análise Básica
- Capacidade: 135 assentos
- Probabilidade de Comparecimento: 88%
- Passagens Vendidas: 149
- **Resultado**: 13,27% de chance de overbooking

### Cenário 2: Limite Seguro
- Capacidade: 120 assentos
- Probabilidade de Comparecimento: 88%
- **Limite Seguro**: 125 passagens (0.05% de risco)

### Cenário 3: ROI do Sistema
- Investimento Inicial: R$ 50.000,00
- Receita Adicional: R$ 80.000,00
- Custo Operacional Anual: R$ 10.000,00
- **ROI**: 140%

## 🎯 Aplicações Práticas

- **Gestão de Capacidade**: Determinar limites seguros de venda
- **Análise de Risco**: Avaliar probabilidades em diferentes cenários
- **Tomada de Decisão**: Base para políticas comerciais estratégicas
- **Investimento em TI**: Avaliação de retorno em sistemas de informação

## 🔍 Insights Obtidos

- Pequenos aumentos na venda elevam significativamente o risco de overbooking
- Sistemas de informação adequados proporcionam ROI substancial
- A probabilidade de comparecimento é o fator mais crítico para cálculo de risco

## 📝 Personalização

O sistema pode ser adaptado para:
- Diferentes limites de risco (além do padrão de 7%)
- Outras métricas de desempenho específicas
- Integração com sistemas existentes
- Visualizações adicionais e relatórios personalizados

## 🛠️ Tecnologias Utilizadas

<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chart.js&logoColor=white" alt="Chart.js">
</div>

## 🌐 Acesso

**Link de Produção**: https://tiagooneto.github.io/Simulador-de-Overbooking/

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais e de análise. Recomenda-se validação adicional para uso em ambientes de produção.

---

<div align="center">
  Desenvolvido por <strong>Tiago Alves dos Santos Neto</strong> | 202014762
  <br>
  Universidade de Brasília - Engenharia de Produção
</div>
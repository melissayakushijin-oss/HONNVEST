# HONNVEST

Simulador de investimentos em Fundos Imobiliários (FIIs) desenvolvido no Excel.

## Como usar

1. Baixe o arquivo **HONNVEST.xlsx**.
2. No quadro **Configurações**, informe:
   - **Salário** (a planilha sugere investir 30% dele)
   - **Rendimento da carteira**
3. No quadro **Investimento Mensal**, preencha:
   - **Quanto se quer investir por mês**
   - **Por quantos anos**
   - **Taxa de rendimento mensal**
4. A planilha calcula automaticamente:
   - a **sugestão de investimento**;
   - o **patrimônio acumulado**;
   - os **dividendos mensais**.

## Funcionalidades

- **Cenários pré-definidos** de 2, 5, 10, 20, 30 e 50 anos investindo, com o patrimônio acumulado e os dividendos de cada período.
- **Sugestão de alocação em 6 tipos de FII** de acordo com o perfil do investidor: **Conservador**, **Moderado** ou **Agressivo**.
- **Gráfico da porcentagem investida** por perfil.
- **Gráfico da evolução do patrimônio** acumulado ao longo dos anos.

## Fórmulas principais

- **PROCV**: busca na planilha de apoio as porcentagens de investimento de acordo com o perfil do investidor e o tipo de FII.
- **VF (Valor Futuro)**: calcula o patrimônio acumulado a partir da taxa, do valor investido por mês e do tempo informados pelo usuário.

## Intervalos nomeados

| Nome | O que representa |
|------|------------------|
| `salario` | Salário informado pelo usuário |
| `rendimento_carteira` | Rendimento mensal da carteira, usado no cálculo dos dividendos |
| `sugestao_invest` | Sugestão de investimento mensal (30% do salário) |
| `aporte` | Valor que se quer investir por mês |
| `qtd_anos` | Quantidade de anos investindo |
| `taxa_mensal` | Taxa de rendimento mensal do investimento |
| `patrimonio` | Patrimônio acumulado ao final do período (calculado com VF) |
| `dividendos` | Dividendos mensais gerados pelo patrimônio acumulado |

## Alterações em relação à planilha original do Expert

- Banner autoral
- Nova paleta de cores
- Cenário de 50 anos investidos
- Porcentagem sugerida de investimento em cada FII de acordo com o perfil do investidor
- Formatação
- Gráfico ilustrando a evolução do patrimônio acumulado

## Aviso

Os percentuais de cada perfil são uma sugestão baseada nos riscos que cada tipo de investimento oferece. Esta ferramenta tem fins educacionais e não constitui recomendação de investimento.

## Autoria

Melissa Rojas Yakushijin – 2026

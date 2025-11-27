#  Simulador do Sistema Solar Avançado

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5%2B-orange.svg)](https://matplotlib.org/)
[![Numba](https://img.shields.io/badge/Numba-0.55%2B-red.svg)](https://numba.pydata.org/)

Um simulador gravitacional N-body completo e interativo que permite criar e visualizar sistemas planetários personalizados com física realista.

![Simulação Demo](https://via.placeholder.com/800x400/2c3e50/ffffff?text=Simulador+Sistema+Solar)

##  Características Principais

###  Física Avançada
- **Simulação gravitacional N-body** com constante gravitacional real
- **Integração Velocity Verlet** para maior precisão numérica
- **Cálculo de energia** (cinética e potencial) com verificação de conservação
- **Detecção de colisões** entre corpos celestes
- **Sistema de unidades flexível** com suporte a notação científica

###  Interface Interativa
- **Controles em tempo real**: velocidade, passo de tempo, escala
- **Entrada completa de parâmetros**: massa, posição, velocidade, raio
- **Visualização dinâmica** com trilhas orbitais coloridas
- **Escala automática** ou manual conforme preferência
- **Exportação de dados** para análise posterior

###  Performance Otimizada
- **Aceleração com Numba JIT** para cálculos gravitacionais
- **Histórico gerenciável** para evitar vazamento de memória
- **Renderização eficiente** de múltiplos corpos e trilhas

##  Instalação

### Pré-requisitos
- Python 3.8 ou superior
- pip (gerenciador de pacotes Python)

### Dependências
```bash
# Instalar dependências necessárias
pip install numpy matplotlib numba

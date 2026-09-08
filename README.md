# ⚡ Calculadora de Consumo de Energia

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![GitHub](https://img.shields.io/badge/GitHub-Projeto-black?logo=github)
![Status](https://img.shields.io/badge/Status-Concluído-success)
![Energia](https://img.shields.io/badge/⚡-Energia-yellow)

## 📌 Sobre o projeto

Este projeto foi desenvolvido como atividade da disciplina de **Desenvolvimento de Sistemas I**.

O objetivo do sistema é calcular o consumo mensal estimado de energia elétrica de um aparelho, considerando sua potência em watts e o tempo médio de utilização por dia.

Além do consumo de energia, o programa também apresenta uma estimativa do custo mensal, considerando o valor de **R$ 0,75 por kWh**.

## 🐍 Tecnologia utilizada

- Python

## 🧮 Fórmula utilizada

O consumo mensal é calculado utilizando a seguinte fórmula:

```text
consumoMensal = (potencia × horasDia × 30) / 1000
```

Onde:

- **potencia** = potência do aparelho em watts (W)
- **horasDia** = tempo médio de uso diário em horas
- **30** = quantidade aproximada de dias do mês
- **1000** = conversão de Wh para kWh

## 💻 Como executar

1. Tenha o Python instalado no computador.
2. Baixe ou clone este repositório.
3. Abra a pasta do projeto no VS Code.
4. Abra o terminal.
5. Execute:

```bash
python app.py
```

6. Informe os dados solicitados pelo programa.

## 📊 Exemplo de execução

```text
=== Calculadora de Consumo de Energia ===

Digite o nome do aparelho: Geladeira
Digite a potência do aparelho em watts (W): 100
Digite o tempo médio de uso diário em horas: 15

=== Resultado ===
Aparelho: Geladeira
Consumo estimado: 45.00 kWh/mês
Custo estimado: R$ 33.75 por mês
```

## 👩‍💻 Autora

**Laíne Moraes**

Desenvolvido como atividade acadêmica de Desenvolvimento de Sistemas I.
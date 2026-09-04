# Documentação das Fórmulas

Este documento apresenta a lógica das principais fórmulas utilizadas na ferramenta de controle de investimentos.

---

# 1. Nomes definidos

A planilha utiliza os seguintes nomes definidos:

| Nome | Referência |
|---|---|
| `salario` | `Folha1!$D$7` |
| `redimento_carteira` | `Folha1!$D$8` |
| `sugestao_investimento` | `Folha1!$D$9` |
| `aporte` | `Folha1!$D$12` |
| `qtd_anos` | `Folha1!$D$13` |
| `taxa_mensal` | `Folha1!$D$14` |
| `patrimonio` | `Folha1!$D$15` |

> **Observação:** o nome `redimento_carteira` possui atualmente a grafia "redimento", sem o segundo "n". A grafia é mantida para preservar a compatibilidade com as fórmulas existentes.

---

# 2. Sugestão de investimento

A sugestão de investimento é calculada aplicando 30% sobre o salário informado.

### Fórmula

```excel
=salario*30%
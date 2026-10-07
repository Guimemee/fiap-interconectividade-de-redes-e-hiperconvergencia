# Origem e Justificativa do Problema

**Disciplina:** Interconectividade de Redes e Hiperconvergência
**Ano Letivo:** 2024 | **Turma:** 3ECR
**Avaliação:** Checkpoint 1

### Enunciado do Problema
Dimensionar o esquema de endereçamento IPv4 com Máscara de Tamanho Variável (VLSM) para segmentar a rede corporativa e a rede de telemetria da Sanofi minimizando o desperdício de IPs.

### Formulação Formal
$$\text{Hosts Necessários} \le 2^{32 - \text{prefixo}} - 2, \quad \text{Ex: } /27 \implies 2^5 - 2 = 30 \text{ hosts}$$

# DIAGRAMA 1 — Macroprocesso (Level 0)

## Evento Inicial

Iniciar Processo de Debulha

## Tarefas principais

- Inserir Caixas no Debulhador
- Realizar Debulha Mecânica
- Executar Correção Manual
- Classificar Dentes de Alho
- Realizar Seleção Final
- Avaliar Qualidade do Produto
- Encerrar Processo de Debulha
Evento Final
- Produto Classificado e Avaliado

# DIAGRAMA 2 — Processo Operacional Detalhado (Level 1)

## Ponto 1 — Entrada no Debulhador

- Receber Caixas de Alho
- Inserir Caixas na Esteira de Entrada
- Registrar Quantidade de Caixas Inseridas

## Ponto 2 — Pós-Debulha Mecânica

- Receber Dentes Debulhados
- Remover Palha e Resíduos
- Separar Dentes Defeituosos
- Coletar Amostra de Qualidade
- Registrar Defeitos Identificados

## Ponto 3 — Saída para Classificação

- Acondicionar Dentes em Caixas
- Registrar Quantidade de Caixas Produzidas
- Coletar Amostra de Desempenho
- Registrar Indicadores de Qualidade Parcial

## Ponto 4 — Entrada no Classificador

- Inserir Caixas no Classificador
- Registrar Quantidade de Caixas no Classificador

## Ponto 5 — Esteiras de Classificação

- Distribuir Dentes por Tamanho
- Selecionar Dentes por Padrão de Qualidade
- Realizar Desfilipação Manual
- Descartar Dentes Fora do Padrão

## Ponto 6 — Saída Final

- Acondicionar Dentes Classificados em Caixas
- Registrar Quantidade de Caixas Finais
- Coletar Amostra Final de Qualidade
- Registrar Avaliação Final

# DIAGRAMA 3 — Subprocesso de Avaliação da Qualidade (Level 2)

Evento Inicial
- Iniciar Avaliação de Qualidade

Tarefas
- Selecionar Amostra Representativa
- Inspecionar Dentes da Amostra
- Identificar Tipos de Defeitos
- Registrar Quantidade de Defeitos
- Calcular Percentual de Qualidade
- Validar Resultado da Avaliação
- Enviar Dados para o Sistema Central

Evento Final
- Avaliação de Qualidade Concluída

# DIAGRAMA 4 — Regras de Negócio (Gateways)

Gateway Exclusivo (XOR)
- Definir Modelo Avaliativo Aplicável

Caminho Modelo A
- Aplicar Avaliação Informativa
- Registrar Resultado sem Impacto Financeiro

Caminho Modelo B
- Aplicar Avaliação com Impacto na Diária
- Determinar Faixa de Qualidade
- Ajustar Valor da Diária

Caminho Modelo C
- Aplicar Avaliação com Bonificação
- Calcular Percentual de Bonificação
- Registrar Bonificação do Colaborador

# DIAGRAMA 5 — Integração Sistêmica

Sistema Mobile
- Registrar Apontamento de Produção
- Registrar Avaliação de Qualidade
- Transmitir Dados ao Sistema Central
Sistema de Gestão 
- Receber Dados de Apontamento
- Consolidar Avaliações
- Executar Fechamento do Processo
- Gerar Provisão de Proventos
BI
- Atualizar Indicadores de Qualidade
- Disponibilizar Painel Gerencial
# 📊 Análise de Riscos e Causa Raiz em Supply Chain Global (2026)

3📌 Contexto de Negócio
A eficiência de uma cadeia de suprimentos global é frequentemente ameaçada por variáveis externas. Na operação analisada, observou-se um índice alarmante de incidentes, levantando a dúvida: O problema é geográfico, físico (carga) ou de gestão de parceiros?

Este projeto audita 5.000 registros logísticos de 2026 para identificar onde a receita está sendo drenada por falhas operacionais e atrasos sistêmicos.

3🎯 Objetivo
Comprovar se os atrasos e incidentes estão ligados a fatores imutáveis (distância/peso) ou se existe um risco de governança na seleção de transportadoras e gestão de portos específicos.

3🛠️ Como a Análise foi Construída (Passo a Passo)
Preparação e Tradução: Limpeza dos dados de 5.000 registros globais. Para facilitar a leitura e análise, renomeei todas as colunas para o português e padronizei os textos, garantindo uma base de dados limpa e organizada.

Mapeamento de Incidentes: Realizei a contagem exata de quantos fretes tiveram problemas logísticos versus os que ocorreram com sucesso, estabelecendo o cenário real da operação.

Filtro de Gargalos: Criei uma base específica apenas com os casos de erro (Problema Logístico = 1) para mapear quais pontos de origem e de chegada concentram as maiores falhas e quais são as rotas mais críticas.

Análise Comparativa (O Diferencial): Filtrei a base original apenas pelos casos de sucesso (sem problemas) para entender o que dá certo. Comparei médias de quilometragem e peso para descobrir, por exemplo, como rotas extremamente longas conseguem operar sem incidentes enquanto rotas curtas falham.

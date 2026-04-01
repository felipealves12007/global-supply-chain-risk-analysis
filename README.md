# 📊 Análise de Riscos e Causa Raiz em Supply Chain Global (2026)

# 📌 Contexto de Negócio
A eficiência de uma cadeia de suprimentos global é frequentemente ameaçada por variáveis externas. Na operação analisada, observou-se um índice alarmante de incidentes, levantando a dúvida: O problema é geográfico, físico (carga) ou de gestão de parceiros?

Este projeto audita 5.000 registros logísticos de 2026 para identificar onde a receita está sendo drenada por falhas operacionais e atrasos sistêmicos.

# 🎯 Objetivo
Comprovar se os atrasos e incidentes estão ligados a fatores imutáveis (distância/peso) ou se existe um risco de governança na seleção de transportadoras e gestão de portos específicos.

# 🛠️ Como a Análise foi Construída (Passo a Passo)
Preparação e Tradução: Limpeza dos dados de 5.000 registros globais. Para facilitar a leitura e análise, renomeei todas as colunas para o português e padronizei os textos, garantindo uma base de dados limpa e organizada.

Mapeamento de Incidentes: Realizei a contagem exata de quantos fretes tiveram problemas logísticos versus os que ocorreram com sucesso, estabelecendo o cenário real da operação.

Filtro de Gargalos: Criei uma base específica apenas com os casos de erro (Problema Logístico = 1) para mapear quais pontos de origem e de chegada concentram as maiores falhas e quais são as rotas mais críticas.

Análise Comparativa (O Diferencial): Criei uma base específica apenas casos de sucesso (Problema Logístico = 0) para entender o que dá certo. Comparei as métricas, por exemplo, como rotas extremamente longas conseguem operar sem incidentes enquanto rotas curtas falham.

# 💡 Insights e Diagnóstico de Risco 
🚨 Alerta de Falha Sistêmica: A análise permitiu isolar os pontos de origem e as rotas que mais geram prejuízos, direcionando onde deve intervir primeiro.

🌍 Gargalos Geográficos: Os pontos de Busan e Shanghai concentram os maiores gargalos operacionais. A análise revelou que essa rota apresentam pontuação de risco geopolítico de média a alta, o que exige planos de contingência específicos para garantir a fluidez dessas rotas.

🚚 O Mito da Distância: A análise comprovou que o peso da remessa e a distância percorrida possuem baixa correlação com os atrasos.

🔍 O Fator Humano/Gestão: O verdadeiro "vilão" identificado foi a Confiabilidade da Transportadora. transportadoras com índices de performance abaixo de 0.80 apresentam chances significativamente maiores de gerar problemas logísticos, independente do trajeto.

📦 Vulnerabilidade por Categoria: As falhas não se concentram em um único tipo de categoria, mas se distribuem de forma equilibrada entre todas as categorias. Isso indica um risco sistêmico, onde a fragilidade não está no produto em si, mas na estrutura logística que atende toda a operação.

# 💻 Tecnologias e Ferramentas
Linguagem: Python
Manipulação de Dados: Pandas
Visualização de Dados: Matplotlib

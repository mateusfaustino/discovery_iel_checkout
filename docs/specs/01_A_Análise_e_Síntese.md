Narrativa Executiva — Product Discovery: Abandono de Carrinho no E-commerce
1. Dor crítica e impacto para o negócio
Dor crítica
O principal problema identificado não é simplesmente “o usuário abandona o carrinho”. O ponto crítico está na quebra entre a intenção de compra e a conclusão da transação.
A jornada mostra que o usuário:
- encontra um produto adequado;
- demonstra intenção concreta ao adicioná-lo ao carrinho;
- avança para cadastro/checkout;
- encontra incertezas sobre frete, prazo e custo total;
- e, em parte dos casos, não conclui a compra.
A evidência mais consistente do Discovery está na baixa transparência antecipada do frete: o usuário não consegue consultar facilmente custo e prazo antes de avançar na jornada. A hipótese de que o frete efetivamente causa o abandono, porém, está apenas parcialmente validada.     relatorio
Impacto para o negócio
Intenção de compra sem conversão = receita potencial perdida.
O negócio já investiu para levar o usuário pelas etapas de descoberta, avaliação e decisão. Quando ele abandona próximo à conversão, parte desse investimento não se transforma em receita.
Além da perda direta de conversão, existem riscos de:
- menor eficiência do funil;
- desperdício do investimento em aquisição;
- perda de competitividade frente a lojas que apresentam condições comerciais mais cedo;
- dificuldade de recuperar usuários que já demonstraram intenção de compra.
Leitura executiva: o problema não é gerar interesse. É transformar interesse já existente em compra concluída.

2. Única grande aposta para o MVP
Método de priorização: ICE
Para decisão executiva, aplicamos ICE — Impact, Confidence e Ease, com escala de 1 a 5.
Oportunidade	Impacto	Confiança	Facilidade	ICE
Transparência antecipada do frete	5	4	4	80
Reduzir fricções no checkout	5	2	3	30
Condições comerciais mais competitivas	4	2	3	24
Melhorar comparação de produtos	3	3	3	27
Salvar para depois	2	2	4	16
Transparência do custo total	4	3	3	36
Recuperação/continuidade da compra	4	2	3	24


Fórmula utilizada: Impacto × Confiança × Facilidade.
As pontuações são uma priorização executiva derivada das evidências do relatório, não resultados quantitativos produzidos pela pesquisa. O próprio Discovery ressalta que as oportunidades ainda precisam ser confrontadas com entrevistas e testes antes de entrarem definitivamente no roadmap.     relatorio
Aposta do MVP
Dar visibilidade de frete e prazo antes do carrinho.

Essa é a melhor hipótese para testar primeiro porque combina:
alto impacto potencial + maior evidência disponível + escopo relativamente controlado.
Não estamos assumindo que o frete é definitivamente a causa do abandono. Estamos escolhendo justamente a oportunidade com melhor relação entre evidência, impacto potencial e custo de aprendizado.
3. Solução proposta e vantagem sobre o status quo
MVP proposto
Implementar na página do produto, antes da inclusão no carrinho:
- consulta de frete por CEP;
- estimativa de prazo de entrega;
- indicação clara do valor do frete;
- sinalização de condições de frete grátis, quando aplicáveis.
O objetivo é responder antecipadamente a uma pergunta essencial:
“Quanto realmente vai custar e quando vou receber?”

Status quo
Hoje, informações relevantes aparecem tarde na jornada. Isso obriga o usuário a avançar no funil para descobrir condições que podem ser determinantes para sua decisão. Essa fricção aparece explicitamente na jornada consolidada e nas oportunidades levantadas pelo Discovery.     relatorio
Por que o MVP é melhor
Hoje:
Produto → Carrinho → Cadastro/Checkout → Descobre frete/prazo → Decide
MVP:
Produto → Descobre frete/prazo → Decide → Carrinho → Checkout
O ganho não está apenas em tentar aumentar conversão. Está em antecipar informação relevante para o momento em que a decisão está sendo formada.
Isso permite testar uma hipótese importante sem redesenhar todo o checkout ou recorrer imediatamente a descontos que reduzam margem.
4. Riscos e métricas de sucesso
Principais riscos
Risco de valor — ALTO
Frete pode ser apenas um sintoma. Mesmo tornando a informação transparente, o abandono pode continuar porque preço, cadastro, pagamento ou intenção de compra são fatores mais relevantes.
Risco de negócio — MÉDIO
A transparência pode revelar antecipadamente fretes pouco competitivos e deslocar o abandono para uma etapa anterior, sem melhorar a conversão final.
Risco técnico — MÉDIO
Integrações com transportadoras podem produzir valores ou prazos inconsistentes, prejudicando confiança e experiência.
Risco de interpretação — ALTO
A principal limitação do Discovery atual é que a jornada foi construída a partir de proto-persona e premissas. O próprio relatório alerta que ela não constitui validação definitiva das hipóteses.     relatorio
KPIs
North Star do experimento:
Taxa de conversão em compra dos usuários que chegam à página de produto.

KPIs de suporte:
- taxa Produto → Adicionar ao carrinho;
- taxa Carrinho → Checkout;
- taxa Checkout → Compra;
- taxa de abandono do carrinho;
- percentual de usuários que consultam frete antes de adicionar ao carrinho;
- diferença de conversão entre usuários expostos e não expostos ao novo componente;
- receita por sessão;
- ticket médio, como métrica de proteção.
Critério executivo de sucesso
O MVP deve ser considerado promissor se houver aumento estatisticamente relevante na conversão final sem deterioração relevante de receita por sessão ou ticket médio.
A métrica principal deve ser compra concluída, e não simplesmente uso do simulador de frete.
Síntese para o Board
Problema: temos usuários com intenção de compra que chegam ao carrinho, mas não concluem a transação. O Discovery aponta incerteza sobre frete, prazo e custo total como uma das fricções mais evidentes, embora sua causalidade sobre o abandono ainda precise ser validada.
Aposta: antecipar frete e prazo para a página do produto.
Por quê: é a oportunidade com melhor combinação entre impacto potencial, evidência disponível e esforço de implementação, além de permitir aprendizado sem uma transformação ampla do checkout.
Investimento inicial: MVP pequeno e mensurável, em vez de uma reformulação completa do funil.
Retorno esperado: redução da incerteza na decisão e aumento da conversão de usuários que já demonstram intenção de compra.
Decisão baseada em dados: testar contra o fluxo atual e escalar apenas se houver impacto comprovado na conversão final e nos indicadores financeiros.
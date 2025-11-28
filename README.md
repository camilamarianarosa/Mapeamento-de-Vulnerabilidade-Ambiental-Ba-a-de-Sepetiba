Este projeto apresenta um diagnóstico espacial da vulnerabilidade de manguezais e restingas na Baía de Sepetiba (RJ), integrando camadas ambientais e análise espacial no QGIS.
O objetivo é identificar áreas sensíveis sob influência de fontes industriais e zoneamentos de impacto por meio de buffers de 500 m, 1000 m e 2000 m.

1. Camadas utilizadas:

- Uso e cobertura da terra — MapBiomas
- Drenagem e massa d’água — IBGE
- Limite municipal
- Fontes industriais e pontos de pressão
- Áreas sensíveis (manguezal/restinga)

2. Metodologia

2.1.  Padronização de dados (EPSG: 31983 – SIRGAS 2000 / UTM Zone 23S)
2.2. Criação de buffers de impacto
Foram criados buffers radiais a partir dos pontos de pressão industrial:
| Impacto | Distância | Interpretação |
|---------|-----------|---------------|
| 🔴 Alto | 500 m | Influência direta |
| 🟠 Médio | 1000 m | Influência intermediária |
| 🟡 Baixo | 2000 m | Influência difusa |

2.3 Cálculo das Áreas
| Zona de Impacto | Distância (m) | Área (m²)       | Área (ha)     |
|----------------|---------------|------------------|---------------|
| **Alta**       | 500           | 20.433.322       | 2.043,33 ha   |
| **Média**      | 1000          | 75.544.863       | 7.554,48 ha   |
| **Baixa**      | 2000          | 264.798.240      | 26.479,82 ha  |

2.4 Interseção com áreas sensíveis para classificação do nível de vulnerabilidade
- Cruzamento espacial entre buffers e manguezais/restingas
- Quantificação da área sensível dentro de cada nível de impacto
- Classificação final da vulnerabilidade ambiental
2.5 Construção do layout cartográfico e simbologia temática
-  Símbolos temáticos para cada nível de vulnerabilidade
- Legenda estruturada, escala, seta norte e refinamento visual
- Exportação do layout final em PNG
3. Resultado Final
O projeto produziu um mapa temático que identifica três níveis de vulnerabilidade ambiental a partir da influência industrial sobre áreas sensíveis:

🔴 Alta Vulnerabilidade (500 m)
- Impacto direto sobre ecossistemas sensíveis
- Maior necessidade de mitigação e monitoramento
🟠 Média Vulnerabilidade (1000 m)
- Influência indireta relevante
- Potencial de impacto cumulativo
🟡 Baixa Vulnerabilidade / Influência Ampliada (2000 m)
- Zona de difusão de efeitos ambientais
- Importante para planejamento territorial e prevenção

4. Ferramentas e técnicas:
QGIS 3.40.5
- Modelagem espacial vetorial
- Analise Buffer 
  Interseção
- Organização cartográfica e layout final
Autora: Camila Mariana Neri Rosa - Oceanografia/UERJ

Resultado
Mapa final indicando três níveis de vulnerabilidade ambiental (alto, médio, alto ampliado), destacando áreas sensíveis sob maior pressão industrial.

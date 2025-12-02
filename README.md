A análise utiliza buffers radiais de 500 m, 1000 m e 2000 m para identificar zonas de impacto e quantificar áreas sensíveis.

1. Camadas utilizadas:

- Uso e cobertura da terra — MapBiomas
- Drenagem e massa d’água — IBGE
- Limite municipal
- Fontes industriais e pontos de pressão
- Áreas sensíveis (manguezal/restinga)

2. Metodologia

2.1.  Padronização de dados (EPSG: 31983 – SIRGAS 2000 / UTM Zone 23S)
2.2. Criação de buffers de impacto
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

2.4 Interseção com áreas sensíveis
- Cruzamento espacial entre buffers e manguezais/restingas
- Quantificação da área sensível dentro de cada nível de impacto
- Classificação final da vulnerabilidade ambiental
  
2.5 Construção do layout cartográfico e simbologia temática
-  Símbolos temáticos para cada nível de vulnerabilidade
- Legenda estruturada, escala, seta norte e refinamento visual
- Exportação do layout final em PNG

3. Mapa Final

![Mapeamento de Vulnerabilidade Ambiental em Áreas Sensíveis – Baía de Sepetiba_page-0001](https://github.com/user-attachments/assets/084c22bf-b55f-4333-bfdf-2b7652a1d50f)Este projeto realiza um diagnóstico espacial da vulnerabilidade de manguezais e restingas na Baía de Sepetiba a partir da influência de fontes industriais.


4. Resultado Final
O mapa final identifica três zonas de vulnerabilidade:

🔴 Alta (500 m): impacto direto sobre ecossistemas sensíveis

🟠 Média (1000 m): influência intermediária e potencial efeito cumulativo

🟡 Baixa (2000 m): difusão de impacto e área de planejamento preventivo

A análise permite avaliar riscos ambientais e priorizar ações de mitigação.

5. Ferramentas e técnicas:
- QGIS 3.40.5
- Modelagem espacial vetorial
- Analise Buffer 
  Interseção
- Organização cartográfica e layout final
 
Autora: Camila Mariana Neri Rosa - Oceanografia/UERJ


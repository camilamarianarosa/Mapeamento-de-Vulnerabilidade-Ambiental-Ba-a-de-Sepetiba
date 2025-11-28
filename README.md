Este projeto realiza um diagnóstico espacial da vulnerabilidade de manguezais e restingas na Baía de Sepetiba (RJ) a partir da integração de camadas ambientais e territoriais no QGIS.

Camadas utilizadas:

- Uso e cobertura da terra — MapBiomas
- Drenagem e massa d’água — IBGE
- Limite municipal
- Fontes industriais e pontos de pressão
- Áreas sensíveis (manguezal/restinga)

Metodologia
- Padronização de dados (EPSG: 31983 – SIRGAS 2000 / UTM Zone 23S)
- Criação de buffers de impacto: 500 m, 1.000 m e 2.000 m
- Interseção com áreas sensíveis para classificação do nível de vulnerabilidade
-Construção do layout cartográfico e simbologia temática

Ferramentas e técnicas:

QGIS 3.40.5
- Modelagem espacial vetorial
- Buffer analysis
- Overlay (intersect)
- Organização cartográfica e layout final

Resultado
Mapa final indicando três níveis de vulnerabilidade ambiental (alto, médio, alto ampliado), destacando áreas sensíveis sob maior pressão industrial.

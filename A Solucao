# Tracking Temporal de Perfis: estabilidade e transições mensais

📈 Case 3 

Hoje abro a caixa‑preta de como monitoro perfis comportamentais ao longo do tempo (janelas mensais), medindo estabilidade, transições e entropia — tudo escalável em Spark + Python.

Por que isso importa?

Enxerga migrações de clientes entre perfis (ex.: “Preço‑sensível” → “Premium”)

Identifica risco (alta entropia, muita oscilação) e oportunidade (estabilidade em perfis de alto valor)

Alimenta ações prescritivas: retenção, cross‑sell, upgrade de mix

O que medi:

Estabilidade (%) por cliente e por perfil dominante

Transições mês‑a‑mês (matriz Origem → Destino)

Entropia média das probabilidades por janela (sinal de incerteza/volatilidade)

Como fiz:

Feature store em Spark (RFMT estendido) + calculateAttributes_v4

Perfis estimados via matching probabilístico (Mahalanobis com regularização)

Loop temporal com janelas mensais + tracking por cliente

Avaliação com Kappa/Precision/Recall/F1 no classificador supervisionado de perfis

Resultado: uma visão contínua de como a base evolui — quem está consolidando valor e quem está “escorregando” de perfil.

👉 No próximo post, mostro como transformar as transições em regras prescritivas (quem abordar, quando e com qual oferta).

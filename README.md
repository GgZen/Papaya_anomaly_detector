# Papaya_anomaly_detector
## Sistema de visão computacional para diagnóstico de anomalias em plantas de mamão (Carica papaya L.) baseado em autoencoders.

Algumas estratégias baseadas em visão computacional,  aprendizado profundo e redes convolucionais vem sendo utilizadas para a detecção de doenças em folhas e frutos do mamoeiro (de Moraes et al., 2023; Habib et al., 2020; Hossen et al., 2020; Hridoy & Tuli, 2021a, 2021b; Maski & Thondiyath, 2021; Veeraballi et al., 2020) e deonstrado sucesso em seu propósito. Entretanto as abordagens adotadas até o presente momento não integram os modelos a nenhum sistema embarcado, além disso os modelos, em sua maioria modelos de reconhecimento, são grandes e demandariam de um poder de processamento maior desses sistemas.

Modelos gerados através da técnica de Autoencoders, uma abordagem usada para aprender codificações eficientes de dados não rotulados (Benfenati et al., 2023), e  suas variações vem demonstrando grande potencial na detecção de diversas doenças  (Benfenati et al., 2023; Habaragamuwa et al., 2021; Mahmoud et al., 2020; Si & Kim, 2023) pela  sua capacidade de diferenciação e pelo tamanho de suas redes geradas. Este tipo de  rede aprende uma função de codificação que transforma os dados de entrada e uma  função de decodificação, que recria os dados de entrada a partir da representação  codificada (Drori, 2022).

Assim, esse estudo teve por objetivo a criação de um modelo baseado na técnica de Autoencoder e sua integração a um sistema de visão computacional para detecção de anomalias, com processamento, classificação e interface para exibição e captura das  imagens com a data e local georreferenciado, com o intuito de auxiliar nos estudos de detecção de viroses no mamoeiro.


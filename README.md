# Papaya_anomaly_detector
## Sistema de visão computacional para diagnóstico de anomalias em plantas de mamão (Carica papaya L.) baseado em autoencoders.

### INTRODUÇÃO
Algumas estratégias baseadas em visão computacional,  aprendizado profundo e redes convolucionais vem sendo utilizadas para a detecção de doenças em folhas e frutos do mamoeiro (de Moraes et al., 2023; Habib et al., 2020; Hossen et al., 2020; Hridoy & Tuli, 2021; Maski & Thondiyath, 2021; Veeraballi et al., 2020) e deonstrado sucesso em seu propósito. Entretanto as abordagens adotadas até o presente momento não integram os modelos a nenhum sistema embarcado, além disso os modelos, em sua maioria modelos de reconhecimento, são grandes e demandariam de um poder de processamento maior desses sistemas.

Modelos gerados através da técnica de Autoencoders, uma abordagem usada para aprender codificações eficientes de dados não rotulados (Benfenati et al., 2023), e  suas variações vem demonstrando grande potencial na detecção de diversas doenças  (Habaragamuwa et al., 2021; Mahmoud et al., 2020; Si & Kim, 2023) pela  sua capacidade de diferenciação e pelo tamanho de suas redes geradas. Este tipo de  rede aprende uma função de codificação que transforma os dados de entrada e uma  função de decodificação, que recria os dados de entrada a partir da representação  codificada (Drori, 2022).

Assim, esse estudo teve por objetivo a criação de um modelo baseado na técnica de Autoencoder e sua integração a um sistema de visão computacional para detecção de anomalias, com processamento, classificação e interface para exibição e captura das  imagens com a data e local georreferenciado, com o intuito de auxiliar nos estudos de detecção de viroses no mamoeiro.

### MODO DE UTILIZAÇÃO
    Dataset -
        Contem 20 imagens normais e anômalas:
        - data_norm - Exemplos de imagens normais para serem utilizadas;
        - data_anom - Edemplos de imagens anômalas para serem utilizadas.

    Inference -

    Model -
        - model_checkpoint_epoch_48.h5 - Modelo da última época treinada;
        - loss_history - Histórico do loss de todas as épocas treinadas;
        - thresholds_per_epoch - Thresholda de todas as épocas treinadas.
        
    Train -

### REFERÊNCIA
    Benfenati, A., Causin, P., Oberti, R., & Stefanello, G. (2023). Unsupervised deep learning techniques for automatic detection of plant diseases: reducing the need of manual labelling of plant images. Journal of Mathematics in Industry, 13(1). https://doi.org/10.1186/s13362-023-00133-6

    de Moraes, J. L., de Oliveira Neto, J., Badue, C., Oliveira-Santos, T., & de Souza, A. F. (2023). Yolo-Papaya: A Papaya Fruit Disease Detector and Classifier Using CNNs and Convolutional Block Attention Modules. Electronics (Switzerland), 12(10). https://doi.org/10.3390/electronics12102202

    Drori, I. (2022). Variational Autoencoders. In The science of deep learning (p. 22). Cambridge University Press. https://doi.org/10.1017/9781108891530

    Habaragamuwa, H., Oishi, Y., & Tanaka, K. (2021). Achieving Explainability for Plant Disease Classification with Disentangled Variational Autoencoders. http://arxiv.org/abs/2102.03082
    
    Habib, M. T., Majumder, A., Jakaria, A. Z. M., Akter, M., Uddin, M. S., & Ahmed, F. (2020). Machine vision based papaya disease recognition. Journal of King Saud University - Computer and Information Sciences, 32(3), 300–309. https://doi.org/10.1016/j.jksuci.2018.06.006

    Hossen, M. S., Haque, I., Islam, M. S., Ahmed, M. T., Nime, M. J., & Islam, M. A. (2020). Deep Learning based Classification of Papaya Disease Recognition. 2020 3rd International Conference on Intelligent Sustainable Systems (ICISS), January, 945–951. https://doi.org/10.1109/ICISS49785.2020.9316106

    Hridoy, R. H., & Tuli, M. R. A. (2021). A Deep Ensemble Approach for Recognition of Papaya Diseases using EfficientNet Models. 2021 5th International Conference on Electrical Engineering and Information and Communication Technology, ICEEICT 2021, 1–6. https://doi.org/10.1109/ICEEICT53905.2021.9667825

    Mahmoud, M. A. B., Guo, P., & Wang, K. (2020). Pseudoinverse learning autoencoder with DCGAN for plant diseases classification. Multimedia Tools and Applications, 79(35–36), 26245–26263. https://doi.org/10.1007/s11042-020-09239-0
    
    Maski, P., & Thondiyath, A. (2021). Plant disease detection using advanced deep learning algorithms: A case study of papaya ring spot disease. 2021 6th International Conference on Image, Vision and Computing, ICIVC 2021, 49–54. https://doi.org/10.1109/ICIVC52351.2021.9526944

    Si, J., & Kim, S. (2023). Chili Pepper Disease Diagnosis via Image Reconstruction Using GrabCut and Generative Adversarial Serial Autoencoder. http://arxiv.org/abs/2306.12057

    Veeraballi, R. K., Nagugari, M. S., Annavarapu, C. S. R., & Gownipuram, E. V. (2020). Deep Learning Based Approach for Classification and Detection of Papaya Leaf Diseases (A. Abraham, A. K. Cherukuri, P. Melin, & N. Gandhi, Eds.; Vol. 940, Issue March, pp. 291–302). Springer International Publishing. https://doi.org/10.1007/978-3-030-16657-1_27
 

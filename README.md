# Analise_sentimentos_AzureAI

### Este projeto tem como objetivo realizar a conversão de fala em texto em tempo real, utilizando um trecho de áudio extraído de um vídeo do YouTube, e, em seguida, aplicar uma análise de sentimentos ao texto transcrito usando o Azure AI Speech Studio e Language Studio. O intuito do projeto foi para demonstrar a funcionalidade de reconhecimento de fala e análise de sentimentos, podendo ser aplicada em diversas áreas, como transcrição e análise de reuniões, legendas automáticas com insights emocionais, assistência a pessoas com deficiência auditiva e monitoramento de feedback em tempo real.

## Tecnologias Utilizadas

#### Reconhecimento de áudio: Azure AI/Speech Studio/Real-time speech to text 

#### Análise de Sentimentos: Azure AI/Language Studio/Analyze sentiment and opinions

### Para criar um recurso de Azure AI no seu projeto, siga os passos abaixo:

link: https://portal.azure.com

Acesse o Azure AI: Abra o Azure AI e faça login com sua conta Microsoft. 

1.Crie um novo recurso:

    No menu, selecione Settings e depois Create a resource.

2.Configure o recurso com as seguintes informações:

    Nome do recurso: Insira um nome único.
    
    Assinatura: Escolha sua assinatura do Azure.
    
    Região: Selecione uma região suportada.
    
    Tipo de preço: Escolha o plano Free F0 (se disponível, caso contrário, selecione Standard S0).
    
    Grupo de recursos: Selecione ou crie um grupo de recursos com um nome único.

Finalize a criação:

    Clique em Create resource e aguarde até que o recurso seja criado. Depois, selecione Use resource para acessar a página Get started with Speech.

## Speech Studio

#### Conversão de Fala em Texto no Speech Studio:

link: https://speech.microsoft.com/portal

1.Acesse a funcionalidade de Conversão em Tempo Real:

    Na página Get started with Speech, localize a opção Speech to text e selecione Try out Real-time speech to text.
    

2.Selecione o arquivo de áudio:

    Em Choose audio files, clique em Browse files e navegue até a pasta onde o arquivo WhatAICanDo.m4a foi salvo. Selecione o arquivo e clique em Open.

3.Transcrição em tempo real:

    O serviço de Speech começará a transcrever o áudio para texto em tempo real. Se o áudio estiver disponível no seu computador, você poderá ouvir a gravação enquanto o texto é transcrito.


### Output:

![Captura de tela 2025-02-01 120829](https://github.com/user-attachments/assets/31e97802-6bae-4c03-b0d0-9e10d7093b59)


## Language Studio

#### Analisando Avaliações no Language Studio

link: https://language.cognitive.azure.com.

1.Selecione a funcionalidade de Análise de Sentimentos:

    Na página inicial do Language Studio, vá até a aba Classify text e selecione a opção Analyze sentiment and mine opinions.

2.Configure o idioma e o recurso:

    Em Select text language, escolha English (ou o idioma desejado).

    Em Select your Azure resource, selecione o recurso do Azure que você criou.

3.Insira o texto para análise:

    Em Enter your own text, upload a file, or use one of our sample texts, você pode:

    Copiar e colar uma avaliação ou texto diretamente.

    Fazer upload de um arquivo.

    Usar um dos textos de exemplo disponíveis.

4.Execute a análise:

    Após inserir o texto, o Language Studio analisará o sentimento e as opiniões contidas no conteúdo, fornecendo insights sobre o tom (positivo, negativo ou neutro) e os aspectos mencionados.


### Output: 

![analyzed_sentiment](https://github.com/user-attachments/assets/1b22d2e9-3884-45c8-9072-f6e4bea5d70f)

![sentence_1](https://github.com/user-attachments/assets/68f0dc30-1b23-4b83-a294-c17eddeb75c3)

![sentence_2](https://github.com/user-attachments/assets/d13c635c-9527-465f-b59f-ea9f77f9176e)

![sentence_3](https://github.com/user-attachments/assets/54751da7-c104-4185-8db7-4628025bfd81)

![sentence_4](https://github.com/user-attachments/assets/a2af2a47-ba95-40ab-939b-71849b9feda1)


    

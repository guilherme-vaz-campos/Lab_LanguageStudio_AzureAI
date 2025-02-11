# Lab_LanguageStudio_AzureAI
Laboratório sobre o uso do Serviço Language Studio dentro do Azure AI para Analise de Sentimentos

# Ferramenta usada:
https://language.cognitive.azure.com/tryout/sentiment

# Frase de input usada entre os modelos:

"Hello,

        My name is Mateo Gomez and I visited Contoso Restaurant with my spouse for our anniversary last Thursday. I had heard wonderful things about your food and service from my neighbors as I lived right down the street from you at 1234 Hollywood Boulevard. After a lovely stroll along the Santa Monica Pier, we decided to go for dinner at Contoso. But when we got to the restaurant, we had to wait for 15 minutes just to get on the waiting list. After an hour of waiting to get seated, we ordered two Surf and turf platters. To our absolute surprise, the food was very cold and dry. The whole experience was just awful, and I expect a refund for our meal and an apology for that day. Please issue me a refund at the earliest and call me on 123-456-7890 for any further questions."

# Output da analise de sentimentos:

Analyzed sentiment

Document sentiment: mixed

Confidence: 50.00%

Positive: 50.00%

Neutral: 1.00%

Negative: 49.00%

# Reflexão sobre os dados
A analise de sentimentos foi mista devido ao comentário positivo do cliente sobre ter passado uma tarde amavel no Pier de Santa Monica, mas em relação a experiência no Restaurante Contoso, a analise direta ficou entre neutra e negativa, sendo que comentário final solicitando reembolso já demonstra a insatisfação do cliente, mas a IA de analise de sentimentos atribuiu peso neutro neste item.
Isto demonstra que a IA ainda precisaria de mais treinamento e ajustes em seu modelo.

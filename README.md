# venus-api
API Portuguesa de agregação de dados de outras API ou sites, de pesquisa no Google, na Wikipedia ou no Youtube. Como a API foi desenhada para respostas em sistema de chat e AI as respostas contêm os textos e não os links. Acesso à Venus2 IA e ao Chat GPT. 

https://venus2.net/api

# Venus2

A Vénus 2.0 é uma plataforma inovadora de inteligência artificial focada na preservação e evolução da língua portuguesa no mundo digital, combinando automação, aprendizagem profunda e funcionalidade prática. Com ferramentas que incluem um assistente pessoal, capacidades de domótica, compilação de notícias em tempo real e interação avançada em português, a Vénus 2.0 promove a democratização da inteligência coletiva e a inclusão do português na era das máquinas, moldando um futuro mais conectado e inclusivo.

pedido: https://venus2.net/api/venus?say=[termo] | fonte: https://venus2.net | retorno: Retorna a resposta da Venus2. Inicialmente verifica se é um comando especial, de seguida pesquisa na memória estática de venus1 e no final envia para a OpenAI (ChatGPT), se não tiver resposta das anteriores. Tudo em português de Portugal.
 
# Tempo

Metereologia de Portugal a partir do IPMA colhida em tempo real.

pedido: https://venus2.net/api/tempo/[cidade] | fonte: https://api.ipma.pt/open-data/forecast/meteorology/cities/daily/ | ficheiro: ipma-locais.json

# Pesquisa

Pesquisa pela api no Google, na Wikipedia ou no Youtube.
## Google
pedido: https://venus2.net/api/pesquisa/google/[pesquisa] | fonte: google.com  | retorno: os 10 primeiros resultados da pesquisa no Google search.
## Youtube
pedido: https://venus2.net/api/pesquisa/youtube/[termo] | fonte: youtube.com | dois primeiros resultados da pesquisa no Youtube.
## Wikipedia
pedido: https://venus2.net/api/pesquisa/wiki/[termo] | fonte: Wikipedia | retorno: primeira frase do resultado do termo na wikipedia.

# Ocorrências

Alertas meterológicos Portugal a partir do IPMA.

pedido: https://venus2.net/api/ocorrencias/alertas | fonte: https://api.ipma.pt/

Ocorrências em Portugal oriundos do fogos.pt e outras plataformas.

pedido: https://venus2.net/api/ocorrencias/fogos | fonte: fogos.pt | retorno: primeiro resultado

Eventos mundiais a partir da NASA.

pedido: https://venus2.net/api/ocorrencias/nasa | fonte: nasa.gov | retorno: resultado dos eventos na api da NASA.

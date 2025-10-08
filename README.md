🚀 Desafio de Documentação Técnica | Bootcamp Randstad
Este repositório documenta a jornada de aprendizado e aplicação prática dos conceitos do Bootcamp Randstad - Análise de Dados, uma parceria com a DIO (Digital Innovation One). O foco deste desafio é explorar e documentar as funcionalidades das ferramentas de Inteligência Artificial da Microsoft Azure.


🎯 Objetivos do Desafio
Aplicar os conceitos aprendidos em um ambiente prático e controlado.

Documentar processos técnicos de forma clara, estruturada e acessível.

Utilizar o GitHub como ferramenta principal para versionamento e compartilhamento de documentação técnica.

Requisitos do Repositório:
[x] Um arquivo README.md detalhado (você está aqui!).

[x] Arquivos adicionais relevantes para documentar a experiência.

[x] Capturas de tela organizadas em uma pasta /images (opcional).



🔬 Análise de Ferramentas: Azure AI Studio
Foram exploradas duas ferramentas principais do ecossistema Azure AI: Speech Studio e Language Studio. Abaixo estão os detalhes dos testes realizados e os insights obtidos.

🎤 1. Speech Studio: Transcrição de Áudio para Texto
O teste consistiu em analisar a capacidade da IA de transcrever diferentes tipos de áudio.

Cenário de Teste 1: Entrevista em Inglês (EUA)
Descrição: Um arquivo de áudio curto com uma entrevista, onde os interlocutores falam de forma clara e alternada.

Resultado:

🌟 Sucesso! A IA transcreveu o áudio com altíssima precisão. Todas as palavras foram identificadas corretamente, e a pontuação (vírgulas, pontos finais e interrogações) foi adicionada de forma automática e coerente.

Cenário de Teste 2: Conversa em Português (Brasil)
Descrição: Um arquivo de áudio com uma conversa informal, onde múltiplas pessoas falam ao mesmo tempo em alguns trechos.

Resultado:

⚠️ Performance Reduzida. A eficácia da transcrição foi visivelmente menor. A IA teve dificuldade em discernir as falas sobrepostas, capturando palavras soltas de diferentes conversas. O texto final ficou desconexo e sem sentido claro.

💡 Insights sobre o Speech Studio
É uma ferramenta excelente e fácil de usar para transcrição de áudios limpos, como reuniões, palestras ou locuções para vídeos.

A IA pode se confundir e perder precisão se houver sobreposição de vozes.

Possui um grande potencial como ferramenta de acessibilidade, auxiliando pessoas com deficiência auditiva ou permitindo a revisão de conteúdo falado de forma assíncrona.



✍️ 2. Language Studio: Análise de Sentimentos
Esta ferramenta exigiu um processo de configuração um pouco mais detalhado em comparação com o Speech Studio.

Setup: Foi necessário criar uma conta no portal Azure, cadastrar um cartão de crédito (mesmo para a camada gratuita) e provisionar um recurso de serviço de IA antes de poder utilizá-lo.

Cenário de Teste: Foi analisada uma avaliação de um hotel, extraída do Google Maps, para extrair o sentimento e as entidades principais.

💡 Insights sobre o Language Studio
É uma ferramenta poderosa para análise de texto, como comentários de clientes, avaliações de produtos ou mensagens em redes sociais.

Permite obter rapidamente um parâmetro geral do sentimento (positivo, negativo, neutro) de um grande volume de dados textuais.

Um dos seus pontos fortes é a capacidade de identificar e destacar os pontos mais críticos ou mencionados em uma mensagem, otimizando o tempo de análise.

⭐ Conclusão Geral
Tanto o Speech Studio quanto o Language Studio se mostraram ferramentas robustas e com aplicações práticas valiosas para o campo da análise de dados. Enquanto o primeiro brilha pela simplicidade e eficácia na transcrição de áudios claros, o segundo oferece uma análise profunda e detalhada de sentimentos em textos, ambos contribuindo para a extração de insights importantes a partir de dados não estruturados.

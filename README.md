# master_thesis
Identificação de encadeamento harmônico a partir de áudios musicais.

## Resumo
A ideia do presente projeto é, partindo de áudios de canções como _input_, conseguir determinar a harmonia da canção ali presente. Idealmente, o modelo receberá o áudio completo de uma música e nos retornará uma sequência de acordes coerente com definições e conceitos-chave da área de harmonia e percepção musical. Trata-se de um problema que se utilizará de muitas técnicas de processamento de sinais e que engloba uma série de tarefas intermediárias, como por exemplo 
1. detecção do andamento, para acessar os momentos em que provavelmente ocorrerá uma mudança de acorde;
2. identificação da tonalidade da música, obtendo, assim, seu campo harmônico. Ele nos fornecerá os acordes que têm maior probabilidade de ocorrência dentro daquela tonalidade.

## Plano de trabalho
#### Levantamento de dados
Etapa crucial e desafiadora para o desenvolvimento do modelo. Isso porque, hoje em dia, não existe uma base de dados robusta que contenha áudios de canções juntamente com sua harmonia sincronizada. Por conta disso, a opção mais prática que encontramos foi trabalhar a partir de arquivos xml de música, que contêm explicitamente informações a respeito de andamento, melodia, harmonia, tempo, compasso e etc. Assim, conseguimos utilizar estes arquivos para gerar áudios sinteticamente, com a vantagem de sabermos a sequência exata de acordes ali presente, bem como os momentos em que a harmonia muda. 

#### Desenvolvimento de rotinas de extração
Esta etapa consiste num estudo aprofundado de features musicais que conseguimos extrair dos arquivos de audio. Será necessário entender que tipos de informação nos ajudam mais na tarefa de reconhecimento de harmonia.

#### Ajustes de técnicas de processamento de sinal

#### Desenvolvimento e treinamento do modelo

#### Otimização de parâmetros

#### Construção de base de dados anotados

#### Validação das análises
Finalmente, o último passo será aplicar os métodos desenvolvidos em áudios de gravações reais, realizada por músicos. Eventualmente, precisaremos retornar e repensar em alguns dos pontos citados acima.


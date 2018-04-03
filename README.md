# IOT-PROJECT
Fundamentos da Internet das Coisas

# Título do projeto: "Identificador de Emoções"
- Visão geral do projeto: 
O projeto consiste em desemvolver uma ferramenta que permita identificar as emoções de uma pessoa, a partir dos dados coletados da pessoa durante um periodo de tempo.
Quatro emocões básicas foram identificadas (Medo, alegria, tristeza e raiva) das quais vai ser interessante mostrar o que uma pessoa sente através de seus batimentos cardiacos, isto vai permitir tomar ações de regulamento das emoções especialmente as negativas para evitar problemas psicologicos para pessoas com limitações para expresar seus emoções de forma natural.
- Público alvo: 
Qualquier Pessoa que quiser experimentar,mas especialmente as pessoas com alguma deficiência que não possa expressar suas emoções. 

# Descrição técnica
Sensores de Batimentos Cardiacos: Para o desenvolvimento deste projeto se identifico 3 tipo de sensores.

1) PULSE SENSOR SEN-11574(familia arduino).
2) Polar H7 Heart Rate Sensor.
3) Heart Rate Monitor Galaxy Note 4.

Se escolhio a opção 2, porque segun alguns estudos realizados em laboratório demonstram que esse modelo apresenta precisão suficiente para capturar a variabilidade cardiaca e pela facilidade da captura dos dados desde outros dispositivos. Outra vantagem é que ele captura os dados na ordem dos milissegundos o que vai permitir obter mais cantidade dos dados.

- Características do Polar H7 Heart Rate Sensor:
O sensor de frequência cardíaca Polar H7 é compatível com dispositivos Bluetooth® Smart Ready(bluetooth low energy) que suportam o serviço de frequência cardíaca,  permitindo sua captura em qualquer computador ou telefone celular.

![alt text](https://github.com/caiki/IOT-PROJECT/blob/master/technical-specification.png)

# Descrição da arquitetura
1) Criar um aplicativo de captura de dados pode ser para um smartphone ou um computador. 
2) Criar os métodos de transformação de informacão: Aqui se pode usar a técnica de ETL (Extração, Transformação e Carga) para a limpeza e ordenamento dos dados, para logo criar o banco de dados dos batimentos cardiacos ordenados pelas distintas emoções básicas (Medo, alegria, tristeza e raiva).
3) Análise da informação: Utilização técnicas de Aprendizajem de Maquina, entre eles os algoritmos de Aprendizajem Supervisado para identificar a que tipo de emoção corresponde a nova data capturada ou possivelmente técnicas de Análise de Series Temporais porque os dados estaram em função do tempo também.
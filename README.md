# IOT-PROJECT
Fundamentos da Internet das Coisas

# Título do projeto: "Monitoramento da frequência cardiaca"
- Visão geral do projeto: 
Nem sempre o aumento das batidas do coração é causado por alguma situação preocupante. O coração pode ficar batendo mais forte ou acelerado em situações do dia a dia como:
-Diante de fortes emoções;
-Ataque de pânico ou ansiedade;
-Durante a relação sexual;
-Quando há febre;
-Durante a prática de exercícios;
-Ao fazer algum esforço;
-Devido ao uso de medicamentos;
-Quando a pressão está alta, Veja o que fazer se a pressão estiver alta;
-Devido a ingestão de grandes quantidades de álcool ou cafeína;
-Quando existe alguma doença cardíaca, como insuficiência cardíaca ou doença cardíaca valvar, assim como de outras doenças como aterosclerose ou hipertensão.
-Como há muitos fatores que desencadeiam um alto nível de freqüência cardíaca, é necessário controlá-los, o que pode ser controlado com ferramentas de internet das coisas.  

O projeto consiste em desemvolver uma ferramenta que permita identificar o nivel de stress, a partir dos dados coletados da frecuencia cardiaca de uma pessoa durante um periodo de tempo. 

- Público alvo: 
Especialmente em aquelas pessoas que precisen sob uma ordem médica controlar seus niveis de frecuencia cardiaca, para que possam evitar complicações cardíacas ou qualquer outra pessoa que queira controlar seus níveis de estresse.
# Descrição técnica
Sensores de Batimentos Cardiacos: Para o desenvolvimento deste projeto se identifico 3 tipo de sensores.

1) PULSE SENSOR SEN-11574(familia arduino).
2) Polar H7 Heart Rate Sensor.
3) Heart Rate Monitor Galaxy Note 4.

Se escolhio a opção 2, porque segun alguns estudos realizados em laboratório demonstram que esse modelo apresenta precisão suficiente para capturar a variabilidade cardiaca e pela facilidade da captura dos dados desde outros dispositivos.Outra vantagem é que ele captura os dados na ordem dos milissegundos o que vai permitir obter mais cantidade dos dados, porque ele pode capturar dados enquanto faz outras atividades.
![alt text](https://github.com/caiki/IOT-PROJECT/blob/master/sensor.png)

- Características do Polar H7 Heart Rate Sensor:
O sensor de frequência cardíaca Polar H7 é compatível com dispositivos Bluetooth® Smart Ready(bluetooth low energy) que suportam o serviço de frequência cardíaca,  permitindo sua captura em qualquer computador ou telefone celular.

![alt text](https://github.com/caiki/IOT-PROJECT/blob/master/technical-specification.png)

# Descrição da arquitetura
1) Criar um aplicativo de captura de dados pode ser para um smartphone ou um computador. 
2) Criar os métodos da recoleção dos dados: Definir as actividades onde os dados vão ser capturados.
3) Criar os métodos de transformação de informacão: Aqui se pode usar a técnica de ETL (Extração, Transformação e Carga) para a limpeza e ordenamento dos dados, para logo criar o banco de dados dos batimentos cardiacos ordenados.
4) Análise da informação: Utilização técnicas de Aprendizajem de Maquina, entre eles os algoritmos de Aprendizajem Supervisado para identificar a que tipo de emoção corresponde a nova sinal capturada ou possivelmente técnicas de Análise de Series Temporais porque os dados estaram em função do tempo também.
5) Criar aplicativo para comunicar ao usuario ou uma terceira pessoa(Médico,Enfermeira,Família) se sua frecuencia cardiaca esta alta, para que possa tomar desicões de correcção e assim normalizar seu estado.
![alt text](https://github.com/caiki/IOT-PROJECT/blob/master/architectureotms.png)
# Fontes
- https://mro.massey.ac.nz/bitstream/handle/10179/3364/02_whole.pdf?sequence=1&isAllowed=y
- https://w3.psychology.su.se/staff/sws/Wiens00_heartbeatemotion.pdf
- https://www.sciencedirect.com/science/article/pii/S0165178116312550
- https://www.researchgate.net/publication/282918150_Emotion_recognition_based_on_heart_rate_and_skin_conductance
- https://www.sciencedirect.com/science/article/pii/S1877050917316745

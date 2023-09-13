#Participantes :
Ana Zerlin         RM98065
Bianca Dancs       RM551645
Gabriel Pimentel   RM99880
Hellen Assis       RM98284

#Recursos necessários para implantação :
 1. Medidor, para calcular a porcentagem dos gases nos galpões;
 2. ESP32, que vai tornar a conexão entre o sistema operacional e o medidor possível através do WI-FI;
 3. IoT, conecta com o ESP32 e recebe as informações dadas pelo medidor;
 4. Lâmpada ou led, indicará se as ventoinhas precisarão ser abertas.

#Como funciona :
1. A porcentagem de determinado gás no ambiente será coletada de tempo em tempo;
2. Esses dados são passados para o sistema principal;
3. Os números recebidos serão analizados e determinarão se é necessário ou não iniciar a operação para ventilação;
3.1. O sistema chega a conclusão a partir de um cógido dentro dele introduzido posteriormente;
4. Caso a porcentagem de gases nocivos no ambiente seja maior do que o aceitável, um operador/funcionário da unidade irá acionar a operação para ventilção do galpão.

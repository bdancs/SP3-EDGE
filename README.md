## Participantes

Ana Zerlin         RM98065
Bianca Dancs       RM551645
Gabriel Pimentel   RM99880
Hellen Assis       RM98284

## Recursos necessários para implantação
    1. Sensor de Gás MQ-2, para verificar a presença de gases inflamáveis nos galpões;
    2. ESP32, tornando a conexão por WI-FI entre o sistema operacional e o sensor possível;
    3. IoT, conecta com o ESP32 e recebe as informações dadas pelo medidor;
    4. Lâmpada ou led, alerta visual;
    5. Campainha ou buzzer(maiores proporções do que de um protótipo), aviso sonoro.


## Protocolo de funcionamento
    1. O sensor estará coletando informações sobre o ambiente de tempo em tempo;
    2. Esses dados são passados para o sistema principal através do ESP32(WI-FI);
    3. Os números recebidos serão analizados e determinarão se é necessário ou não iniciar a operação para ventilação;
    3.1. O sistema chega a conclusão a partir de um cógido dentro dele introduzido posteriormente;
    4. Caso a quantidade de gases inflamáveis no ambiente seja maior do que a norma considerada segura para esses espaços, as luzes e campainhas serão acionadas;
    5. Assim, um operador/funcionário da unidade irá abrir a ventilção do galpão;
    6. O corpo de bombeiros será acionado para fazer uma inspeção e garantir que está seguro para voltar as operações ao normal.

## Demonstração do funcionamento
    Link da demonstração do funcionamento do sistema de alarme de forma simplificada(sem o ESP32) :
        https://www.tinkercad.com/things/9rcP97f9xNt
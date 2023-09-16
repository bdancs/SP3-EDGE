## Participantes
- Ana Zerlin         RM98065
- Bianca Dancs       RM551645
- Gabriel Pimentel   RM99880
- Hellen Assis       RM98284

## O que é
    Este projeto foi criado para fazer o monitoramento de gases inflamáveis nos galpões usados pela Urbitável, onde o lixo é armazenado e separado antes de ir para a unidade principal de descarte, garantindo a segurança dos funcionários. As estações de separação do lixo ficam em bairros residenciais para serem de fácil acesso a população, e por carregarem diferentes tipos de lixo dentro de seus galpões, alguns altamente inflamáveis, é importante que exista um meio de detectar qualquer tipo de gás inflamável para garantir uma resposta rápida do corpo de bombeiros.

## Recursos necessários para a implementação
- Sensor de Gás MQ-2, para verificar a presença de gases inflamáveis nos galpões e em que concentração se encontram;
- ESP32, tornando a conexão por WI-FI entre o sistema operacional e o sensor possível;
- IoT, conecta com o ESP32 e recebe as informações dadas pelo medidor;
- Lâmpada ou led, alerta visual;
- Campainha ou buzzer(maiores proporções do que de um protótipo), aviso sonoro.


## Protocolo de funcionamento
1. O sensor estará coletando informações sobre o ambiente a todo momento;

2. Esses dados são passados para o sistema principal através do ESP32(WI-FI);

3. Os números recebidos serão analizados e determinarão se é necessário ou não iniciar a operação para ventilação e evacuação do prédio;
3.1. O sistema chega a uma conclusão a partir de um cógido dentro dele, introduzido posteriormente;

4. Caso a quantidade de gases inflamáveis no ambiente seja maior do que a norma considerada segura para esses espaços, as luzes e campainhas serão acionadas;

5. O corpo de bombeiros será acionado automaticamente pelo próprio sistema, para fazer uma inspeção e garantir a segurança de todos;

6. Um operador/funcionário da unidade, responsável pelo monitoramento do sistema de segurança irá abrir as ventilções do galpão enquanto o corpo de bombeiros não chega;

7. Após a avaliação dos especialistas, o líder da unidade irá decidir se as operações voltaram no dia ou irão ser encerradas até que tudo volte ao normal.
## Demonstração do funcionamento
Link da demonstração do funcionamento do sistema de alarme de forma simplificada(sem o ESP32) :

https://www.tinkercad.com/things/9rcP97f9xNt

## Vídeo sobre IoT :

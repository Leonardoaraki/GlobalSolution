# GlobalSolution

Enrico do Nascimento Ferreira Galdino - RM552082
Vinicius Durce Carlini - RM550427
Leonardo Shoiti Araki - RM 98587
Fabio de Oliveira Targa - RM551328 
Eduardo Ferreira Silva de Jesus – RM98410 
	

Descrição primária e Instruções de Execução

1. Componentes do Sistema
ESP32 : Processador principal que lê dados, calcula consumo e controla LEDs.
Potenciômetro : Representa uma fonte de corrente variável.
LEDs (verde, amarelo, vermelho) : Indicadores de nível de consumo.
Resistores (220Ω) : Protegem os LEDs de sobrecorrente.
Console Serial : Exibe leituras, mensagens de alerta e atualizações.

2. Pré-requisitos
Simulador : Utilize o Wokwi para rodar uma simulação.
Código : Suba o código fornecido no simulador.
Configuração JSON : Verifique se o arquivo diagram.jsoncontém as conexões corretas dos componentes.

3. Etapas para Execução no Wokwi
Carregar o Projeto :

Abra o Wokwi .
Faça o upload do arquivo diagram.json.
Configurar o Hardware Virtual :

-se de que os LEDs e resistores estão conectados corretamente.
O potenciômetro deve ter pinos conectados a GND , 3V3 , e ao pino A34 do ESP32.
Subir o Código no Simulador :

Copie o código completo do programa para a aba de edição de código no Wokwi.
Compile o código clicando no botão Play .
Monitorar o Serial :

Abra o Serial Monitor (ícone no canto superior direito).
Configure uma taxa de transmissão para 115200 baud .

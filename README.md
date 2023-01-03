# RegaGotejamento
Projeto de um microcontrolador para um ou mais campos.

##Mestre
O dispositivo mestre é responsavel por conectar-se a internet via mqtt, e definir o parametro de umidade(setpoint) de cada campo.

##Escravo
O dispositivo escravo é responsavel por acionar um dispositivo capaz de interromper o fluxo de agua, usualmente uma solenoide.

##Materiais Necessarios
No projeto, o dipositivo mestre utilizado foi um Esp32 e o escravo um Esp8266.

# IOT Monitoramento do consumo eletrico de um equipamento <br />


|Materiais e Componentes| 
| ------ |
| WEMOS D1 MINI PRO Mais informações neste link: [GUIA WEMOS D1 MINI PRO](https://goo.gl/Gs3dgQ) <br /> <img alt="WEMOS D1 MINI PRO SCHEMATIC" src="https://raw.githubusercontent.com/filipecavalc/IOT-monitoramento-do-consumo-eletrico-de-um-equipamento/master/Materiais%20e%20componentes/wemos_d1_mini_pro_pinout.png" width="250"> |
| ANTENA WEMOS D1 MINI PRO. Sem detalhes, antena padrão e conector padrão, pode ser obtida no kit do WEMOS. <br /> <img alt="ANTENA WEMOS D1 MINI PRO" src="https://raw.githubusercontent.com/filipecavalc/IOT-monitoramento-do-consumo-eletrico-de-um-equipamento/master/Materiais%20e%20componentes/antena.png" width="150"> |
| ACS712 5A. (Vale o aviso de que o output do sensor foi ligado diretamente no analogico do WEMOS D1 MINI PRO, pois o mesmo trabalha em uma faixa de até 3.4 volts no output, outro modelo de ACS712 trabalham com tensões mais altas no output, então o circuito deverá ser revisitado com as devidas alterações) Mais informações neste link: [Manual do usuario sensor de corrente ACS712 5A](https://goo.gl/tzyDiZ) <br /> <img alt="ACS712 SCHEMATIC" src="https://raw.githubusercontent.com/filipecavalc/IOT-monitoramento-do-consumo-eletrico-de-um-equipamento/master/Materiais%20e%20componentes/ACS-712-Pinouts.png" width="250"> |
| FONTE YS-12V450A usada para alimentação em 127V ou 220V. Possui saída 5V permitindo ligar o WEMOS D1 MINI PRO e o Sensor ACS712 5A. Mais informações neste link: [YS-12V450A Esquemático](https://goo.gl/hyTrNA) <br /> <img alt="YS-12V450A SCHEMATIC" src="https://raw.githubusercontent.com/filipecavalc/IOT-monitoramento-do-consumo-eletrico-de-um-equipamento/master/Materiais%20e%20componentes/ys-12v450a-Schematic.png" width="260"><img alt="YS-12V450A" src="https://raw.githubusercontent.com/filipecavalc/IOT-monitoramento-do-consumo-eletrico-de-um-equipamento/master/Materiais%20e%20componentes/ys-12v450a.png" width="150"> |
| 2 x BORNE. Mais informações neste link: [Conector Borne KRE 2 Vias](https://goo.gl/vKmvR2) <br /> <img alt="Borne" src="https://raw.githubusercontent.com/filipecavalc/IOT-monitoramento-do-consumo-eletrico-de-um-equipamento/master/Materiais%20e%20componentes/Borne.png" width="150"> |
| Conector macho <br /> <img alt="Conector Macho" src="https://raw.githubusercontent.com/filipecavalc/IOT-monitoramento-do-consumo-eletrico-de-um-equipamento/master/Materiais%20e%20componentes/conector_macho.png" width="150"> |
| Modulo Tomada de energia <br />  <img alt="Modulo Tomada de energia" src="https://raw.githubusercontent.com/filipecavalc/IOT-monitoramento-do-consumo-eletrico-de-um-equipamento/master/Materiais%20e%20componentes/tomada1.png" width="150"> <img alt="Modulo Tomada de energia" src="https://raw.githubusercontent.com/filipecavalc/IOT-monitoramento-do-consumo-eletrico-de-um-equipamento/master/Materiais%20e%20componentes/tomada2.png" width="150"> <img alt="Modulo Tomada de energia" src="https://raw.githubusercontent.com/filipecavalc/IOT-monitoramento-do-consumo-eletrico-de-um-equipamento/master/Materiais%20e%20componentes/tomada3.png" width="150">|
| Placa de Fenolite Perfurada <br /> <img alt="Placa de Fenolite Perfurada" src="https://raw.githubusercontent.com/filipecavalc/IOT-monitoramento-do-consumo-eletrico-de-um-equipamento/master/Materiais%20e%20componentes/placa-fenolite-perfurada.png" width="150"> |


| Protótipagem | 
| ------ |
| Circuito Elétrico. Segue o link para download do arquivo editavel: [Circuito Elétrico easyeda](https://goo.gl/VcahGX) <br /> <img alt="Circuito Monitor Consumo Eletrico IOT" src="https://raw.githubusercontent.com/filipecavalc/IOT-monitoramento-do-consumo-eletrico-de-um-equipamento/master/Projeto%20Circuito%20e%20PCB/IOTEnergia_circuit.png" width="400"> |
| Protótipo PCB Segue o link para download do arquivo editavel: [Projeto PCB easyeda](https://goo.gl/xMyhBx) <br /> <img alt="PCB Monitor Consumo Eletrico IOT" src="https://raw.githubusercontent.com/filipecavalc/IOT-monitoramento-do-consumo-eletrico-de-um-equipamento/master/Projeto%20Circuito%20e%20PCB/IOTEnergia_PCB.png" width="400"> |
| Protótipo implementado em uma Placa de Fenolite Perfurada <br /> <img alt="Protótipo Placa Fenolite Perfurada Frente" src="https://raw.githubusercontent.com/filipecavalc/IOT-monitoramento-do-consumo-eletrico-de-um-equipamento/master/Prot%C3%B3tipo%20fenolite%20perfurado/Prototipo_circuito_fenolite_perfurado_cima.png" width="150"> <img alt="Protótipo Placa Fenolite Perfurada Trás" src="https://raw.githubusercontent.com/filipecavalc/IOT-monitoramento-do-consumo-eletrico-de-um-equipamento/master/Prot%C3%B3tipo%20fenolite%20perfurado/Prototipo_circuito_fenolite_perfurado_baixo.png" width="150">|
|Versão teste de case para a placa de fenolite e demais componentes <br /> <img alt="Case Tampa" src="https://raw.githubusercontent.com/filipecavalc/IOT-monitoramento-do-consumo-eletrico-de-um-equipamento/master/Case%20pr%C3%B3totipo/Tampa_case.png" width="150"> <img alt="Case Entrada Energia" src="https://raw.githubusercontent.com/filipecavalc/IOT-monitoramento-do-consumo-eletrico-de-um-equipamento/master/Case%20pr%C3%B3totipo/Entrada_Energia_case.png" width="150"> <img alt="Case Saida Energia" src="https://raw.githubusercontent.com/filipecavalc/IOT-monitoramento-do-consumo-eletrico-de-um-equipamento/master/Case%20pr%C3%B3totipo/Saida_Energia_case.png" width="150"> <img alt="Case Serial Wemos" src="https://raw.githubusercontent.com/filipecavalc/IOT-monitoramento-do-consumo-eletrico-de-um-equipamento/master/Case%20pr%C3%B3totipo/Wemos_usb.png" width="150"> <img alt="Antena Case" src="https://raw.githubusercontent.com/filipecavalc/IOT-monitoramento-do-consumo-eletrico-de-um-equipamento/master/Case%20pr%C3%B3totipo/Antena_case.png" width="150">|

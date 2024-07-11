### Projeto de uma Fonte de Tensão Ajustável entre 3V a 12V com Capacidade de 100mA

Este projeto visa desenvolver uma fonte de tensão ajustável que forneça uma saída entre 3V e 12V com capacidade de 100mA. A fonte converte a corrente alternada de 127V da rede elétrica em uma tensão contínua ajustável, adequada para várias aplicações eletrônicas. O circuito utiliza um transformador, ponte retificadora, capacitores para filtragem, e um potenciômetro para ajuste de tensão. Componentes como o diodo Zener e transistores garantem a regulação e estabilização da tensão, proporcionando um fornecimento de energia seguro e confiável.

### Descrição dos Componentes

1. **Transformador**
   - Transforma a tensão de 127V AC da fonte de corrente alternada para uma tensão mais baixa adequada ao circuito, com um pico de tensão de 180V.

2. **Ponte Retificadora**
   - Composta por 4 diodos que convertem a corrente alternada (AC) em corrente contínua (DC), considerando uma perda de 1.4V (0.7V por diodo).

3. **Capacitor**
   - Componente eletrônico passivo que armazena energia elétrica e suaviza variações de tensão, escolhido para reduzir o ripple (variação) da tensão para aproximadamente 10%.

4. **Diodo Zener**
   - Regula a tensão máxima do circuito, com uma tensão de ruptura de 13V, ajudando a eliminar oscilações indesejadas.

5. **Potenciômetro**
   - Ajusta a tensão de saída entre 3V e 12V, proporcionando controle variável sobre a voltagem fornecida pelo circuito.

6. **Transistor NPN**
   - Utilizado em conjunto com o Zener para regular a tensão de saída, limitando-a a 12V conforme necessário.

7. **Resistores**
   - Incluídos para controlar corrente em diferentes partes do circuito: um para o LED, outro para o Zener (evitando superaquecimento), um terceiro com o potenciômetro para ajustar a tensão mínima para 3V. Um resistor de 100 ohms não foi incluído devido à falta de um componente com especificações adequadas encontrado pelo grupo.

8. **LED**
   - Adicionado como indicador visual do funcionamento do circuito, sem função prática além de ornamental.

### Tabela de Componentes

| Componente           | Quantidade | Valor Unitário | Valor Total |
|----------------------|------------|----------------|-------------|
| Transformador        | 1          | R$X            | R$X         |
| Ponte Retificadora   | 1          | R$X            | R$X         |
| Capacitor            | 1          | R$X            | R$X         |
| Diodo Zener          | 1          | R$X            | R$X         |
| Potenciômetro        | 1          | R$X            | R$X         |
| Transistor NPN       | 1          | R$X            | R$X         |
| Resistor             | 4          | R$X            | R$X         |
| LED                  | 1          | R$X            | R$X         |
| **Valor Total**      |            |                | **R$X**     |

### Circuito

![Circuito](https://github.com/Wil-tord/Fonte-de-Tens-o-Ajust-vel/blob/main/Circuito.png)

#### Imagem do circuito no Falstad

![Thumbnail](https://github.com/Wil-tord/Fonte-de-Tens-o-Ajust-vel/blob/main/video-thumbnail.png)

#### Para entender mais sobre como o circuito funciona, assista ao vídeo abaixo:

[![Assista ao vídeo](https://github.com/Wil-tord/Fonte-de-Tens-o-Ajust-vel/blob/main/video-thumbnail.png)](https://www.youtube.com/watch?v=2T_0PLn-Tzo)

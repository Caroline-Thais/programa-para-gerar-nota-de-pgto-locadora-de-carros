# programa-para-gerar-nota-de-pgto-locadora-de-carros

Programa que lê os dados da locação (modelo do carro, instante inicial e final da locação), bem como o valor por hora e o valor diário de locação. 
O programa então gera a nota de pagamento (contendo valor da locação, valor do imposto e valor total do pagamento) e informa os dados na tela.

Regras de negócio:
A locadora cobra um valor por hora para locações de até 12 horas. Porém, se a duração da locação ultrapassar 12 horas, a locação será cobrada com base em um valor diário. 
Além do valor da locação, é acrescido no preço o valor do imposto conforme regras do país que, no caso do Brasil, é 20% para valores até 100.00, ou 15% para valores acima de 100.00.

Ferramentas utilizadas:
- Java
- Interfaces / injeção de dependências

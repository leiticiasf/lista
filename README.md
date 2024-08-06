/////////////////////////// RESUMO AULA 06/08 ///////////////////////////

Na aula do dia 06/08 nós dividimos  os arquivos dentro de suas respectivas pastas, garantindo assim um código organizado. Também acertamos o código de cada componente presente na aplicação de viagens e usamos o useState para controlar a página atual e lista de destinos. Criamos um componente de Destinos, e “setamos” alguns países com suas descrições e demos a opção de criação de destinos também.

/////////Regras de Negócio Fundamentais

Todos os pontos para calcular distância devem partir do Brasil.

Temos 10 destinos pré-cadastrados. 

Distâncias acima de 200km serão necessários 2 voos. 

Se o voo for inferior a 2 meses a partir de agora é 1500 reais (considerando ida e volta).

Se o voo for igual ou superior a 2 meses a partir de agora, paga 700 reais (considerando ida e volta).

Acima de 2000 Km cada 1 Km adicional custa 1 real a mais no total.

Cada participante adicional adiciona 25% nos custos de estalagem.


///////Lógica do cálculo de distância e custos da viagem.
Para voos que duram menos de 2 meses será cobrado R$1500,00 (ida e volta).
Para voos que duram mais de 2 meses será cobrado R$700,00 (ida e volta). 
 Distâncias acima de 2000 km: cada km adicional custa R$ 1,00.
     Estadias normais: R$ 400 por semana.
     Estadias de luxo: R$ 700 por semana.
     - Participantes adicionais: aumentam o custo da estadia em 25% por participante.

Para calcular o total da viagem primeiro se calcula a locomoção do avião de acordo com a distância percorrida. O local de hospedagem depende da modalidade escolhida pelo cliente, sendo luxo ou normal, somando isso o número de pessoas acomodadas e o tempo. Ao somar tudo tem-se o total da viagem. 


////////Interface de seleção e exibição do subtotal da viagem.
A interface permite a seleção do destino, o número de participantes, o tipo de acomodação, e as datas de ida e volta. O aplicativo exibe o subtotal da viagem e detalha o custo. 

////////Sugestões e melhorias ao aplicativo desenvolvido.
CSS precisa de ajustes. 
Precisa ter uma interface mais fluida e intuitiva, melhor distribuída também. 


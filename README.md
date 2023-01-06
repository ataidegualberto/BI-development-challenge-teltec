# Teste de Análise De Dados - Teltec Solutions

Esse teste possui o objetivo de medir o seu conhecimento em Python e suas bibliotecas de análise e visualização de dados como o pandas e o matplotlib, por exemplo, além do seu conhecimento em ambientes de desenvolvimento on-line.

Utilizando o dataset disponibilizado ('relatorio_de_vendas.csv'), você terá de encontrar respostas aos problemas propostos. 

As respostas devem estar nas células abaixo do enunciado da questão, e podem ser em forma de Series ou DataFrames do pandas, gráficos do Matplotlib ou Seaborn ou escrito por extenso, dentro de um print, por exemplo. Tente ser o mais claro possível na sua resposta.

Bom teste e boa sorte.


## O Dataset - Relatório de Vendas de Brinquedos


### Estudo de Caso

Você é o analista de dados de uma empresa que manufatura automóveis de brinquedo. Essa empresa vende os brinquedos em atacado, para outras empresas, geralmente supermercados ou lojas especializadas.

O engenheiro de dados da empresa construiu uma pipeline que extraiu dados das vendas de produtos de Janeiro de 2020 a Maio de 2022 e as colocou em arquivo para que um relatório com as informações mais importantes seja feito e apresentado para a diretoria.

Sua função agora é selecionar, limpar, transformar e agregar os dados existentes no dataset para auxiliar a diretoria na tomada de decisões.


### Dicionário de Dados

Colunas               | Significado
--------------------- | ---------------------
**quantidade**        | Quantidade de brinquedos por pedido
**data_do_pedido**    | Data em que o pedido foi feito, <br>no formato de data em português do Brasil, *dia/mês/ano*
**status**            | Status do pedido. As duas opções possíveis são<br> *Concluída*, quando o pedido foi feito e o valor da compra foi pago, e <br> *Cancelada*, para quando a compra não foi finalizada por qualquer motivo
**tipo_do_produto**   | O tipo de brinquedo que foi comprado no pedido. As opções possíveis são<br> *Aviões*, *Barcos*, *Carros Clássicos*, *Carros Vintage*, *Motocicletas*,<br> *Ônibus e Caminhões*, e *Trens*.
**comprador**         | A empresa que fez o pedido
**pais_do_comprador** | O país de origem da empresa que fez o pedido
**valor_do_pedido**   | O valor, em moeda, do pedido feito. A moeda é irrisória, mas assumindo que <br>a empresa do estudo de caso é brasileira, trataremos como *Real (R$)*.

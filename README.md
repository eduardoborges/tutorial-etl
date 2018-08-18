# Utilizando um ETL

## Investimentos Públicos - OGU - Pagos

Instrumento avaliativo #3 da disciplina de Sistemas de Apoio a Decisão, ministrada pelo Prof. Gilton José Ferreira da Silva.

### Passo #1: Escolhendo os dados

Acesse o portal brasileiro de dados abertos: http://dados.gov.br/ e escolha um *dataset*. Um dataset nada mais é que um conjunto de dados.

Neste tutorial vamos utilizar o Dataset de Investimento Publico - OGU - Valores Pagos.

![Página do Dataset]{![img](https://i.imgur.com/rf7LuZJ.png)}

Nesta mesma janela Possui informações dos recursos e dados. Escolha preferencialmente recursos em XLS ou CSV. Assim:

![Baixando o recurso](https://i.imgur.com/DkFWzWK.png)







Desta forma teremos o arquivo que iremos importar no *Pentaho Data Integration*.

#### Passo 2: A tela do ETL

Execute o Pentaho para iniciar a analise dos dados, voce pode baixa-lo gratuitamente em https://sourceforge.net/projects/pentaho/ . Ai instala-lo e executa-lo teremos a seguinte tela:

![Tela inicial do Pentaho](https://i.imgur.com/jRVgB3yg.png)

Nesta tela, na sessão de Work, selecione a opção New Transformation. E na aba lateral selecione na categoria de Input a forma de entrada, neste caso um CSV.

#### Passo 3: Importando os dados

![Selecionando uma entrada](https://i.imgur.com/o6qkQPB.png)



Apartir disso teremos a seguinte tela:

![Tela de Input](https://i.imgur.com/AxPZedM.png)

Aqui informe a fonte do arquivo. Poderá obter os campos automaticamente, neste caso não deu muito certo. Você pode ajustar de acordo com o formato do documento, você pode precisar entender seu conteudo antes.



#### Passo 5: Exportando os dados transformados

Na barra leteral na categoria de Output, escolha a forma de exportação dos dados. Nesta atividade foi recomendada os formatos JSON, XLS, TXT e XML. Assim:

![Exportando os dados](https://i.imgur.com/RE0vZTs.png)



Na tela seguinte basta escolher o destino e caso necessite, alterar algumas opções de exportação, e Finalizar com o botão "Ok".



Qualquer dúvida deixe nas Issues. ;)

# Metodologia de pesquisa científica

## Problema
Desde o inicío da abertura das bolsas de valores até os dias de hoje a especulação é um fator relevante nas oscilações dos preços de ativos/títulos de empresas que tem capital aberto. Porém tais especulações se devem à fatores que são divulgados em diversos meios de comunicação, o que torna difícil o estudo, a análise e por fim a tomada de decisão na hora de se investir no mercado financeiro.

## Motivação

Construir um bem sólido com base em investimentos em fundos, ações ou até mesmo títulos públicos não é um processo trivial. Muitas pessoas investem anos e anos de vida a fim de alcançar sua independência financeira. Um grande exemplo de pessoa que conseguiu este marco, é o investidor Warren Buffett, um investidor americano, filantrópico e CEO da Berkshire Hathaway. Um outro grande exemplo, um brasileiro, o investior Luiz Barsi também conhecido como o "rei da bolsa". Ambos iniciaram sua trajetória para alcançar a independência financeira através de investimentos na bolsa de valores.

A bolsa de valores é um ambiente de negociação de ações, fundos imobiliários, BDRs (Brazilian Depositary Receipts) entre outras tipos de investimentos na qual investidores podem comprar, vender e até mesmo alugar títulos emitidos por empresas. Neste ambiente, é possível encontrar empresas com capital público, privado ou misto. Todo o processo de negociação de títulos é intermediado através de corretoras. [Blog - BTG Pactual digital, 2018](https://www.btgpactualdigital.com/blog/investimentos/tudo-sobre-bolsa-de-valores)

Corretoras são intermediadoras e distribuidoras de ofertas e sua principal função é executar ordens de compra ou venda que seus clientes - investidores - solicitam. Corretoras também são responsáveis pela administração de fundos de investimentos na qual demandam maiores valores de aquisição, consequentemente riscos maiores. Esse administração, comumente é feita através de profissinais certificados. [BONA, 2016](https://andrebona.com.br/entendendo-o-mercado-financeiro-em-6-passos/)

Um dos tipos de ativos mais conhecidos entre os investidores, são as ações. Ações são "papéis", ou por assim dizer, a menor unidade dentro de uma companhia. Ao comprá-las, o investidor torna-se "sócio" de uma parcela da companhia em questão. Tornando-se proprietário dessa unidade, o investidor garante alguns direitos, como por exemplo, o direito ao voto em assembleias ou até mesmo a participação dos lucros das empresas, também conhecido como dividendos. [Blog - BTG Pactual digital, 2018](https://www.btgpactualdigital.com/blog/investimentos/tudo-sobre-bolsa-de-valores)

É importante ressaltar que a bolsa de valores é um ambiente com muitas especulações. Estas ajudam o valor de ativos se valorizarem ou desvalorizarem. Especulações se devem à diversos movimentos que as empresas tomam na sua gestão. Um exemplo, é quando uma empresa altamente endividada esteja prestes a receber uma oferta de aquisição de uma companhia maior e bem avaliada pelo mercado.

Dessa forma investidores especulam sobre o futuro da empresa e logo correm para iniciar suas negociações na bolsa.

A oscilação de ativos não se deve tão somente a especulação, mas também da saúde financeira, da gestão e dos resultados das empresas. [Blog - BTG Pactual digital, 2018](https://www.btgpactualdigital.com/blog/investimentos/tudo-sobre-bolsa-de-valores)

A negociação na bolsa envolve os investidores em alguns riscos. O primeiro deles é o chamado risco de liquidez. Basicamente é o risco do investidor não conseguir comprar ou vender seus ativos pois não há uma demanda e procura pelos ativos da companhia em questão. Devido a isso, é importante estar atento às tendências e movimentações no mercado antes de investir.

O outro risco é justamente a desvalorização de um ativo. Um exemplo, é que logo após o investidor fazer a aquisição de alguns ativos de uma companhia, a mesma apresentar fatores que impactam negativamente as suas atividades, assim sendo, desavalorizando os seus títulos. [Blog - BTG Pactual digital, 2018](https://www.btgpactualdigital.com/blog/investimentos/tudo-sobre-bolsa-de-valores)

Alguns dos principais eventos que levam à oscilação de ativos são, por exemplo, alguma notícia que impacta o mercado como um todo ou no setor que a companhia atua; alguma notícia envolvendos escândalos; divulgação de resultados e balanços; inteferências políticas, interferências ambientais; crises econômicas; crises sociais etc.

Hoje com o avanço dos meios de comunicação com foco nas redes sociais, as especulações contribuem ainda mais para as oscilações no mercado financeiro.

Por conta do grande número de pessoas nas redes sociais e da ascensão dos CASHTAGS, tornou-se muito fácil encontrar informações sobre o mercado financeiro ou determinada empresa.

Um estudo publicado no First Monday Journal a respeito do volume de Cashtags, relacionado à performance do segmento de ações das empresas Starbucks, TripAdivisor, Firt Solar e Netflix, observou que, em alguns casos, esses elementos estão, de fato, relacionados.

A partir da divulgação de notícias por parte das empresas, o valor das ações podem ser intensivamente afetados. Informações publicadas podem ser entendidas como fatos realmente relevantes, e o investidor utiliza-se disso como base para a tomada de decisão. [DIEGUES, 2019](https://propmark.com.br/opiniao/o-sentimento-nas-redes-sociais-e-o-impacto-no-mercado-financeiro/)

![Relação número de tweets e variação de preço de mercado](https://i0.wp.com/assets.propmark.com.br/uploads/2019/09/dd.png?w=737&ssl=1)

[Figura 1 - Relação número de tweets e variação de preço de mercado](https://propmark.com.br/opiniao/o-sentimento-nas-redes-sociais-e-o-impacto-no-mercado-financeiro/)

## Proposta de Solução

O trabalho em questão tem como proposta, utilizar algoritmos de inteligência artificial para desenvolver uma aplicação capaz de interpretar diversos textos presentes blogs. Com base nas interpretações, o algoritmo terá a capacidade de identificar e correlacionar notícias que podem caracterizar tendências de alta ou de queda nos valores de ações no mercado brasileiro de ações. Tanto quanto identificar, o objetivo final da aplicação é auxiliar o investidor na sua tomada de decisão. A inteligência artificial será treinada a partir de uma técnica conhecida como aprendizagem de máquinas. Serão utilizados diversos posts, artigos e notícias como input para o treinamento do modelo de inteligência da máquina. A solução será composta por uma aplicação responsável por "assistir" novas postagens em um blog, como MoneyTimes, e salvar todos os dados necessários. Estes dados serão passados para uma outra aplicação, podendo ser uma função lambda (Serverless) hospedado em um serviço de nuvem, por exemplo Amazon Comprehend da AWS, responsável por fazer o processamento dos dados que por fim indicará se tem relação com movimento de alta, de queda ou não há nenhuma relação.

## Referências

Bolsa de valores: o que é, como funciona e como investir. Blog - BTG Pactual digital, 2018. Disponível em: <https://www.btgpactualdigital.com/blog/investimentos/tudo-sobre-bolsa-de-valores>. Acesso em 23 de nov. 2020.

BONA, André. Entendendo o mercado financeiro em 6 passos. André Bona - Finanças e Investimentos, 2016. Disponível em <https://andrebona.com.br/entendendo-o-mercado-financeiro-em-6-passos/>. Acesso em 23 de nov. 2020.

DIEGUES, Mariana. O sentimento nas redes sociais e o impacto no mercado financeiro. PROPMARK, 2019. Disponível em: <https://propmark.com.br/opiniao/o-sentimento-nas-redes-sociais-e-o-impacto-no-mercado-financeiro/>. Acesso em 23 de nov. 2020.

## Interessante ler

[Compra e venda de ações: entenda por que o mercado oscila - Nelogica](https://blog.nelogica.com.br/compra-e-venda-de-acoes-entenda-por-que-o-mercado-oscila-2/)

[Veja como se manter atualizado sobre as questões que envolvem o mercado financeiro - Nelogica](http://blog.nelogica.com.br/veja-como-se-manter-atualizado-sobre-as-questoes-que-envolvem-o-mercado-financeiro/)

[O software para o mercado financeiro e sua importância para os traders - Nelogica](http://blog.nelogica.com.br/o-software-para-o-mercado-financeiro-e-sua-importancia-para-os-traders/)

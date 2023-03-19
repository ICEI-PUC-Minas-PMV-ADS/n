# Especificações do Projeto

Com os detalhes levantados nesse processo foram consolidados na forma de personas e histórias de usuários.

## Personas

| <img src="x" width="350" height="175"/> | Arnaldo Santos, 45 anos|
| ------------------------------------------------------------------------- | ------------------------------------------------------------------|
| Ocupação:                                                       | Cirurgião dentista, proprietário de uma Clínica cooperativa.                                                                                           |
| Aplicativos:                                                    | Instagram, Linkedin, G1, Amazon.                                                        |
| Motivações:                                                     | Avaliar o  consumo energético total da clínica; Entender quais equipamentos consomem mais energia; Efetuar trocas eficientes desses equipamentos.                    |       
| Frustrações:                                                    | Valor exorbitante das contas de energia; Não entender os valores finais na conta de energia; Não conseguir economizar;                                             |
| Hobbies, História:                                              | Gosta de pesquisar sobre novas; tecnologias e demandas do mercado;Política e economia.                                                        |

| <img src="https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-1-e2-proj-int-t4-pmv-ads-2023-1-e2-proj-int-t4-g2/blob/main/docs/img/persona2.jpg?raw=true" width="350" height="175"/> | Carlos Gomes, 36 anos|
| ------------------------------------------------------------------------- | ------------------------------------------------------------------|
| Ocupação:                                                       | Mestre de obras.                                                                                           |
| Aplicativos:                                                    | Whatsapp, Tik-Tok, Mercado Livre, Instagram  |
| Motivações:                                                     | Entender melhor sistemas elétricos e padrões de consumo; Construir imóveis com consumo eficiente; Propor análise entre estimativa e valores das contas para localizar problemas nas redes elétricas.|       
| Frustrações:                                                    | Dificuldade em catalogar seus gastos mensais com seu maquinário de trabalho e aparelhos residenciais; Uso de equipamentos antigos com alto custo energético; Desperdício de energia durante o dia.| 
| Hobbies, História:                                              | Gosta de buscar soluções inovadoras para a construção civil; Música; Pescaria. |

## Histórias de Usuários

A partir da compreensão do dia a dia das personas identificadas para o projeto, foram registradas as seguintes histórias de usuários.


|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Arnaldo Santos  | Conhecer o gasto de energia nos equipamentos da clínica. | Para que seja capaz de substituir os equipamentos se conveniente para economia de energia.|
|Arnaldo Santos  | Compreender melhor os gastos com energia.             | Para criar estratégias de economia; |
|Arnaldo Santos  | Prever o gasto anual. | Para dimensionar um sistema de produção de energia fotovoltaica.|
|Carlos Gomes | Analisar o perfil de consumo de seus clientes. | Para indicar instalação de painéis solares |
|Carlos Gomes | Estimar valores de sistemas fotovoltaicos. | Para recomendar aos seus clientes a instalação do sistema fotovoltaico.|
|Carlos Gomes | Comparar valores estimados e reais das contas.| Para detectar possíveis falhas na rede elétrica. |

## Requisitos de projeto

O escopo funcional do projeto é definido por meio dos requisitos funcionais que descrevem as possibilidades interação dos usuários, bem como os requisitos não funcionais que descrevem os aspectos que o sistema deverá apresentar de maneira geral. Estes requisitos são apresentados a seguir.


### Requisitos Funcionais
A tabela a seguir apresenta os requisitos do projeto, identificando a prioridade em que os mesmos devem ser entregues.

|ID    | Descrição do Requisito  | Prioridade         |
|------|-----------------------------------------|----|
|RF-001| O sistema deve permitir o cadastro de equipamentos e eletrodomésticos.s | ALTA  | 
|RF-002| O sistema permite a escolha do usuário entre perfil residencial ou empresarial   | MÉDIA |
|RF-003| O sistema deve apresentar de forma clara uma listagem de equipamentos eletroeletrônicos e sua média de consumo em KWH. | ALTA  | 
|RF-004| O sistema deve permitir ao usuário incluir o tempo de uso médio de cada equipamento ou eletrodoméstico em minutos;   | MÉDIA |
|RF-005| O sistema calcula valores a partir de consumo em KWH e o valor atual da concessionária; | MÉDIA | 
|RF-006| O sistema gera um relatório com estimativa de valores mensais de acordo com equipamentos eletroeletrônicos e eletrodomésticos utilizados pelo usuário.   | ALTA  |
|RF-007| A partir da média de consumo, o sistema apresenta uma tabela com os insumos necessários para implementação de um sistema fotovoltaico. | BAIXA | 
|RF-008| O sistema apresenta um catálogo de empresas parceiras onde o usuário pode solicitar orçamentos para compra do sistema fotovoltaico.   | BAIXA |
|RF-009| O sistema imprime valores com base na projeção do sistema fotovoltaico previamente feitos   | BAIXA |
|RF-010| O sistema gera um informativo sugerindo que o usuário realize a análise de valores reais e estimados pela aplicação, com o intuito de alertar ao cliente sobre possíveis problemas na rede elétrica ou em seus equipamentos eletroeletrônicos.   | BAIXA |

### Requisitos não Funcionais
A tabela a seguir apresenta os requisitos não funcionais que o projeto deverá atender.

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | ALTA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  ALTA | 
|RNF-003| Deve processar requisições do usuário em no máximo 3s |  MÉDIA | 
|RNF-004| Deve processar requisições do usuário em no máximo 3s |  ALTA | 

## Restrições

As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|RE-01| O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 19/03/2023. |
|RE-02| O aplicativo deve se restringir às tecnologias básicas da Web no Frontend e Backend.|
|RE-03| A equipe não pode subcontratar o desenvolvimento do trabalho.|


## Diagrama de Casos de Uso

COLOCAR IMAGEM AQUI DO DIAGRAMA

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 




# CONTROLE DE FARMÁCIA


**Julio dos Reis Firmino, jrfirmino@sga.pucminas.br**

**Eduardo Henrique Morais Costa, eduardo.costa.1187487@sga.pucminas.br**

**Hudson Suvalsky Vieira, hudson.suvalsky@sga.pucminas.br**

**Carlos Gabriel Campos Gaspar, carlos.gaspar.1429414@sga.pucminas.br**

**Jeziel Suzana Pires da Silva, jeziel.pires@sga.pucminas.br**


---

Professores:

**Juliana Amaral Baroni de Carvalho**

---

_Curso de Sistemas de Informação_

_Instituto de Informática e Ciências Exatas – Pontifícia Universidade de Minas Gerais (PUC MINAS), Belo Horizonte – MG – Brasil_

---

_**Resumo**. Este estudo busca desenvolver uma modelagem primária do processo de negócio farmacêutico, considerando a notável presença desse setor na sociedade. O objetivo é desenhar um fluxo eficiente e funcional, aplicando as regras de negócio ao contexto, embora sem se aprofundar nas peculiaridades de cada empresa, dada a sua diversidade.
Na proposta, todos os componentes dos processos de negócios são considerados, direcionando os recursos organizacionais para objetivos predefinidos. O cliente é o participante chave e a modelagem do processo é centrada em suas necessidades. Para a estruturação deste processo de negócio, a ferramenta SydleOne foi utilizada, permitindo uma modelagem eficiente e flexível._

---


## 1. Introdução

A introdução deve apresentar de dois ou quatro parágrafos de contextualização do trabalho. 

    1.1 Contextualização


Este trabalho tem por finalidade realizar a modelagem primária do processo de negócio de uma farmácia. Todo o estudo desenvolvido referente ao processo de negócio de uma farmácia foi trabalhado com foco no contexto desse tipo de negócio que está presente no cotidiano dos usuários. 
O objetivo é criar uma proposta de solução que viabiliza um fluxo de processos capaz de garantir eficiência e funcionalidade de uma empresa farmacêutica. A proposta irá entender e aplicar, dentro do contexto de modelagem de processos de negócios, as diversas regras de que envolvem esse tipo de atividade, ou seja, todo o fluxo será mapeado levando em consideração o início e o fim de todos os passos que deverão ser claramente mapeados.  
O trabalho se torna relevante quando consideramos os dados mais atualizados do Conselho Federal de Farmácia do Brasil (2021). A instituição relata que, em 2020 existiam 89.879 Farmácias e drogarias comerciais no Brasil. Além das 8.506 farmácias de manipulação, 6.771 farmácias hospitalares e 6.771 farmácias públicas. Todas as farmácias possuem processos que podem ser melhorados e agilizados, vide o propósito do trabalho.
Cabe ressaltar que o norteador desta atividade será as regras de negócios que representam as atividades essenciais para se alcançar os objetivos corporativos previamente definidos, contudo, cada instituição possui as suas particularidades culturais e adota as suas práticas específicas e tais medidas as tornam únicas em seu contexto empresarial, desta forma a modelagem em particular desses tipos de cases não será abordado nesse trabalho, tendo em vista a infinidade de empresas do ramo. 
Por fim o desenvolvimento da proposta considerou todos os componentes pertencentes aos processos de negócios, tais como: clientes externos e internos, fornecedores internos e externos, insumos e atividades. Toda a proposta baseou-se no objetivo primordial de orientar recursos organizacionais em direção a objetivos definidos e possibilitar que o mapeamento possa maximizar o retorno esperado que foi definido no âmbito corporativo. 

    1.2 Problema

Em seguida o aluno deve caminhar a contextualização para descrever o **problema** que o artigo trata. 
O **problema** pode ser algo vivido em uma empresa específica. Neste caso, o aluno deve rapidamente apresentar 
o cenário de problema da empresa. A empresa só deve ser citada explicitamente se o aluno tiver autorização 
para tal.

    1.3 Objetivo geral

Como objetivo geral do sistema temos a facilitação do processo de integração entre os consumidores e revendedores no setor farmacêutico. Auxiliando a partir de um sistema na compra, venda e organização de medicamentos de acordo com oferta e demanda. 
Em relação aos objetivos específicos do sistema, temos a possibilidade de visualização do histórico e periodicidade de compra dos produtos, assim como o auxílio no controle de estoque a partir da segmentação dos medicamentos por validade e lote. 

        1.3.1 Objetivos específicos

Viabilizar um fluxo de processos capaz de garantir eficiência e funcionalidade de uma empresa farmacêutica. A proposta irá entender e aplicar, dentro do contexto de modelagem de processos de negócios, as diversas regras de que envolvem esse tipo de atividade, ou seja, todo o fluxo será mapeado levando em consideração o início e o fim de todos os passos que deverão ser claramente mapeados.

    1.4 Justificativas

O setor farmacêutico no Brasil é um dos mais importantes do país, e é indiscutível que a tecnologia e a inovação são essenciais para o desenvolvimento do setor, sendo necessário que as farmácias estejam sempre atualizadas com as últimas tecnologias e sistemas de informação para gerenciar seus estoques e prestar atendimento ao cliente. 
Porém, muitas vezes os processos fundamentais para o funcionamento de um serviço não são bem mapeados, com deficiência nos processos básicos como controle de estoque e atendimento ao cliente. Portanto, com soluções e controles simples, mas eficazes, podemos resolver uma série de desafios e problemas na operação diária de uma farmácia e na compra de medicamentos por parte de clientes. 


## 2. Participantes do processo

- **Fornecedores:** São empresas ou pessoas que fornecem os medicamentos e outros produtos vendidos pela farmácia, quando os fornecedores são confiáveis no seu tempo de entrega e recebimento garantirão um bom fluxo de produtos na farmácia. Além disso ajuda a manter um estoque diversificado e atualizado, com produtos de qualidade e preços acessíveis. 
- **Farmacêuticos e Técnicos de farmácia:** Profissionais que trabalham em conjunto para interpretar receitas médicas, preparar medicamentos, dispensar medicamentos, dar orientações aos clientes, fornecer informações sobre medicamentos, gerenciar estoques físicos, agir na organização da farmácia e no atendimento ao cliente. 
- **Funcionários administrativos:** São os funcionários que gerenciam as atividades administrativas e financeiras da farmácia, como contabilidade, recursos humanos e gestão de estoques no sistema. 
- **Clientes:** São os participantes chave que vão comprar medicamentos e produtos na farmácia. Eles podem ser pacientes que precisam de medicamentos prescritos por um médico, ou podem ser clientes que procuram produtos de cuidados pessoais, suplementos alimentares, entre diversos outros. 

## 3. Modelagem do processo de negócio

## 3.1. Análise da situação atual

Apresente uma descrição textual de como os sistemas atuais resolvem o problema que se propoe a resolver.  Caso sua proposta seja inovadora e não existam processos claramente definidos, **apresente como as tarefas que o seu sistema pretende implementar são executadas atualmente**, mesmo que não se utilize tecnologia computacional.

## 3.2. Descrição Geral da proposta

Apresente aqui uma descrição da sua proposta abordando seus limites e suas ligações com as estratégias e objetivos do negócio. Apresente aqui as oportunidades de melhorias.

## 3.3. Modelagem dos Processos

### 3.3.1 Processo 1 – PROCESSO DE CADASTRO DE CLIENTES

Apresente aqui o nome e as oportunidades de melhorias para o processo 1. Em seguida, apresente o modelo do processo 1, descrito no padrão BPMN.

![Exemplo de um Modelo BPMN do PROCESSO 1](imagens/process.png "Modelo BPMN do Processo 1.")


### 3.3.2 Processo 2 – PROCESSO DE CADASTRO DE PRODUTOS

Apresente aqui o nome e as oportunidades de melhorias para o processo 2. Em seguida, apresente o modelo do processo 2, descrito no padrão BPMN.

![Exemplo de um Modelo BPMN do PROCESSO 2](imagens/call_process.png "Modelo BPMN do Processo 2.")

### 3.3.3 Processo 3 – PROCESSO DE VENDAS

Apresente aqui o nome e as oportunidades de melhorias para o processo 2. Em seguida, apresente o modelo do processo 2, descrito no padrão BPMN.


## 4. Projeto da Solução

### 4.1. Detalhamento das atividades

Descrever aqui cada uma das propriedades das atividades de cada um dos processos. Devem estar relacionadas com o modelo de processo apresentado anteriormente.

#### Processo 1 – NOME DO PROCESSO

**Nome da atividade 1**

| **Campo** | **Tipo** | **Restrições** | **Valor default** |
| --- | --- | --- | --- |
| [Nome do campo] | [Área de texto, Caixa de texto, Número, Data, Imagem, Seleção única, Múltipla escolha, Arquivo, Link, Tabela] |  |  |
| ***Exemplo:***  |    |     |
| login | Caixa de Texto | formato de e-mail |  |
| senha | Caixa de Texto | mínimo de 8 caracteres |   |

**Nome da atividade 2**

| **Campo** | **Tipo** | **Restrições** | **Valor default** |
| --- | --- | --- | --- |
| [Nome do campo] | [Área de texto, Caixa de texto, Número, Data, Imagem, Seleção única, Múltipla escolha, Arquivo, Link, Tabela] |  |  |
|    |    |     |

#### Processo 2 – NOME DO PROCESSO

**Nome da atividade 1**

| **Campo** | **Tipo** | **Restrições** | **Valor default** |
| --- | --- | --- | --- |
| [Nome do campo] | [Área de texto, Caixa de texto, Número, Data, Imagem, Seleção única, Múltipla escolha, Arquivo, Link, Tabela] |  |  |
|    |    |     |

**Nome da atividade 2**

| **Campo** | **Tipo** | **Restrições** | **Valor default** |
| --- | --- | --- | --- |
| [Nome do campo] | [Área de texto, Caixa de texto, Número, Data, Imagem, Seleção única, Múltipla escolha, Arquivo, Link, Tabela] |  |  |
|    |    |     |

### 4.2. Tecnologias

O projeto foi desenvolvido com o uso da ferramenta **SYDLE ONE** no qual foi realizado o mapeamento de processos e a automação.

## 5. Modelo de dados

Apresente o modelo de dados por meio de um modelo relacional ou Diagrama de Entidade-Relacionamento (DER) que contemple todos conceitos e atributos apresentados item anterior. 

![Diagrama de Entidade Relacionamento de Exemplo](imagens/er_diagram.png "Diagrama de Entidade Relacionamento de Exemplo")

![]("C:\Users\Julio\Downloads\der_puc.pdf")

## 6. Indicadores de desempenho

Apresente aqui os principais indicadores de desempenho e algumas metas para o processo. Atenção: as informações necessárias para gerar os indicadores devem estar contempladas no diagrama de classe. Colocar no mínimo 5 indicadores.

Usar o seguinte modelo:

| **Indicador** | **Objetivos** | **Descrição** | **Cálculo** | **Fonte dados** | **Perspectiva** |
| --- | --- | --- | --- | --- | --- |
| Percentual reclamações | Avaliar quantitativamente as reclamações | Percentual de reclamações em relação ao total atendimento |   | Tabela reclamações | Aprendizado e Crescimento |
| Taxa de Requisições abertas | Melhorar a prestação de serviços medindo a porcentagem de requisições | Mede % de requisições atendidas na semana | ![\frac{\sum{atendidas}}{\sum{requisicoes}}100](https://latex.codecogs.com/svg.latex?\frac{\sum{atendidas}}{\sum{requisicoes}}100) | Tabela solicitações | Processos internos |
| Taxa de entrega de material | Manter controle sobre os materiais que estão sendo entregues | Mede % de material entregue dentro do mês |   | Tabela Pedidos | Clientes |

Obs.: todas as informações para gerar os indicadores devem estar no diagrama de classe **a ser proposto**

## 7. Sistema desenvolvido

Faça aqui uma breve descrição do software e coloque as principais telas com uma explicação de como usar cada uma.

## 8. Conclusão

Apresente aqui a conclusão do seu trabalho. Discussão dos resultados obtidos no trabalho, onde se verifica as observações pessoais de cada aluno. Poderá também apresentar sugestões de novas linhas de estudo.

# REFERÊNCIAS

Como um projeto de software não requer revisão bibliográfica, a inclusão das referências não é obrigatória. No entanto, caso você deseje incluir referências relacionadas às tecnologias, padrões, ou metodologias que serão usadas no seu trabalho, relacione-as de acordo com a ABNT.

Verifique no link abaixo como devem ser as referências no padrão ABNT:

http://www.pucminas.br/imagedb/documento/DOC\_DSC\_NOME\_ARQUI20160217102425.pdf


**[1.1]** - _ELMASRI, Ramez; NAVATHE, Sham. **Sistemas de banco de dados**. 7. ed. São Paulo: Pearson, c2019. E-book. ISBN 9788543025001._

**[1.2]** - _NIELD, Thomas. **Getting Started with SQL**. A Hands-on Approach forBeginners. Sebastopol: O’Reilly, 2016. Capítulos 1 e 2. LivroEletrônico._

**[1.2]** - _COPPIN, Ben. **Inteligência artificial**. Rio de Janeiro, RJ: LTC, c2010. E-book. ISBN 978-85-216-2936-8._

**[1.3]** - _CORMEN, Thomas H. et al. **Algoritmos: teoria e prática**. Rio de Janeiro, RJ: Elsevier, Campus, c2012. xvi, 926 p. ISBN 9788535236996._

**[1.4]** - _SUTHERLAND, Jeffrey Victor. **Scrum: a arte de fazer o dobro do trabalho na metade do tempo**. 2. ed. rev. São Paulo, SP: Leya, 2016. 236, [4] p. ISBN 9788544104514._

**[1.5]** - _RUSSELL, Stuart J.; NORVIG, Peter. **Inteligência artificial**. Rio de Janeiro: Elsevier, c2013. xxi, 988 p. ISBN 9788535237016._



# APÊNDICES

**Colocar link:**

Do código (armazenado no repositório);

Dos artefatos (armazenado do repositório);

Da apresentação final (armazenado no repositório);

Do vídeo de apresentação (armazenado no repositório).





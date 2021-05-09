
![Apenas 1 dose bastaria?](https://github.com/lucasnascm/imersao-dados-desafio-final/blob/main/Imagens/dose.png?raw=true)

Como já cantava Paralamas, (...) bastaria, ah meu Deus era tudo que eu queria! 

## **Drug Discovery**

Cada vez mais, as ferramentas computacionais têm auxiliado a busca por causalidade na medicina. O processo de Drug Discovery através de Machine Learning busca predizer se há ação em princípios ativos dependendo da informação genética que temos como variáveis em nossa base de dados. Na última semana (3 a 7 de maio de 2021) conhecemos um pouco sobre os desafios da área de bioinformática na Imersão Dados promovida pela Alura. Como desafio final e pensando não só no árduo processo que é a busca por informações genéticas, **a minha hipótese vem tentando entender se apenas com 1 dose para células tratadas seria possível resultados satisfatórios e assim economizar tempo e recursos**.

## **Dados**
Para melhor entender os dados, eis aqui um resumo:
id: identificação exclusiva da cultura celular;
tratamento: indica se a cultura celular recebeu o tratamento ou se funcionou como controle;
tempo: período de 24h, 48h ou 72h em que o tratamento foi administrado;
dose: indica o nível de tratamento recebido, baixa ou alta dose, D1 e D2, respectivamente;
droga: composto a ser estudado. Excluindo o composto placebo, a base contém mais de três mil tipos analisados;
g0-g771: estruturas gênicas que trazem informações relativas ao RNA da célula;
c0-99: viabilidade celular, que é a razão de células viáveis pelo total de células de cada cultura;

Ainda temos a base que especifica cada mecanismo de ação que foi ativado em cada cultura. É a partir destas observações que a nossa base fica completa e podemos predizer os resultados, com base na forma como cada estrutura gênica e de viabilidade celular se comportam frente as características de tempo, dose e composto.


## **Desafio**
Em cada aula era introduzido um conceito diferente e uma perspectiva para a base de dados que tínhamos. Durante a aula de Machine Learning introduzidos, a gente analisava os modelos preditivos em torno de uma variável binária para entender o quão bom era aquele modelo em definir se cada observação da nossa base de dados, com base nas expressões gênicas e de viabilidade celular, ativava um mecanimos de ação. A minha proposta aqui, no intuito de maximizar o uso dos recursos disponíveis na pesquisa, é identificar se a acurácia de modelos preditivos para a base com apenas informações da dose baixa (D1) seria inferior em relação a base de dados completa ou ainda possuiria muitas diferenças com relação a base de dados que só trouxesse informações de D2. No notebook disponível no Colab, analisamos inicialmente a base de dados, fornecendo uma análise descritiva de cada uma delas e rodamos quatro modelos preditivos para verificar se acurácia dos testes sob diferentes especificações de dados se altera significativamente em relação as bases. 
Sabemos que todo este processo, até ser validado para etapas futuras no desenvolvimento de novos fármacos necessita de muita experimentação e comprovação, com metodologias mais aprofundadas e parâmetros melhor estabelecidos.

## **Contato**
Lucas Moreira
lucas.nasc.m@gmail.com
https://www.linkedin.com/in/moreiranlucas/

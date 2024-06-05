Aja como um desenvolvedor de software especialista em banco de dados Oracle, e que também saiba muito bem sobre arquivos de dados em JSON. 
Sua tarefa é criar um JSON (sempre um array de objetos) com base nos dados fornecidos pelo usuário. Siga as etapas abaixo para solicitar e gerar o JSON:

Definições:
{{REGISTROS}} = 9

Etapas
Pergunte ao usuário os valores ou faixas de valores para cada um dos seguintes atributos:

IPO_IDUSER: Código alfanumérico de 6 posições. Exemplo de faixa: "001567" a "001699".
IPO_PROC: Valor fixo para todos os registros. Exemplo: "MNTACE".
IPO_VRPTOC: Valor fixo para todos os registros. Exemplo: "001".
R_E_C_N_O_: Numeração inteira sequencial, começando de um valor definido pelo usuário. Exemplo: 1000 a 1004.
D_E_L_E_T_: Valor fixo para todos os registros. Exemplo: " ".
Gere 5 registros hipotéticos de exemplo usando os valores ou faixas fornecidas pelo usuário.

Solicitação
Pergunte ao usuário:

Qual é a faixa de valores para IPO_IDUSER? (Forneça um exemplo de faixa: "001567" a "001699")
Qual é o valor fixo para IPO_PROC? (Forneça um exemplo: "MNTACE")
Qual é o valor fixo para IPO_VRPTOC? (Forneça um exemplo: "001")
Qual é a faixa de valores para R_E_C_N_O_? (Forneça um exemplo: 1000 a 1004)
Confirme que o valor para D_E_L_E_T_ é sempre " " (espaço em branco).
JSON de Exemplo
Use os valores fornecidos pelo usuário para criar o JSON com {{REGISTROS}} registros. O formato do JSON deve ser semelhante ao seguinte:


===========================================================================================================================


Ótimo. Converta isso para um script Oracle que faça essas exatas inclusões em uma tabela IMPORTA_IPO. As colunas são as propriedades desse JSON exemplo como você forneceu. 
Porém, entenda que eu gostaria na verdade da relação de todos os INSERT, e não uma função com DECLARE, etc.



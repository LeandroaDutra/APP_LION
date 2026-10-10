# APP_LION
Um app que auxilia a fazer a sua declaração de Imposto de renda
la funciona como um simulador para organizar informações da pessoa física, reunir rendimentos e despesas e estimar o Imposto de Renda anual, indicando se há imposto a pagar ou restituição.
O arquivo possui oito abas principais. Veja como utilizar cada uma.

1. Abra o arquivo e confira as abas
TITULAR
Cadastro da pessoa que fará a apuração.
INFORMES
Saldos informados pelas instituições financeiras.
NOTAS
Entradas de dinheiro e rendimentos ao longo do ano.
PAGAMENTOS
Despesas, deduções informadas e imposto já retido ou pago.
RESUMO
Consolidação dos valores e estimativa do imposto.

Importante: a planilha contém dados pessoais e valores de exemplo já preenchidos. Antes de utilizá-la, substitua-os pelos seus dados e não compartilhe o arquivo com informações pessoais de terceiros.
Ela contêm TABELAS, TABELA_IR e REDUÇÃO LEGAL, listas de bancos e parâmetros usados nos cálculos.

2. Preencha a aba TITULAR
Abra a aba TITULAR e revise os campos:
1. Nome completo.
2. CPF.
3. Data de nascimento.
4. Título de eleitor, se aplicável ao cadastro.
5. Nome do cônjuge, quando houver.
6. Endereço, CEP e telefone.
7. Celular e e-mail.
8. Indicação de alterações em relação à declaração anterior.
9. Indicação de dependência do cônjuge.
10. Quantidade de dependentes.
11. Indicação de residência no exterior.
Digite as informações nas células correspondentes, mantendo os títulos e a estrutura da planilha.
Atenção: confira especialmente a quantidade de dependentes. Ela é utilizada no cálculo da base tributável. Informe somente dependentes que atendam às regras fiscais aplicáveis.

<img width="1216" height="592" alt="image" src="https://github.com/user-attachments/assets/96b3a835-aa68-49c3-a2a3-3875dbeff6cf" />

3. Preencha a aba INFORMES
Essa aba registra os saldos informados pelos bancos e instituições financeiras.
Para cada instituição:
1. Selecione ou informe o banco.
2. Digite o valor correspondente ao campo VALOR ATUAL, conforme o informe de rendimentos.
3. Registre o nome do arquivo do informe no campo ANEXO, para facilitar a conferência dos documentos.
4. Repita o procedimento para os demais bancos.
A célula TOTAL soma os valores das instituições cadastradas.
Exemplo ilustrativo:
Instituição	  Saldo informado
Banco A	      R$ 8.000,00
Banco B      	R$ 12.000,00
Banco C      	R$ 5.000,00
Total	        R$ 25.000,00
Os saldos bancários não devem ser confundidos com rendimentos tributáveis. Na declaração oficial, cada informação precisa ser classificada corretamente conforme o informe da instituição.

<img width="1220" height="603" alt="image" src="https://github.com/user-attachments/assets/ecd55421-1e69-436d-9d90-4e45967b4cf0" />

4. Preencha a aba NOTAS
Essa aba registra as entradas de dinheiro durante o ano.
A planilha apresenta as colunas:
- DATA: dia em que recebeu o valor.
- CATEGORIA: origem do recebimento.
- VALOR: quantia recebida.
  
Exemplo:
Data	      Categoria	Valor
10/02/2026	Salário	R$ 5.000,00
15/04/2026	Serviço autônomo	R$ 2.000,00
20/06/2026	Outros rendimentos	R$ 800,00
Na sua planilha, as categorias de exemplo incluem HOLERITE, FREELANCE e CNPJ.
Como usar: inclua cada recebimento na linha correspondente e adicione novas linhas à tabela quando necessário. O total é calculado automaticamente pela fórmula existente na aba.
Atenção: recebimentos de salário, serviços, rendimentos bancários e valores provenientes de um CNPJ não possuem necessariamente o mesmo tratamento tributário. Não some tudo como se fosse renda tributável sem antes classificar a origem e verificar a documentação.

<img width="942" height="532" alt="image" src="https://github.com/user-attachments/assets/bf9e05e2-689d-450a-b04d-0ea1b230486f" />

5. Preencha a aba PAGAMENTOS
Essa aba reúne saídas de dinheiro e informações que podem ser relevantes para a apuração.
Na tabela, informe:
- DATA: data do pagamento.
- CATEGORIA: tipo de despesa ou pagamento.
- JUSTIFICATIVA: descrição do gasto.
- VALOR: quantia paga.
  
Exemplo:
Data	      Categoria	      Justificativa	  Valor
10/02/2026	Previdência	    Contribuição	  R$ 300,00
15/04/2026	Instrução	      Curso	          R$ 1.500,00
20/06/2026	Saúde	          Despesa médica	R$ 800,00
A planilha também tem um campo separado chamado PAGAMENTO DO IRRF ANUAL.
Muito importante: nem toda despesa pessoal pode ser deduzida do Imposto de Renda. Despesas com instrução, previdência e saúde, por exemplo, possuem regras, limites e condições específicas. O valor pago não deve ser automaticamente considerado dedutível. Confira também se o imposto informado nesse campo corresponde ao imposto efetivamente retido ou pago e se não está sendo contabilizado duas vezes.

<img width="1067" height="530" alt="image" src="https://github.com/user-attachments/assets/e0913140-e176-48b9-93bd-23750c1b707c" />

6. Confira a aba RESUMO
Essa é a principal aba do aplicativo. Ela reúne informações das outras abas e apresenta a estimativa do resultado.
Como interpretar o resumo:
Total referenciado
Consolida os valores das abas INFORMES, NOTAS e PAGAMENTOS. Confira se cada valor está classificado corretamente antes de interpretar o resultado.

<img width="1362" height="532" alt="image" src="https://github.com/user-attachments/assets/3fd2af86-c4d8-4a9e-8d97-447696f9507f" />

Apuração da base
A planilha calcula os rendimentos considerados, aplica uma lógica de deduções e estima a base de cálculo do imposto.
Apuração do imposto devido
Apresenta a base de cálculo, a alíquota, a parcela a deduzir e o imposto estimado após a redução anual prevista na fórmula.
Imposto a pagar ou restituir
Compara o imposto calculado com o valor registrado como imposto já retido, para indicar um possível saldo.
Em princípio, o resultado final deverá ser interpretado assim:
- IMPOSTO A PAGAR: o imposto calculado supera o valor já considerado como pago ou retido.
- RESTITUIÇÃO: o valor já pago ou retido supera o imposto calculado.
- SEM SALDO: os valores considerados são iguais.
O resultado é uma estimativa da planilha, não uma confirmação oficial da Receita Federal.
7. Entenda as abas de tabelas
As outras três abas ajudam a alimentar os cálculos:
- TABELAS: lista de instituições financeiras usada para facilitar o preenchimento.
- TABELA_IR: contém faixas de base de cálculo, alíquotas e parcelas a deduzir.
- REDUÇÃO LEGAL: contém valores e limites de dedução e parâmetros de redução utilizados nas fórmulas.
Não altere essas tabelas sem confirmar o ano-calendário, a legislação aplicável e as fórmulas que dependem delas. A mudança de um valor pode alterar todo o resultado.
8. Atualize os cálculos e confira os documentos
Após preencher as abas:
1. No Excel, abra Fórmulas → Opções de Cálculo → Automático.
2. Pressione Ctrl + Alt + F9 para forçar o recálculo das fórmulas.
3. Retorne à aba RESUMO.
4. Confira se os totais correspondem aos valores registrados nas demais abas.
5. Compare os dados com informes bancários, comprovantes de rendimentos e documentos de despesas.
6. Confira se a tabela tributária corresponde ao ano correto antes de utilizar o resultado.

Baixe o arquivo e use conforme precisar
Obs: Os dados informados são todos fictícios.
[Declarador de IRRF.xlsx](https://github.com/user-attachments/files/33291667/Declarador.de.IRRF.xlsx)

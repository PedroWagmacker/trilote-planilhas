
# 📋 Planilhas de Importação

Bem-vindo ao repositório das planilhas de importação. Aqui você encontra a documentação e os arquivos necessários para realizar a importação de dados na plataforma.

---

## 📦 Unidades

*Planilha de importação de unidades.*

Uma breve instrução para realizar o preenchimento:
Na planilha temos algumas colunas em que os preenchimentos são obrigatórios para que a importação seja realizada. Sendo elas:

- unidade_empreendimento;
- unidade_quadra;
- unidade_numero;
- unidade_situacao;
- unidade_tipo;
- unidade_area;
- unidade_valor;

Ao passar o cursor do mouse 🖱️ em cada coluna, uma descrição será exibida com as instruções de preenchimento.

> ⚠️ Se o empreendimento for do tipo *"Condomínio de lote"*, *"Multipropriedade"*, *"Condomínio de casas"* ou *"Condomínio vertical"*, é necessário preencher a coluna `unidade_fracao_ideal`.

🔗 [Acessar planilha de importação de unidades](Planilhas_importação)

---

## 👥 Clientes

*Planilha de importação de clientes.*

Uma breve instrução para realizar o preenchimento:
Na planilha temos algumas colunas em que os preenchimentos são obrigatórios para que a importação seja realizada. Sendo elas:

- cliente_cpfcnpj;
- cliente_telefone_tipo_1;
- cliente_telefone_numero_1;
- cliente_endereco_cep;
- cliente_endereco_logradouro;
- cliente_endereco_numero;
- cliente_endereco_bairro;
- cliente_endereco_cidade;
- cliente_endereco_uf;

Ao passar o cursor do mouse 🖱️ em cada coluna, uma descrição será exibida com as instruções de preenchimento.

> ⚠️ Caso o cliente seja uma *pessoa jurídica*, o preenchimento do campo `cliente_nome_fantasia` também se torna obrigatório.

🔗 [Acessar planilha de importação de clientes](Planilhas_importação)

---

## 📄 Contratos

*Planilha de importação de contratos.*

Uma breve instrução para realizar o preenchimento:
Na planilha temos algumas colunas em que os preenchimentos são obrigatórios para que a importação seja realizada. Sendo elas:

- numero_contrato;
- data_emissao;
- empreendimento_descricao;
- unidade_quadra;
- unidade_numero;
- valor_unidade;
- valor_desconto;
- valor_venda;
- cliente_cpfcnpj;
- tipo_contrato;
- indexador_monetario;
- taxa_multa_atraso;
- taxa_juros_atraso;
- atualizacao_monetaria;
- taxa_juros_financiamento;
- sistema_amortizacao;

Ao passar o cursor do mouse 🖱️ em cada coluna, uma descrição será exibida com as instruções de preenchimento.

> ⚠️ Sempre que o campo `intermediador_cpfcnpj` for informado, os campos `intermediador_nome` e `intermediador_valor` também se tornam *obrigatórios*. Caso o intermediador seja uma pessoa jurídica, o campo `vendedor_cpf` é igualmente obrigatório.

🔗 [Acessar planilha de importação de contratos](Planilhas_importação)

---

## 💰 Parcelas dos Contratos

*Planilha de importação de parcelas dos contratos.*

Uma breve instrução para realizar o preenchimento:
Na planilha temos algumas colunas em que os preenchimentos são obrigatórios para que a importação seja realizada. Sendo elas:

- contrato_numero;
- empreendimento_descricao;
- unidade_quadra;
- unidade_numero;
- parcela_numero;
- parcela_tipo;
- parcela_valor_face;
- parcela_valor_pago;
- parcela_data_vencimento;
- parcela_situacao;

Ao passar o cursor do mouse 🖱️ em cada coluna, uma descrição será exibida com as instruções de preenchimento.

> ⚠️ Caso a parcela esteja com situação *LIQUIDADA*, os campos `parcela_valor_encargos`, `parcela_data_pagamento` e `parcela_conta_liquidacao` também se tornam *obrigatórios*.

🔗 [Acessar planilha de importação de parcelas](Planilhas_importação)

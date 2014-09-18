Módulo desenvolvido pela Lema21 para integrar com o sistema do Bling e gerar notas fiscais.

Para o funcionamento do módulo é preciso criar os seguintes atributos de produto na munheca (sim, nao está automatizado a criacao dos atributos)

<b>Campos Obrigatórios</b>

- codigo_origem (codigo de origem do produto)
- opertion_name (espécie de 'nome operacional' do produto)
- operation_unit - unidade de medida, se é "PÇ", "KG"
- codigo_ncm - Código NCM do produto

<b>Outros Campos</b>
- gtin
- gtin_embalagem

Melhorias no módulo:

- incluída opção para emissão de Nf-e em massa para pedidos;
- incluída opção para permitir a emissão de Nf-e por estado do(s) pedidos;
- validação para produtos que não possuem os atributos requeridos
- alteração das mensagens de sucesso e erro para exibir o número de incrementId do objeto order;
- inclusão automática dos atributos de nfe no grupo default do magento como não obrigatórios
- Retirado validações desnecessárias.
- Alteração na nomenclatura dos rótulos da guia Nf-e em produtos.
- Adicionado tipo de integração e numero pedido loja.
- Adicionado código gtin e gtin embalagem.


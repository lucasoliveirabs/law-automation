- Domínio: compra/venda de imóvel
- Subdomínios:
	1. Negociação, Criação de Contrato e de autorização do cliente
	
	a) Geração de Procuração Eletrônica + integração assinatura gov.br do cliente + assinatura gov.br do advogado
	b) Input: detalhes gerais do acordo, endereço completo*, nome e CPF proprietário

	2. Consulta de Situação Jurídica do Imóvel (revisar detalhes de cada tópico em documentação)
	
	https://registradores.onr.org.br/ServicosOnline.aspx
	https://www.registrodeimoveis.org.br/intranet/arquivos/upload/geral/999999_upload_de_arquivos_geral_20230906_144922_7926cdd0-fda3-4122-8b8c-c408c7c708f1.pdf
		
	a) Coleta de Parâmetros
	+ Consulta de número de matrícula/registro de imóvel (registro de imoveis)
		1. Pagamento: FALSE
		2. Parâmetros legais: endereço completo, nome proprietário
		3. Requerente necessário: advogado
		
	+ Consulta de número de número de inscrição de imóvel
		1. Pagamento: 
		2. Parâmetros legais: 
		3. Requerente necessário: advogado	
	
	b) Coleta de Documentos
	
	Visualização de Matrícula (conferir)
	+ Consulta de Matrícula Atualizada do Imóvel
		1. Pagamento: TRUE
		2. Parâmetros legais: número de matrícula, endereço completo, nome proprietário
		3. Requerente necessário: advogado
	
	Certidão Digital/Pesquisa Qualificada
	+ Certidão Negativa de Débito IPTU (site da prefeitura) - débitos de impostos: 
		1. Pagamento: TRUE
		2. Parâmetros legais: número inscrição imóvel, endereço completo, nome proprietário, CPF proprietário
		3. Requerente necessário: advogado 
		
	Certidão Digital/Pesquisa Qualificada (conferir)
	+ Certidão de Ônus Reais (registro de imoveis) - gravames e dívidas gerais:
		1. Pagamento: TRUE
		2. Parâmetros legais: número de matrícula, endereço completo, nome proprietário
		3. Requerente necessário: advogado
		
	c) Verificação/Validação de documentos coletados
	
	3. Consulta, verificação e validação de Documentos do Vendedor
		- Certidão de Distribuidores Cível (tribunal de justiça do estado), 
		- Certidão da receita federal (site receita federal), 
		- Certidão negativa de protesto (cartório de protesto), 
		- Certidão negativa de débitos trabalhistas (tribunal reginal do trabalho, tribunal superior do trabalho), 
		- Certidão da justiça federal (trf do estado))
		a) Parâmetros
		b) Documentos
		c) Verificação/Validação de documentos coletados
	
	4. Pagamento e transferência do Imóvel
	

---
	
*(Logradouro (rua, avenida, travessa, etc.), Número, Bairro, Cidade, Estado, CEP) ou lote

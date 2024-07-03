# desafio_de_codigo_Sagemaker_Canvas_1

Descrição

Dentre os benefícios do SageMaker Canvas, constam: ML sem código, modelos de base prontos para uso, suporte ao ciclo de vida completo do ML e o impulsionamento da colaboração entre analistas de negócios e equipes de ciência de dados.
Com base nisso, complete o código deste desafio, associando os benefícios do SageMaker Canvas com suas respectivas descrições.

Saiba mais em: Amazon SageMaker Canvas.
Entrada

A entrada consiste no benefício do SageMaker Canvas para o qual você deve retornar a descrição. Neste contexto, os seguintes benefícios são considerados válidos para este desafio de código:

    "ML sem código"
    "Modelos de base prontos para uso"
    "Suporta todo o ciclo de vida do ML"
    "Impulsiona a colaboração"

Saída

A saída esperada é a descrição associada ao benefício fornecido como entrada. Seguem as saídas possíveis, listadas aleatoriamente, para que você possa analisar e associar corretamente:

    "Suporte a todo o ciclo de vida do Machine Learning"
    "Todos os modelos criados podem ser compartilhados"
    "Interface visual intuitiva e simples"
    "Acesso a Modelos de base (FMs) prontos para uso"

Exemplos

A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.
Entrada 	Saída
Suporta todo o ciclo de vida do ML 	Suporte a todo o ciclo de vida do Machine Learning
Impulsiona a colaboração 	Todos os modelos criados podem ser compartilhados
ML sem código 	Interface visual intuitiva e simples

Atenção: É extremamente importante que as entradas e saídas sejam exatamente iguais às descritas na descrição do desafio de código.
O código deverá seguir a seguinte estrutura 
# Recebe a Entrada do usuário e armazena na variável "entrada"
entrada = input()

# Função responsável por receber um beneficio e retornar sua respectiva descrição.
def descrever_beneficio(beneficio):
	if beneficio == "Suporta todo o ciclo de vida do ML":
			return "Suporte a todo o ciclo de vida do Machine Learning"
			
	# TODO: Preencha corretamente a descrição de cada beneficio, considerando as condições abaixo e Saídas possíveis:		
	elif beneficio == "":
	    return "Todos os modelos criados podem ser compartilhados"
	    
	elif beneficio == "":
	    return "Interface visual intuitiva e simples"
     

   # desafio_de_codigo_Sagemaker_Canvas_2

     Descrição

O Amazon SageMaker Canvas é uma ferramenta poderosa que democratiza o uso de machine learning, permitindo que analistas de negócios sem conhecimento técnico em ML criem modelos preditivos. Com ele, é possível prever a rotatividade de clientes, extrair informações de documentos, gerar conteúdo de vendas e marketing entre outros casos de uso. 
Nesse contexto, complete o código deste desafio, associando os casos de uso do SageMaker Canvas com suas respectivas descrições.

Saiba mais em: Amazon SageMaker Canvas.
Entrada

A entrada consiste em um caso de uso do SageMaker Canvas para o qual você deve retornar a descrição. Neste contexto, os seguintes casos são considerados válidos para este desafio de código:

    "Gerar conteúdo de vendas e marketing"
    "Resumir o conteúdo"
    "Extrair informações de documentos"
    "Prever a rotatividade de clientes"
    "Planejar o inventário com eficiência"

Saída

A saída esperada é a descrição associada ao caso de uso fornecido como entrada. Seguem as saídas possíveis, listadas aleatoriamente, para que você possa analisar e associar corretamente:

    "Produza resumos concisos com as informações mais importantes"
    "Crie conteúdo de vendas e marketing personalizado"
    "Preveja os níveis do inventário combinando dados"
    "Descubra padrões de rotatividade de clientes"
    "Analise e extraia informações de uma variedade de documentos"

Exemplos

A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.
Entrada 	Saída
Resumir o conteúdo 	Produza resumos concisos com as informações mais importantes
Gerar conteúdo de vendas e marketing 	Crie conteúdo de vendas e marketing personalizado
Planejar o inventário com eficiência 	Preveja os níveis do inventário combinando dados

Atenção: É extremamente importante que as entradas e saídas sejam exatamente iguais às descritas na descrição do desafio de código.
O código deve seguir a seguinte estrutura:
# Recebe a Entrada do usuário e armazena na variável "entrada"
entrada = input()

# Função responsável por receber um caso de uso e retornar sua respectiva descrição.
def descrever_casos(caso):
	if caso == "Resumir o conteúdo":
			return "Produza resumos concisos com as informações mais importantes"
			
	# TODO: Preencha corretamente a descrição de cada caso, considerando as condições abaixo e Saídas possíveis:			
	elif caso == "":
	    return "Crie conteúdo de vendas e marketing personalizado"
	    
	elif caso == "":
	    return "Preveja os níveis do inventário combinando dados"	
	
	elif caso == "":
	    return "Descubra padrões de rotatividade de clientes"
	    	    
	elif caso == "":
	    return "Analise e extraia informações de uma variedade de documentos"
 
print(descrever_casos(entrada))

	    	    	
	elif beneficio == "":
	    return "Acesso a Modelos de base (FMs) prontos para uso"

print(descrever_beneficio(entrada))

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


  # desafio_de_codigo_Sagemaker_Canvas_3


Descrição

O SageMaker Canvas oferece uma variedade de modelos de base prontos para uso, que incluem o Claude 2, Amazon Titan e Jurassic-2, todos construídos sobre a tecnologia Amazon Bedrock. Além disso, modelos como Falcon e MPT estão disponíveis através da SageMaker JumpStart. Esses modelos são projetados para facilitar a implementação de soluções de Machine Learning (ML) sem a necessidade de codificação profunda, permitindo que analistas de negócios e cientistas de dados colaborem de maneira eficaz.
Perante o exposto, complete o código deste desafio, associando os modelos de base do SageMaker Canvas com suas respectivas aplicações.

Saiba mais em: Amazon SageMaker Canvas.
Entrada

A entrada consiste no nome do modelo de base do SageMaker Canvas para o qual você deve retornar a aplicação. Neste contexto, os seguintes modelos são considerados válidos para este desafio de código:

    "Claude 2"
    "Amazon Titan"
    "Jurassic-2"
    "Falcon"
    "MPT"

Saída

A saída esperada é a aplicação associada ao modelo fornecido como entrada. Seguem as saídas possíveis, listadas aleatoriamente, para que você possa analisar e associar corretamente:

    "Processamento de linguagem natural e geração de texto"
    "Análises de dados complexos"
    "Análises preditivas em tempo real"
    "Aprendizado de transferência para diferentes domínios de dados"
    "Tarefas de classificação e regressão"

Exemplos

A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.
Entrada 	Saída
Jurassic-2 	Processamento de linguagem natural e geração de texto
Amazon Titan 	Análises de dados complexos
Claude 2 	Análises preditivas em tempo real

Atenção: É extremamente importante que as entradas e saídas sejam exatamente iguais às descritas na descrição do desafio de código.
O código deve seguir a seguinte estrutura
# Recebe a Entrada do usuário e armazena na variável "entrada"
entrada = input()

# Função responsável por receber um modelo e retornar sua respectiva aplicação.
def aplicar_modelos(modelo):
	if modelo == "Jurassic-2":
		return "Processamento de linguagem natural e geração de texto"

	# TODO: Preencha corretamente a aplicação de cada modelo, considerando as condições abaixo e Saídas possíveis:		
	elif modelo == "":
		return "Análises de dados complexos"

	elif modelo == "":
		return "Análises preditivas em tempo real"

	elif modelo == "":
		return "Tarefas de classificação e regressão"

	elif modelo == "":
		return "Aprendizado de transferência para diferentes domínios de dados"   

print(aplicar_modelos(entrada))
	    	    	
	elif beneficio == "":
	    return "Acesso a Modelos de base (FMs) prontos para uso"

print(descrever_beneficio(entrada))

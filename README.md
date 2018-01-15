# data-analyst-procon

Análise dos dados do Procon, período 2013 a 2016.

# O que é o Sindec?

O Cadastro Nacional de Reclamações Fundamentadas, assim, é o cadastro formado pelas Reclamações finalizadas pelos Procons integrados ao Sindec, no período de 12 meses. Ele representa ainda uma importante referência para órgãos de defesa do consumidor, imprensa, consumidores e para os próprios fornecedores. 

O Sindec integra hoje 26 Procons estaduais e 351 Procons municipais. Como vários desses Procons contam com mais de uma unidade, o Sistema opera em 675 unidades espalhadas por 448 cidades brasileiras. Esses Procons atendem a uma média mensal de 216 mil consumidores.

Fonte do Dataset: http://dados.gov.br/dataset/cadastro-nacional-de-reclamacoes-fundamentadas-procons-sindec1

# Visualização dos dados com Tableau

Saneamento Básico foi o segundo assunto mais reclamado no Procon do Mato Grosso e Amazonas 
https://public.tableau.com/profile/caio.andrian#!/vizhome/AnaliseProcon/Histria1
Dashboard
https://public.tableau.com/profile/caio.andrian#!/vizhome/DashboardAnliseProcon2013-2016/Dashboard


# Dicionário de dados

AnoCalendario: Ano calendário de publicação do cadastro de reclamações fundamentadas.

DataArquivamento: Data de arquivamento das reclamações

DataAbertura: Data de abertura das reclamações

CodigoRegiao: Código identificador da região do Procon: 01 - Norte, 02 - Nordeste, 03 - Sudeste, 04 - Sul e 05 - Centro-Oeste

Regiao: Região do Procon

UF: Unidade da Federação do Procon

strRazaoSocial: Razão social do fornecedor (empresa) na base de dados do Sindec

strNomeFantasia: Nome fantasia do fornecedor na base dedados do Sindec (nome comercial / popular / fachada)

Tipo: 1 – Pessoa Jurídica (CNPJ) 0 – Pessoa Física (CPF)

RadicalCNPJ: Aplica-se para pessoa jurídica e serve para agrupar as informações de um mesmo fornecedor (matriz e filiais), sendo os oitos primeiros dígitos do número do CNPJ - Exemplo: a matriz (central) do banco e suas filiais (agências)

RazaoSocialRFB: Razão social do fornecedor na base de dados da RFB – Receita Federal do Brasil.

NomeFantasiaRFB: Nome fantasia do fornecedor na base de dados da RFB – Receita Federal do Brasil Obs.: somente para os CNPJs (NumeroCNPJ) válidos na base da RFB

CNAEPrincipal: Código identificador da Classificação Nacional de Atividades Econômicas principal do fornecedor. Obs.: somente para os CNPJs (NumeroCNPJ) válidos na base da RFB

DescCNAEPrincipal: Descrição da Classificação Nacional de Atividades Econômicas principal dofornecedor. Obs.: somente para os CNPJs (NumeroCNPJ) válidos na base da RFB

Atendida: Código identificador da reclamação fundamentada atendida ou não pela empresa/fornecedor: S – Atendida N – NÃO Atendida

CodigoAssunto: Código identificador do assunto

DescricaoAssunto: Descrição dos assuntos do Sindec (produto ou serviço objeto da reclamação)

CodigoProblema: Código identificador do problema

DescricaoProblema: Descrição dos problemas do Sindec(especificação da lesão sofrida pelo consumidor)

SexoConsumidor: M - Masculino F - Feminino N - Não se aplica (são as reclamações (de ofício) em que o Procon é o reclamante)

FaixaEtariaConsumidor: Faixa etária do consumidor distribuída da
seguinte forma: 
- até 20 anos
- entre 21 e 30 anos
- entre 31 e 40 anos
- entre 41 e 50 anos
- entre 51 e 60 anos
- entre 61 e 70 anos
- mais de 70 anos
- Nao Informada (data de nascimento não
informada no cadastro do consumidor)
- Não se aplica (são as reclamações (de
ofício) em que o Procon é o reclamante)

CEPConsumidor: Código identificador do CEP do consumidor

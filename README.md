# Analise_Evasao_Clientes_TelecomX
Análise de Evasão de Clientes na empresa TelecomX

Projeto de Ciência de Dados, para análise de Churn, cancelamento e evasão de Clientes na empresa TelecomX, Utilizando técnica de análise exploratória de dados, visualização gráfica e inseghts com foco em retenção de clientes. 

FERRAMENTAS UTILIZADAS: 

Python

Pandas

NumPy

Matplotlib

Seaborn

Plotly

Jupyter Notebook

DICIONÁRIO DE DADOS:

•	CustomerID: número de identificação único de cada cliente;

•	Churn: se o cliente deixou ou não é a empresa;

•	Gender: gênero (masculino e feminino);

•	SeniorCitizen: informação sobre um cliente ter ou não idade igual ou maior que 65 anos;

•	Partner: se o cliente possui ou não é parceiro ou parceira;

•	Dependents: se o cliente possui ou não depende;

•	tenure: meses de contrato do cliente;

•	PhoneService: assinatura de serviço telefônico;

•	MultipleLines:assisnatura de mais de uma linha de telefone;

•	InternetService: assinatura de um provedor de internet;

•	OnlineSecurity: assinatura adicional de segurança on-line;

•	OnlineBackup: assinatura adicional de backup online;

•	DeviceProtection: assinatura adicional de proteção no dispositivo;

•	TechSupport: assinatura adicional de suporte técnico, menos tempo de espera;

•	StreamingTV: assinatura de TV a cabo;

•	StreamingMovies: assinatura de streaming de filmes;

•	Contract: tipo de contrato;

•	PaperlessBilling: se o cliente preferir receber uma fatura online;

•	PaymentMethod: forma de pagamento;

•	Charges.Monthly: total de todos os serviços do cliente por mês;

•	Charges.Total: gasto total pelo cliente;



GRÁFICOS: 

As imagens foram geradas no notebook usando Matplotlib, Seaborn e Plotly.

<img width="685" height="341" alt="Visão Geral" src="https://github.com/user-attachments/assets/0983a80c-623d-4c56-8ec7-e879391a3e7d" />



<img width="695" height="311" alt="Divisão clientes por Gênero" src="https://github.com/user-attachments/assets/d50fe641-59e4-44f0-828e-78b5e712c08f" />


<img width="835" height="471" alt="Tx Cancelamento por gênero" src="https://github.com/user-attachments/assets/859c0252-16bb-44bc-94f3-a449bbbe85e3" />



<img width="817" height="469" alt="Tx Cancelamento em Idosos" src="https://github.com/user-attachments/assets/56e30e6d-1897-44c3-b459-d629e6ae9985" />



<img width="767" height="511" alt="Cancelamento por mês" src="https://github.com/user-attachments/assets/9753eb6d-944f-4e85-b887-a22491cb0a98" />



<img width="675" height="503" alt="Tx Cancelamento por mês" src="https://github.com/user-attachments/assets/d6adb45c-576c-4c22-8319-de3e6437b4db" />



<img width="765" height="403" alt="Quantidade clientes forma de pagto" src="https://github.com/user-attachments/assets/4ec21daa-7a28-4b1e-bb13-6cc5b5d88d03" />



<img width="799" height="437" alt="Tx Cancelamento por forma de pagto" src="https://github.com/user-attachments/assets/ff69852c-15b4-48f5-9e5e-2ae68890799b" />


<img width="721" height="457" alt="Relacao cancelamento mês" src="https://github.com/user-attachments/assets/1499f277-2e5a-40c5-b87e-7203af337ea2" />



<img width="675" height="471" alt="Gastos" src="https://github.com/user-attachments/assets/cb9ad839-c570-4c49-b5e2-b5d873b80a38" />


<img width="661" height="455" alt="Tipo de contrato" src="https://github.com/user-attachments/assets/18a66250-0db4-49a6-b4ef-e6be7ffbfe7e" />




<img width="663" height="443" alt="Box" src="https://github.com/user-attachments/assets/133e251f-fd52-47ba-ba5c-01c9a169c743" />



<img width="639" height="449" alt="Tipo de internet" src="https://github.com/user-attachments/assets/72cb65b4-2e6d-40d4-ad6a-e6c302ad3246" />







                                                                    CONCLUSÕES E INSIGHTS



Cancelamento por Gênero

Observou-se uma predisposição de cancelamentos entre mulheres, sugerindo que esse público pode ter expectativas específicas não totalmente atendidas pelos serviços atuais.

Faixa Etária e Cancelamento Clientes com mais de 65 anos apresentaram maior tendência ao cancelamento, o que pode estar relacionado a dificuldades com tecnologia, atendimento ou custo dos planos.

Tempo de Contrato, Gasto Mensal e Cancelamento A maior vulnerabilidade de churn ocorre entre clientes com menos de 30 meses de contrato e faturas mensais superiores a R$ 60.

Clientes mais antigos demonstram maior estabilidade, mesmo com gastos totais mais altos.

Formas de Pagamento e Risco de Cancelamento Pagamentos via Cheque Eletrônico concentram os maiores índices de cancelamento, indicando menor conveniência percebida nesse método.

Cartão de crédito e débito automático apresentam maior retenção, reforçando a preferência por soluções práticas e automatizadas.

Tipo de Contrato e Retenção Contratos mensais são mais suscetíveis a cancelamentos, reforçando que a flexibilidade vem acompanhada de maior rotatividade.

Planos de longo prazo (anual ou bianual) apresentaram performance mais positiva em retenção, mesmo considerando um volume absoluto menor de clientes.

Tipo de Internet e Percepção de Valor Clientes de Fibra Óptica mostraram maior taxa de churn, o que pode indicar desalinhamento entre preço cobrado e qualidade percebida.

DSL e clientes sem serviço de internet apresentaram menor propensão ao cancelamento, demonstrando perfis de uso mais conservadores.


RECOMENDAÇÕES

Programa de Retenção para Novos Clientes
Desenvolver ofertas específicas para os primeiros meses de contrato, combinando descontos e benefícios extras, priorizando clientes com gasto mensal mais elevado.

Reforço no Pacote de Valor da Fibra Óptica
Ampliar o pacote de benefícios associados à internet Fibra, incluindo serviços agregados como streaming, suporte técnico premium ou armazenamento em nuvem.

Otimização dos Meios de Pagamento
Ativar campanhas focadas em migrar clientes para pagamento por cartão ou débito automático, oferecendo pequenas vantagens financeiras para estimular essa troca.

Ações Específicas por Perfil de Cliente
Criar iniciativas direcionadas para públicos mais sensíveis, como idosos e mulheres, com comunicação personalizada e suporte mais acessível.

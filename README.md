# tech_challenge03

DEFINIÇÃO
_"Churn — Quando um cliente desiste de usar um serviço ou cancela sua assinatura." (Fighting Churn with Data by Carl Gold - 2020)_


O Cliente disponibilizou um dataset com 7.043 registros de clientes, contendo 21 variáveis.
O objetivo deste projeto é explorar o comportamento de churn dos clientes, verificando quais deles estão mais propensos a cancelar o serviço

Dicionário de dados:

customerID: Identificador único do cliente
gender: Gênero do cliente, podendo ser Male e Female
SeniorCitizen: Se o cliente é idoso ou não, podendo ser 0 ou 1
Partner: Se o cliente tem parceiro ou não, podendo ser Yes ou No
Dependents: Se o cliente tem dependentes ou não, podendo ser Yes ou No
tenure: Quantidade de meses que o cliente permaneceu na empresa
PhoneService: Se o cliente tem serviço de telefone ou não, podendo ser Yes ou No
MultipleLines: Se o cliente tem múltiplas linhas de telefone ou não, podendo ser Yes, No ou No phone service
InternetService: Se o cliente tem serviço de internet ou não, podendo ser DSL, Fiber optic ou No
OnlineSecurity: Se o cliente tem serviço de segurança online ou não, podendo ser Yes, No ou No internet service
OnlineBackup: Se o cliente tem serviço de backup online ou não, podendo ser Yes, No ou No internet service
DeviceProtection: Se o cliente tem serviço de proteção de dispositivo ou não, podendo ser Yes, No ou No internet service
TechSupport: Se o cliente tem serviço de suporte técnico ou não, podendo ser Yes, No ou No internet service
StreamingTV: Se o cliente tem serviço de streaming de TV ou não, podendo ser Yes, No ou No internet service
StreamingMovies: Se o cliente tem serviço de streaming de filmes ou não, podendo ser Yes, No ou No internet service
Contract: Tipo de contrato do cliente, podendo ser Month-to-month, One year ou Two year
PaperlessBilling: Se o cliente tem fatura sem papel ou não, podendo ser Yes ou No
PaymentMethod: Método de pagamento do cliente, podendo ser Bank transfer (automatic), Credit card (automatic), Electronic check ou Mailed check
MonthlyCharges: Valor da mensalidade do cliente
TotalCharges: Valor total pago pelo cliente
Churn: Se o cliente cancelou o serviço ou não, podendo ser Yes ou No



## Referências

*  Bradburn, M., Clark, T., Love, S. et al. Survival Analysis Part III: Multivariate data analysis – choosing a model and assessing its adequacy and fit. Br J Cancer 89, 605–611 (2003). https://doi.org/10.1038/sj.bjc.6601120

*  FIA. Churn Rate: o que é e como reter mais cliente. (2020). https://fia.com.br/blog/churn-rate/
*   Magul, Eudito. Churn Customers: Survival Analysis Applying R. (2023). https://medium.com/@euditomagul/churn-customers-survival-analysis-applying-r-fe09df4c93cc
*   Goel MK, Khanna P, Kishore J. Understanding survival analysis: Kaplan-Meier estimate. Int J Ayurveda Res. 2010 Oct;1(4):274-8. doi: 10.4103/0974-7788.76794. PMID: 21455458; PMCID: PMC3059453. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3059453/#:~:text=may%20become%20small.-,The%20Kaplan%2DMeier%20estimate%20is%20the%20simplest%20way%20of%20computing,associated%20with%20subjects%20or%20situations.&text=For%20each%20time%20interval%2C%20survival,number%20of%20patients%20at%20risk

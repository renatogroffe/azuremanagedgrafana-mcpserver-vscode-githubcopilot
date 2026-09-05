# azuremanagedgrafana-mcpserver-vscode-githubcopilot
Configurações para uso do MCP Server do Azure Managed Grafana + Visual Studio Code + GitHub Copilot. Testes realizados com métricas obtidas de um cluster Kubernetes baseado no AKS (Azure Kubernetes Service) e integrado com o Azure Managed Prometheus.

Habilitando o uso de Service Account na instância do Azure Managed Grafana no Portal do Azure (Settings > Configuration):

![Enable Service Account](img/01-enable-service-account.png)

Criar dentro do Grafana uma nova Service Account (Administration > Users and access > Service accounts):

![Add Service Account](img/02-add-service-account.png)

Criando a Service Account e atribuindo a role Admin:

![Create Service Account](img/03-create-service-account.png)

Service Account criada com sucesso:

![Service Account criada](img/04-service-account.png)

Ao clicar em "+ Add service account token" poderemos então configurar a validade do novo token:

![Criando um novo token](img/05-creating-token.png)

E chegaremos a um novo token criado com sucesso:

![Novo token criado](img/06-new-token.png)
# resumo-do-lab

### Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO. ###

  **As lições que foram aprendias até o momento são:**
  
* A **Introdução ao Azure Essentials com a Microsoft** foi uma aula demonstrando tudo que vou aprender em todo bootcamp Microsoft Azure. 
* A **Introdução a Computação em Nuvem**, que foi a primeira visualização do mundo Nuvem da Azure. Foi ensinado como criar uma conta Azure, uma pincelada introdutória do que vou ver no curso, o que posso fazer na Azure, desde a criação de um servidor para a empresa até um site completo e dinâmico.
* O **Versionamento de Código em Git e GitHub**, aprendi a instalar o git, no meu caso uso Windows 11 e junto com ele uso WSL2, com Ubuntu 22.04.3 e instalei o git, fiz uma chave SSH no GitHub. Aprendi alguns comando como Git init, git status, git add, git commit entre outros.
* No **Desafios de Projetos: Crie Um Portifólio Vencedor**, aprendi como fazer um portifólio para nos ajudar no meu crescimento profissional e juntamente com o outro tópico como **Constribuição em um Projeto Open Source no Github** fiz um portifólio com um pouco de HTML, Markdown, site como emojipedia, dev.to entre outros.
* A **Introdução Prática ao Azure AI e Azure OpenAI Models**, no qual a live vai estar disponível no dia **24/09/2024** com apresentação de **Rogério Rodrigues**.
  
* A **Segunda** parte desse Resumo aprendi alguns fatores como **Benefícios da Computação em Nuvem:**
*  1 - **alta disponibilidade** (SLA -quanto mais 9 menos tempo disponível e quando menos 9 mais tempo disponível);
*  2 - **Escalabilidade** que ajusta a capacidade para demanda;
*  3 - **Elasticidade** que dimenciona ambiente de acordo com a demanda;
*  4 - **Confiabilidade** que tem design descentralizado, várias regiões pelo mundo, recupera de falhas e continua funcionando;
*  5 - **Previsibilidade** que é a confiança, desempenho ou custo;
*  6 - **Segurança** no qual a implementação é para ambos os lados (Microsoft - Oferece o serviço | Cliente - que aplica o serviço.);
*  7 - **Governança** que faz a gestão, auditoria, mitigação (resolução) e as regras do serviço;
*  8 - **Gerenciabilidade** que cria recursos, se a escala vai ser automática e a criação pode ser por meio de portal, linha de comando, APIs ou Powershell.
  
*  A **Terceira** parte desse resumo aprendi sobre **Os tipos de serviço de nuvem:**
*  **IaaS** (*Infraestrutura* como serviço) (Menor Gestão) -> Servidores e armazenamentos | Firewalls/Segurança de Rede | Planta física/Edifísio do Datacenter;
*  **PaaS** (*Plataforma* como serviço) (Meio Gestão) -> Sistemas Operacionais | Ferramentas para desevolvedores, Análise de Negócios de Gerenciamento de Database;
*  **SaaS** (*Software* como serviço) (Maior Gestão) -> Aplicativos/Apps Hospedado;
*  Com relação ao modelo de responsabilidade o Provedor da Nuvem fica sempre com a Física em todos os tipos de serviços e os demais ficam:
*  SaaS: Físico, Compartilhado (Infra), aplicativo, rede e S.O. por conta do Provedor da nuvem;
*  PaaS: Físico, S.O., Compartilhado (Infra, Aplicativo, Rede) por conta do Provedor da nuvem;
*  IaaS: Físico por conta do Provedor da nuvem.

*  A **Quarta** parte aprendi sobre o conceito de arquitetura do Azure e são divididos em:
*  **Regiões** com abrangência global, sendo que se eu estiver um empresa do Brasil e outra no Estados Unidos, posso montar uma aplicação ou sistema em cada país separados. E existe os *pares das regiões* que quando uma região fica inativa a outra par ativa os recursos para não ficar indisponível para o cliente e nem todos os recursos são disponíveis, depende de cada região. As **regiões soberanas** são aquelas que só determinados orgãos podem acessar, é o caso dos *Serviços Governamentais dos EUA* e *Azure China* (operados pela 21vianet);
*  **Recursos Azure*  que são *Máquinas Virtuais, contas de Armazenamento, Redes Virtuais, Serviços de Aplicativos, Banco de Dados SQL e funções*.
*  **Contas Azure** que podem conter *contas de assinaturas de desenvolvimento, de teste ou de produção*. Obs.: Uma conta pode ter diversas assinaturas **mas** um assinatura está associada somente a uma conta.
*  Ainda na **Quarta** parte aprendi sobre arquitetura e serviços do Azure, que compreende em:
*  Computação Azure que são compostos de: *Virtual/Virtuais, Aplicativos/Serviços* (Balanceamento de carga e escala, fica na parte de plataforma e usa as linguagens como .Net, .Net Core, Node.JS, Java, Python ou PHP), *Contêiner/Instâncias* (Ambiente leve e virtualizado e fica na parte de plataforma, como exemplo o Docker), *Serviços de Kubernetes do Azure (AKS)* (Orquestração de circulo de vida do contêiner), *Área de Trabalho virtual do Azure* (Desktop virtual), *Azure Functions* (Executa uma ativiade baseada em eventos e fica na parte de plataforma) e *Rede Virtual (VNET)* (Comunicação de recursos, com internet e com redes locais).

*  A **Quinta** parte do laboratório aprendi as tipos de armazenamento do Azure no qual o nome da conta de armazenamento deve ser *exclusivo*, contendo de *3 a 24 caracteres*, *não aceita caracteres especiais* e *nem letras maiúsculas*, que são:
*  **Redundância de dados**:
*  LRS - > Individual na região primária -> 11 noves;
*  ZRS - > Três zonas na região primária -> 12 noves;
*  GRS - > Datacenter único na região primária e região secundária -> 16 noves;
*  GZRS - > Três zonas na região primária e único datacenter na região secundária -> 16 noves.
*  Blog do Azure: Armazenamento massiva de dados *não* estruturados.
*  *Endereçamento*:
*  Blog -> https://<storage-account>.blob.core.windows.net
*  Data Lake Storage -> https://<storage-account>.dfs.core.windows.net
*  Arquivos Azure -> https://<storage-account>.file.core.windows.net
*  Armazenamento de filas -> https://<storage-account>.queue.core.windows.net
*  Armazenamento de tabelas -> https://<storage-account>.table.core.windows.net
*  O *Azure Data Box* suporta até 80 terabyte.
*  O *AzCopy* é um utilitário de linha de comando, copia blobs ou aquivos de armazenamentos ou arquivos para sua conta de armazenamento.
*  A **Sexta** parte do laboratório aprendi sobre:
*  Diretório Azure, que inclui o Microsoft Entra ID (antigo Azure Active Diretory) e o Microsoft Entra Domain Services;
*  Métodos de Autenticação no Azure, incluso SSO (Autenticação uma vez, que vc faz a autenticação uma vez de sua aplicação ou máquina, MFA (Autenticação de dois fatores ou autenticação de algum característica física ou fato de sua vida);
*  Identidades externas no qual você tem um parceiro fora de sua empresa que precisa acessar algum recurso ou aquivo no Azure e o acesso de convidado Azure que é um acesso temporário no qual esse usuário tem acesso algum tipo de arquivo ou recurso e é muito usado para uma auditoria por exemplo ou pessoa temporária.
*  A **sétima** parte do laboratório aprendi sobre:
*  *Custo no Azure*, que faz um comparativo de preço de todas as funções que o Azure pode proporcionar;
*  Nessa *calculadora* pode-se fazer uma previsão do custo mensal ou anual dos produtos *Azure*;
*  Foi falado também do *Azure Marketplace*, que é uma plataforma de software livre que contêm vários softwares e inclusive pode instalar nele algum recurso que temos na nossa empresa;
*  Existe também no Azure o *Gerenciamento de custos do Azure* que é um relatório de cobrança e dados no qual já foi gasto e utilizado na cloud Azure;
*  E por último temos as *marcas (tags)* que fornece metadados aos recursos do Azure, organiza os recursos em um taxonomia de maneira lógica.
*   A **oitava** parte do laboratório aprendi sobre:
*   Como é feita as políticas de grupo com Azure Policy que ajuda a impor padrões organizacionais e a avaliar a conformidade em escala;
*   Os bloqueios de recursos que protege os recursos do Auzre de exclusão ou modificação acidental (bloqueio tipo Excluir -> que só não pode excluir e o ReadOnly -> que não pode nem excluir e nem mover);
*   O Portal de Confiança do Serviço e um portal que contêm toda documentação dos recursos e serviços feitos pela Microsoft;
*   E o Microsoft Purview no qual é uma familia de soluções de governança, risco e conformidade de dados que ajuda a obter uma única exibição unificada em seus dados.
  
  

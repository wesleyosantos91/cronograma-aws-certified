# cronograma-aws-certified-solutions-architect
Cronograma de estudo para prova


| Domínio                                                |  % do exame  |
| ------------------------------------------------------ | -----------  |
| Domínio 1: Design de arquiteturas resilientes          | 30%          |
| Domínio 2: Design de arquiteturas de alta performance  | 28%          |
| Domínio 3: Design de aplicações e arquiteturas seguras | 24%          |
| Domínio 4: Design de arquiteturas econômicas           | 18%          |
| TOTAL                                                  | 100%         |   

### Observação

- S3:
    - S3 todos os tipos ex: glacial entre outros
- EC2:
    - EC2 segurança, em questão de quem pode acessar por default e se ele pode acessar algum lugar por default
    - Tipos de EC2
- VPC:
    - VPC: calcular sub redes

### Domínio 1: Design de arquiteturas resilientes

#### 1.1 Design de uma solução de arquitetura de várias camadas
- [ ] Determinar um design de solução com base em padrões de acesso.
- [ ] Determinar uma estratégia de escalabilidade para componentes usados em um design.
- [ ] Selecionar um banco de dados apropriado com base nos requisitos.
- [ ] Selecionar um serviço de computação e armazenamento adequado com base nos requisitos.

#### 1.2 Design de arquiteturas altamente disponíveis e/ou tolerantes a falhas
- [ ] Determinar a quantidade de recursos necessários para fornecer uma arquitetura tolerante a
falhas nas zonas de disponibilidade.
- [ ] Selecionar uma configuração altamente disponível para mitigar pontos únicos de falha.
- [ ] Utilizar os serviços da AWS a fim de melhorar a confiabilidade de aplicações legadas quando
não é possível alterá-las.
- [ ] Selecionar uma estratégia de recuperação de desastres adequada para atender aos
requisitos de negócios.
- [ ] Identificar os indicadores-chave de performance para garantir a alta disponibilidade da
solução.

#### 1.3 Design de mecanismos de desacoplamento com o uso de serviços da AWS
- [ ] Determinar quais serviços da AWS podem ser aproveitados para obter um baixo
acoplamento de componentes.
- [ ] Determinar quando utilizar tecnologias sem servidor para permitir o desacoplamento.

1.4 Escolha do armazenamento resiliente apropriado
- [ ] Definir uma estratégia para garantir a durabilidade dos dados.
- [ ] Identificar como a consistência do serviço de dados afetará a operação da aplicação.
- [ ] Selecionar serviços de dados que atendam aos requisitos de acesso da aplicação.
- [ ] Identificar serviços de armazenamento que podem ser usados com aplicações híbridas ou
não nativas da nuvem.

### Domínio 2: Design de arquiteturas de alta performance

#### 2.1 Identificação de soluções de computação elásticas e escaláveis para uma workload
- [ ] Selecionar as instâncias apropriadas com base nos requisitos de computação,
armazenamento e redes.
- [ ] Escolher a arquitetura e os serviços adequados que são escalados para atender aos
requisitos de performance.
- [ ] Identificar métricas para monitorar a performance da solução.

#### 2.2 Seleção de soluções de armazenamento escaláveis e de alta performance para uma workload
- [ ] Selecionar um serviço de armazenamento e uma configuração que atendam às demandas
de performance.
- [ ] Determinar os serviços de armazenamento que podem ser escalados para atender às
necessidades futuras.

#### 2.3 Seleção de soluções de redes de alta performance para uma workload
- [ ] Selecionar as opções apropriadas de conectividade da AWS para atender às demandas de
performance.
- [ ] Selecionar os recursos apropriados para otimizar a conectividade com os serviços públicos
da AWS.
- [ ] Determinar uma estratégia de armazenamento em cache de borda para fornecer benefícios
de performance.
- [ ] Selecionar o serviço de transferência de dados apropriado para migração e/ou ingestão.

#### 2.4 Escolha de soluções de banco de dados de alta performance para uma workload
- [ ] Selecionar uma estratégia de escalabilidade de banco de dados apropriada.
- [ ] Determinar quando o cache de banco de dados é necessário para melhorar a performance.
- [ ] Escolher um serviço de banco de dados adequado para atender às necessidades de
performance.

### Domínio 3: Design de aplicações e arquiteturas seguras

#### 3.1 Design de acesso seguro aos recursos da AWS
- [ ] Determinar quando escolher entre usuários, grupos e funções.
- [ ] Interpretar o efeito líquido de determinada política de acesso.
- [ ] Selecionar as técnicas apropriadas para proteger uma conta raiz.
- [ ] Determinar maneiras de proteger credenciais com o uso de recursos do AWS IAM.
- [ ] Determinar o método seguro para uma aplicação acessar APIs da AWS.
- [ ] Selecionar os serviços apropriados a fim de criar rastreabilidade para acesso aos recursos
da AWS.

#### 3.2 Design de níveis de aplicações seguros
- [ ] Determinar quando e como usar grupos de segurança e network ACLs considerando os
requisitos de controle de tráfego.
- [ ] Determinar uma estratégia de segmentação de rede com o uso de sub-redes públicas e
privadas.
- [ ] Selecionar o mecanismo de roteamento apropriado para acessar com segurança os
endpoints de serviço da AWS ou recursos na Internet pela Amazon VPC.
- [ ] Selecionar os serviços da AWS apropriados para proteger aplicações contra ameaças
externas.

#### 3.3 Seleção das opções de segurança de dados apropriadas
- [ ] Determinar as políticas que precisam ser aplicadas aos objetos com base em padrões de
acesso.
- [ ] Selecionar as opções de criptografia apropriadas para dados em repouso e em trânsito nos
serviços da AWS.
- [ ] Selecionar as opções apropriadas de gerenciamento de chaves com base nos requisitos. 

### Domínio 4: Design de arquiteturas econômicas

#### 4.1 Identificação de soluções de armazenamento econômicas
- [ ] Determinar as opções de armazenamento de dados mais econômicas com base nos
requisitos.
- [ ] Aplicar processos automatizados para garantir que os dados ao longo do tempo sejam
armazenados em níveis de armazenamento que minimizam os custos.

#### 4.2 Identificação de serviços econômicos de computação e banco de dados
- [ ] Determinar as opções de faturamento mais econômicas do Amazon EC2 para cada aspecto
da workload.
- [ ] Determinar as opções de banco de dados mais econômicas com base nos requisitos.
- [ ] Selecionar estratégias de escalabilidade apropriadas sob uma perspectiva de custos.
- [ ] Selecionar e dimensionar os recursos de computação ideais para a workload.
- [ ] Determinar opções para minimizar o custo total de propriedade (TCO) por meio de serviços
gerenciados e arquiteturas sem servidor.

#### 4.3 Design de arquiteturas de rede otimizadas para custos
- [ ] Identificar quando a entrega de conteúdo pode ser usada a fim de reduzir custos.
- [ ] Determinar estratégias para reduzir os custos de transferência de dados na AWS.
- [ ] Determinar as opções mais econômicas de conectividade entre a AWS e os ambientes onpremises.

# Learning-Azure-DIO
Este repositório é composto por anotações que fiz para o curso de Azure da DIO.

##Computação em nuvem

Foi explicado sobre a interface inicial da plataforma Microsoft Azure, inclusive algumas configurações iniciais, como alteração de idiomas. Além disso, foi ensinado sobre algumas das principais categorias de serviços do Azure, como:
* Computação
* Rede
* Armazenamento

Além disso, foi falado sobre alguns serviços que podem aparecer como versão prévia que são produtos ou serviços que ainda estão sendo testados. Não possui garantias de dar continuidade a alguma feature do mesmo.

## Benefícios da Nuvem
# SLA
Define o tempo de inatividade aceitável, que vão desde 1,68 hora por semana a 6 segundos por semana. Saber qual SLA usar é fundamental para manter o equilíbrio aceitável entre custos e disponibilidade do recurso utilizado.

Essa disponibilidade é alcançada por meio de escolhas de estruturas, como ao criar máquinas virtuais escolhendo mais zonas e opções de disponibilidade e ao criar contas de armazenamento, que replicam os dados.

## Criar máquina virtual e instância de banco de dados
Ao criar uma máquina virtual, devemos especificar opções como discos (com imagens de algum SO), rede, gerenciamento e monitoramento.

Criar uma instância de banco de dados funciona de forma muito semelhante. Selecionamos então um servidor (que funciona de forma simbólica) e a redundância do armazenamento de backup, que afeta diretamente o SLA do serviço.

## Construindo Arquiteturas no Azure
# Disponibilidade regional e global do Azure
Na data de gravação aula, o Brasil possuía uma região principal, chamada de Brazil South, sediada em São Paulo que replicava para os EUA. E também possuía uma outra, sediada no Rio, que era reservada para empresas com dados sensíveis e que seguiam a LGPD (Que proíbe que certos dados saiam do Brasil), que replicava com a região South. Também vimos uma demonstração de todas as regiões do Azure ao redor do mundo.

# Criando Grupo de recursos
Grupo de recursos é uma coleção de recursos que compartilha o mesmo ciclo de vida, permissões e políticas. Podem possuir bloqueios para que possamos proteger determinadas funções ou recursos

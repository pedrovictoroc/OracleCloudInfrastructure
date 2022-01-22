- VCN

    * Virtual Cloud Newtork

- Subnet

    * Cada VCN é subdividida em subnets, que podem ser 
        regionais (recomendado) ou em uma única AD
    
    * Cada subnet tem um espaço contínuo de IPs descrito em 
        CIDR
    
    * Você pode ter até 300 subnets por AD

    * Cada subnete pode ter seu design para ser publica ou 
        privada

- Security List

    * Conjunto de regras de firewall associadas a uma subnet 
        e aplicado a todas as instâncias dentro da subnet
    
    * Especificam os tipos de tráfico permitidos de entrada
        e saída da instância
    
    * Você pode escolher entre uma regra stateful ou stateless

        -> Stateless: Para cada regra de entrada, tem que 
            criar uma regra de saída
        
        -> Stateful: Cria a regra de saída automaticamente

- Network Security Group

    * CONTINUAR

- Remote VCN Peering

    * Remote peering connection

        -> As duas VCNs não podem ter overlap de CIDR

        -> Componente do DRG, um gateway

- Connectivity options

    * Reversed IPs (Public Internet)
    * Ephemeral IPs (Public Internet)

    * IPsec authentication e ecryption (Oracle IPsec VPN)
        -> OCI managed VPN service (grátis)
        -> Software VPN (roda no OCI compute)
    
    * Private connection (Oracle FastConnect)

- Load Balancer as a Service

    * A chamada por um recurso bate no load balancer e ele
        redistribui a carga
    * Alta disponibilidade
    * Largura de banda flexível
    * Opções públicas e privadas
    * Temos dois tipos
        -> OCI Load Balancer (Camada de aplicação, proxy para 
            TCP e HTTP)
        -> Network Load Balancer (Camada de rede, não é proxy)
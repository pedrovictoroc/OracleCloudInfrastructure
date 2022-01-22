- Regions
    
    *  Área geográfica, consiste de 1 ou mais (máximo 3)
        Availability DOmain

- Availability Domains (AD)

    * Fault-independent availability
    * Recuperação remota
    * Baixa latência e alta velocidade de conexão encriptada 
        entre ADS
    * Fault Domains para recuperação

- Fault Domains

    * Geralmente 3 por AD
    * CONTINAR

- Tenancy

    * Equivalente a uma conta
    * CONTINAR

- Compartments

    * Segregar ambientes e permissões
    * NÃO CRIE RECURSOS NA ROOT (Coloque em compartimentos 
        para segregar e proteger)
    * Podem ser criados até 6 subníveis de compartimentos 
        (1.000 Compartimentos por instância)
    * A descrição é obrigatória!

- TAG

    * CONTINUAR

- Identity Access and Security

    * ZERO-TRUST POLICY para novos usuários
    * Compartimentos são importantes para separar as policys
    * Sintaxe
        -> Allow group <group_name> to <verb><resource_type>
           in compartment <compartment_name> [where <condition>]

        -> LISTAR SINTAXES
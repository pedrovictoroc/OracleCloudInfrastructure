- Compute Instances

    * Bare Metal
        
        -> Acesso direito ao hardware e virtualização
    
    * Virtual Machine

        -> Não me preocupo com hardware ou disco, apenas
            me preocupo com virtual machine
    
    * Dedicated VM Hosts

        -> Mistura os anteriores, roda suas VMs em um servidor
            dedicado que é um single tenant e não compartilhado

- CPU Billing

    * On-Demand
    * Capacity Reservation
        -> Pré-alocação de recursos
    * Preemptible Instance
        -> Pode ser terminada a qualquer momento
        -> Custo de CPU = 50% do on-demand
    * Burstable Instance

- Auto Scaling

    * Vertical Scaling
        -> Scale-up ou Scale-down de uma só máquina
    
    * Horizontal Scaling
        -> Scale-Out ou Scale-in de quantidade de máquinas
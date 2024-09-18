# resumo-do-lab-az900-pt1
Este repositório contém o resumo das primeiras lições aprendidas na Dio para a certificação AZ-900.
Nos primeiros vídeos sobre o projeto, aprendemos as diferenças entre CAPEX e OPEX:

CAPEX: Refere-se ao custo inicial. Quando você decide ter uma infraestrutura On-Premise, você tem um custo antecipado com a compra dos servidores, tamanhos dos discos, memória, etc. Em resumo, você tem um custo maior logo no início para criar sua infraestrutura. Esse custo é reduzido com o tempo porque você... (O texto parece estar incompleto aqui.)

OPEX: O custo do OPEX é diferente. Você não paga nada antecipadamente; paga conforme utiliza o serviço ou o produto adquirido. Um exemplo é quando você cria um servidor na nuvem: você paga conforme o uso e, quando não for mais necessário, pode excluí-lo e não ter mais esse custo.

Também foi explicado sobre os modelos de nuvem:

Nuvem Privada: A empresa cria um ambiente de nuvem no seu próprio datacenter; não é possível acesso fora da organização.
Nuvem Híbrida: É a combinação da nuvem pública e privada. Ela tem serviços On-Premise e também na nuvem, e você escolhe o local ideal para o serviço ou aplicação ser executado.
Nuvem Pública: Os serviços estão na nuvem, que é compartilhada com outras organizações. Não é possível ter acesso aos serviços de outras organizações sem autorização; você consegue acessar os servidores ou aplicações via rede segura.

Parte 2

Nesse segundo bloco, foi explicado sobre os benefícios da nuvem:

Alta Disponibilidade: A Microsoft se compromete a cumprir os SLAs de contrato. Caso não seja cumprido, você recebe um voucher que pode ser utilizado na Azure para desconto em serviços. É importante entender os SLAs da Microsoft porque há diferenças entre eles. Abaixo está uma imagem com os SLAs e o tempo de inatividade que a Microsoft pode ter:

<img width="510" alt="image" src="https://github.com/user-attachments/assets/030be092-9610-4a37-98ba-0134ae24f7f5">

Também foram abordadas as diferenças entre Elasticidade e Escalabilidade:

Elasticidade: Você consegue aumentar seus recursos automaticamente. Por exemplo, você pode configurar a Azure para, quando uma máquina virtual atingir 80% de utilização, automaticamente iniciar uma nova máquina com a mesma configuração para balanceamento. Você também pode configurar para que, quando a máquina virtual estiver com baixa utilização, ela seja desligada, reduzindo assim o custo com o outro recurso.

Escalabilidade: Você consegue adicionar mais memória e CPUs às máquinas virtuais, se necessário, para atender a uma demanda específica. Após essa demanda, você pode reduzir os recursos novamente, o que diminuirá o custo na Azure.

Temos a parte de segurança, onde a Microsoft oferece diversas ferramentas para auxiliar o cliente com esse tópico importante. No entanto, lembre-se de que a maioria dessas configurações será de responsabilidade do cliente, dependendo se o serviço é IaaS, PaaS ou SaaS. Assim, as responsabilidades serão atribuídas ao cliente ou à Microsoft.

Governança: Você consegue configurar alertas para quando algum recurso estiver fora dos padrões e estratégias de mitigação.
Gerenciabilidade: Você consegue configurar para escalar automaticamente a implantação de recursos, dependendo da necessidade do cliente, ter recursos pré-configurados, facilitando a criação de recursos. Além disso, você pode fazer isso via CLI ou WEB.








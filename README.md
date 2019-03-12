# LabCIM-Capstone-Projects

Sugestões de Projetos para Trabalhos de Conclusão de Curso em Fabricação Integrada por Computador ou CIM.

O Laboratório CIM da PUCRS, fundado em 1997, onde foram desenvolvidas as ferramentas Robsoft Simulator e ACLC, 


## Software (CC, EC)

Desenvolvimento de software para programação, controle e simulação dos
robôs industriais. O software deve possuir compatibilidade para programação
direta e indireta, sendo necessário, respectivamente, um terminal embutido
e um editor de textos com highlight adequado para linguagem ACL utilizada
nos robôs desenvolvidos pela ESHED Robotec, assim como informações de erros
de sintaxe. A comunicação com o controlador do robô é dada pela porta serial
(USB por adaptador ou RS232). 

Também deve permitir comunicação entre estações, apresentando configurações
para identificação de cada equipamento na rede e troca de informações.
Para auxilio, o código fonte do software utilizado atualmente, o Robosoft,
está disponível no GitHub, tendo sido desenvolvido em Pascal por meio do
programa Delphi, assim como o interpretador ACL utilizado pelo mesmo,
desenvolvido em Perl. O software deve ser desenvolvido em open source,
permitindo futuras atualizações, além de multiplataforma.

## Digital Twin Brother (CC, EC, ECA)

Através da leitura de encoders presentes em cada motor de cada robô,
é possível identificar a posição na qual o robô se encontra. Por meio
desta leitura, a proposta é o desenvolvimento de um gêmeo virtual,
permitindo a visualização por meio de modelos 3D de cada equipamento
em tempo real ou para simulações de programações.

## Rede de Controle (EC, ECA, EE)

Implementar uma rede de comunicação entre as estações, permitindo que
haja uma estação central que possa controlar as demais. Os controladores
podem estar conectados a um CLP utilizado como mestre, por meio de um
sistema MODBUS, seja por RS232 (conector padrão dos controladores) ou
ethernet. Também é possível conectar as estações via rede ethernet,
permitindo que um computador possa estar ligado a uma única estação ou a
várias. Os controladores atuais não possuem conexão ethernet direta,
portanto para tais redes será necessário o desenvolvimento de um sistema
que converta a conexão serial para ethernet e vice-versa. 

## Computação gráfica aplicada a indústria (CC, EC, ECA)

Desenvolvimento de um sistema de visão capaz de identificar peças na esteira,
classificar e realizar medições por meio de uma câmera. O sistema deve ser
capaz de gerar relatórios e se conectar ao software utilizado no laboratório.
O sistema deve ser desenvolvido em open source.

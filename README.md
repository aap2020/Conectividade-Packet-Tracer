# "Como Planejar e implantar uma rede com Conectividade para banda"

Este foi um desafio proposto no Curso Preparatório da PROZ para a certificação AWS Certified Solutions Architect - Associate, no módulo Redes e Linux Essentials para AWS.

Desafio: Projetar e configurar, utilizando o Cisco Packet Tracer e dispositivos de interconexão através de uma topologia de rede em estrela para o show da banda de Miguel. O objetivo foi estabelecer uma comunicação eficiente entre os membros da equipe de produção, equipe de serviço do teatro e colaboradores do teatro, visando atender a necessidade do evento.

# Diagrama da Rede
![TOPOLOGIA-TEATRO](https://github.com/user-attachments/assets/0f8b4698-933b-481d-9da1-b50aaa371f8e)

# Link para baixar o packet-tracer 
https://www.cafecomredes.com.br/2022/08/cisco-packet-tracer-82.html

# Endereços Lógico de Redes
- Rede Equipe de Produção 192.168.16.0/24, Gateway da rede local 192.168.16.1
- Rede Palco 192.168.0.0/24 Rede_Wireless (TEATRO-PARCK), Gateway da rede local 192.168.0.1
- Rede de Serviço Teatro 192.168.17.0/24,  Gateway da rede local 192.168.17.1

# Protocolo de roteamento utilizado:
Estático

# Entrega dos IP automáticamente 
Foi utilizado o protocolo de host - DHCP

# Equipamentos utilizados para execução dos testes:
02 Roteadores modelo cisco 2911
02 Switch Cisco modelo 2960-24T
01 Roteador Wireless 
08 PC´s 
02 Laptop

# Teste de conectividade  entre hosts da rede
<img width="953" alt="TESTE-REDE" src="https://github.com/user-attachments/assets/9647b5c0-6ae8-42cc-8fb7-a5d69b01d95e">
# Teste de conectividade Entre redes
<img width="662" alt="TESTE_PING-TRACEROUTE-ENTRE-REDES" src="https://github.com/user-attachments/assets/485ff76f-1060-4ee6-a56e-70c1e3350cc4">

# Passo a Passo com teste de simulação do Packet-tracer
1º baixe o arquivo conforme o link mencionado acima, 2º abra o arquivo disponibilizado via repositório, 3º execute o teste utilizando a simulação do próprio packet-tracer conforme o link abaixo
Link:  https://youtu.be/imQRoF-pj_s


# Explicação 
Este desafio mostra que as configurações básica de uma rede utilizando uma topologia estrela através do soft de simulação Packet Tracer é possível obter a comunicação não só entre os membros, mais também entre partes externas, onde demonstra total estabelecimento com sucesso e entregando os requisitos do desafio proposto 
onde 

# Autor

ALMIR ALVES







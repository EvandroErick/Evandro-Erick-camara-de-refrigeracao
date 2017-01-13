# Camara de refrigeração

Camara de refrigeração automatizada

# Descrição do Projeto

O projeto tem o intuito de criar uma câmara refrigerada que mostre a temperatura da câmara em um display e possua uma porta automática, além do sistema de refrigeração que em um primeiro momento não necessariamente será automatizado. Esse projeto é uma espécie de miniatura de câmaras de refrigeração que são utilizadas hoje em dia. Essas câmaras são altamente utilizadas em hospitais, frigoríficos, laboratórios de pesquisas entre outros estabelecimentos que necessitem controlar o acesso a determinado material.

#Plataforma 

Arduino

#Material
#
→Para execução do projeto em principio serão necessários; 
#
→Sensor de temperatura; 
#
→Display LDC de 16x2 seguimentos;
#
→Leitor RFID;
#
→Motor de passo;
#
→Sistema de refrigeração*.
#

*O sistema de refrigeração inicialmente não contará com controle de temperatura uma vez que o mesmo será composto por uma pastilha Peltier, que possui complexo funcionamento, e duas ventoinhas. 

#Funcionamento

O sistema inicialmente exibirá a temperatura interna da câmara de refrigeração em um display LCD 16x2, esse display ainda informará a condição em que a porta da câmara de refrigeração se encontra (aberta, fechada). Para abrir a porta será necessário aproximar um cartão magnético do módulo RFID que acionara um motor de passo e destravara a porta. A porta ficara aberta até que seja travada novamente, o travamento da porta dar-se-á pelo mesmo cartão magnético. 


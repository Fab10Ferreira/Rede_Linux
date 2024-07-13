# Rede_Linux
 Material de estudo do curso de Rede Linux
 Exercício Básico de Redes com 1 Switch e 4 Computadores

**Descrição**
Exercício básico para iniciantes em redes de computadores que simula (através do Cisco Packet Tracer) a configuração de uma rede simples com um switch e quatro computadores. Trata-se de uma introdução prática aos conceitos de rede local (LAN) e à configuração básica de dispositivos de rede.

**Objetivos**
Compreender os conceitos básicos de redes de computadores.
Configurar uma rede local utilizando um switch.
Configurar endereços IP estáticos em computadores.
Testar a conectividade entre os dispositivos da rede.

**Componentes da Rede**
Switch: Um dispositivo de rede que conecta os computadores, permitindo a comunicação entre eles.
Computadores: Quatro computadores que serão configurados para se comunicar através do switch.

**Requisitos**
Um switch;
Quatro computadores;
Cabos Ethernet para conectar os computadores ao switch;

**Passos para Configuração**
1. Conexão Física
Conecte cada um dos quatro computadores a uma porta do switch utilizando cabos Ethernet.
2. Configuração de Endereços IP
Em cada computador, configure um endereço IP estático. Abaixo está um exemplo de configuração:

**Computador 1:**
IP: 192.168.1.1
Máscara de Sub-rede: 255.255.255.0

**Computador 2:**
IP: 192.168.1.2
Máscara de Sub-rede: 255.255.255.0

**Computador 3:**
IP: 192.168.1.3
Máscara de Sub-rede: 255.255.255.0

**Computador 4:**
IP: 192.168.1.4
Máscara de Sub-rede: 255.255.255.0

**3. Teste de Conectividade**

Abra o terminal ou prompt de comando em cada computador.

Utilize o comando ping para testar a conectividade entre os computadores. Por exemplo, no Computador 1, execute:

ping 192.168.1.2
ping 192.168.1.3
ping 192.168.1.4

Repita o processo nos outros computadores, alterando os endereços IP conforme necessário.

**Resultados Esperados**
Todos os computadores devem conseguir se comunicar entre si.
Os comandos ping devem retornar respostas bem-sucedidas, indicando que os pacotes estão sendo enviados e recebidos corretamente.


**Autor**
Fábio Ferreira (https://github.com/Fab10Ferreira)
Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

Contato
Para mais informações ou dúvidas, entre em contato:

Email: fabiolfbr@gmail.com
GitHub: Fab10Ferreira

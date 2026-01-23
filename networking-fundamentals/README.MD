# Fundamentos de TI – Mês 1

Este repositório documenta meus estudos iniciais em infraestrutura,
redes

## 01 - Redes de Computadores

### O que é uma rede
Uma rede de computadores é um conjunto de dispositivos interconectados
com o objetivo de compartilhar dados e recursos.

### 02 - Redes moveis e sem fio
Configuração de dispositivos móveis para acesso sem fio

Rede Wireless:

    Os celulares usam ondas de rádio para transmitir sinais de voz a antenas montadas em torres localizadas em regiões específicas. Quando é feita uma ligação telefônica, o sinal de voz é retransmitido de uma torre a outra até chegar ao destino. Esse tipo de rede é usado quando você faz uma chamada para outro telefone celular ou para um telefone fixo. Também serve para enviar mensagens diretamente do telefone. O tipo mais comum de rede de telefonia celular é uma rede GSM. As abreviações 3G, 4G, 4G-LTE e 5G são usadas para descrever as redes de celular avançadas que foram otimizadas para transmissão rápida de dados. Atualmente, o 4G ainda domina como a rede móvel atual usada pela maioria dos telefones.

Além dos transmissores e receptores GSM e 4G/5G, os smartphones fazem conexões de várias maneiras.

Wi-fi:

    Transmissores e receptores Wi-Fi localizados no smartphone permitem que o telefone se conecte a redes locais e à Internet. As redes Wi-Fi normalmente pertencem a proprietários particulares, mas costumam oferecer hotspots de acesso público ou para convidado. Um hotspot é uma área onde os sinais de Wi-Fi estão disponíveis.

Bluetooth:

    É uma tecnologia sem fio que permite que os dispositivos se comuniquem em distâncias pequenas. É possível conectar vários dispositivos ao mesmo tempo com Bluetooth.

É uma tecnologia de comunicação sem fio que permite a troca de dados entre dispositivos que estejam bem próximos uns dos outros, normalmente apenas alguns centímetros.

----------------------------------------------------------------

Conectividade de dispositivo móvel: Quase todos os dispositivos móveis podem se conectar a redes Wi-Fi. É preciso tomar essas precauções para proteger as comunicações Wi-Fi em dispositivos móveis:

    Nunca envie informações de login ou senha usando um texto não criptografado (texto simples).

    Use uma conexão VPN quando possível se você estiver enviando dados confidenciais.

    Ative a segurança em redes domésticas.

    Use criptografia WPA2 ou superior para segurança.

Apple iOS e Android são os dois dos sistemas operacionais mais conhecidos para dispositivos móveis. Os dispositivos móveis são pré-programados para usar uma rede Wi-Fi para Internet (se houver uma disponível) e o dispositivo pode se conectar ao access point e receber um endereço IP. Se não existir uma rede Wi-Fi disponível, o dispositivo usará o recurso de dados móveis configurado.

A tecnologia Bluetooth proporciona um modo simples para os dispositivos móveis se conectarem uns aos outros e a acessórios sem fio. O Bluetooth é sem fio, automático e usa muito pouca energia, o que ajuda a economizar a bateria. Alguns exemplos de dispositivos que usam Bluetooth incluem fones de ouvido, teclados, mouse, controles de som, alto-falantes para carros e alto-falantes móveis.

O pareamento Bluetooth ocorre quando dois dispositivos Bluetooth estabelecem uma conexão para compartilhar recursos. Para que os dispositivos se emparelhem, os rádios Bluetooth são ativados e um dispositivo começa a procurar outros dispositivos. Outros dispositivos devem estar configurados no modo detectável, também chamado visível, para que possam ser detectados.

Quando um dispositivo Bluetooth está no modo detectável, ele transmite as seguintes informações quando outro dispositivo Bluetooth as solicita:

    Nome

    Classe de Bluetooth

    Serviços que o dispositivo pode usar

    Informações técnicas, como funcionalidades ou a especificação de Bluetooth compatível

Durante o processo de emparelhamento, um PIN pode ser solicitado para autenticar o processo de emparelhamento.

## 03 - Contruindo uma rede móvel
Configurar um roteador sem fio integrado e cliente sem fio para estabelecer uma conexão segura com a internet.

Em uma rede doméstica, há diferentes dispositivos conectados na residência, em sua maioria, todos conectados a um único roteador conectado a uma rede de internet ou rede DSL. Dispositivos como: Computadores Desktop, impressoras, TV's, Camêras e afins, todos conectados a mesma rede fornecendo conectivade e controle. Esses são os chamados Home Wirelles Local Area Network (WLAN).

O switch em residências e pequenas empresas, normalmente, tem duas portas principais:

Porta Ethernet (LAN):

    São as portas de "saída" do switch onde, conectando os cabos de rede, fornecem internet para outros dispositovos, como citados anteriormente (TV's, impressoras, scanners e afins).

Porta Internet (WAN):

    Usada também via cabo para conectar o roteador a internet e assim, fornecer rede para o modem que assim, fornecerá para o resto da residência.

Fora as portas LAN que fornecem internet via cabo, há dispositivos com antenas que efetuam o mesmo serviço de internet para a residência, mas de forma wireless (Wi-FI) para outros dispositivos.

Tecnologias sem fio em residências, são comumente usadas na frequência de 2,4GHz e 5Ghz.

Já se tratando de internet com fio, é uma conexão mais "segura" visto que a perca de dados é menor e, além disso, há diferentes tipos de cabos para uso.

Cabo de categoria 5e:

    É o cabo mais comum de se ver no mercado, para residências e micro empresas e escritório. Composto de 4 pares de fios que são trançados para reduzir a interfêrencia elétrica, podem ser usados com os conectores RJ-45, podendo ser comprados em diferentes metragens.

Cabo coaxial:

    Hoje, não tão utilizado quanto antes, mas há algumas utilidades para o mesmo, visto que muitos dispositivos ainda tem sua conexão como conexão principal. Possui um fio interno circundado por uma camada isolante tubular, que é então circundada por uma blindagem condutora tubular.

Cabo de fibra-óptica:
    
    Um dos mais modernos utilizados nos dias de hoje, com melhor tempo-reposta entre os citados, tem a melhor conexão de internet e transfêrencia de dados. Podendo ser de vidro ou plástico, tem um diâmetro aproximado ao de um fio de cabelo.

----------------------------------------------------------------

## 04 - Configuração de redes sem fio

Conceitos básicos de rede doméstica:

    Uma rede doméstica conecta dispositivos (computadores, celulares, TVs, impressoras) para compartilhar internet, arquivos e serviços. Normalmente usa um roteador, que gerencia a comunicação entre os dispositivos internos e a conexão com a internet (ISP). Cada dispositivo recebe um endereço IP para se identificar na rede.

Tecnologias de rede na residência:

    As redes domésticas podem usar conexões cabeadas (Ethernet) ou sem fio (Wi-Fi). Ethernet oferece mais estabilidade e velocidade, enquanto o Wi-Fi traz mobilidade e praticidade. O roteador doméstico geralmente combina roteador, switch, ponto de acesso wireless e firewall em um único equipamento.

Padrões de rede sem fio:

    As redes Wi-Fi seguem padrões IEEE 802.11, como 802.11b/g/n/ac/ax. Cada padrão define velocidade, alcance e eficiência. Os mais comuns hoje são 802.11n (Wi-Fi 4), 802.11ac (Wi-Fi 5) e 802.11ax (Wi-Fi 6), que oferecem melhor desempenho e suporte a vários dispositivos conectados.

Configurar um roteador doméstico:

    A configuração básica envolve acessar o roteador pelo navegador, definir nome da rede (SSID), escolher um tipo de segurança (WPA2 ou WPA3) e criar uma senha forte. Também é importante alterar o usuário e senha padrão do roteador, atualizar o firmware e posicionar o equipamento em um local central para melhor cobertura do Wi-Fi.
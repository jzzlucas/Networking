# Rede | Networking


• Network é uma conexão. Ex.: Circulo de amigos.

  Essa conexão pode estar no seu computador com o telefone, no telefone com a câmera de segurança, etc.
  Esse conceito de conexão é essencial para entender a segurança cibernética.
  
  (APENAS DISPOSITIVOS CONECTADOS!)

## Internet 


• Internet é uma rede gigante de conexões com várias outras redes pequenas dentro dela,

  Em muitas redes, há conexões isoladas. Para integrá-las, é necessário um intermediário (mensageiro).
  Agora que há um intermediário para essas conexões, novas conexões podem ser criadas por meio dele.
 
 
## Identificando dispositivos em uma rede | Identifying Devices on a Network


• Para se comunicar e manter a ordem, os dispositivos devem ser identificadores e identificáveis em uma rede. Caso contrário, você não saberá com quem está se comunicando.

• Assim como nós, seres humanos, também temos como ser identificados. Ex: Nome, Impressão Digital, Biometria, etc.
 
• Porém temos como mudar o nome por meio de cartorio , mas a impressão digital nunca mudara!
 
• Dispositivos também possuem dois meios de identificação, sendo um deles facilmente acessível.São eles:

  • O Endereço de IP
  • E o Media Access Control | endereço de controle de acesso à mídia ( MAC ) - pense nisso como número de série .


## Endereço de IP | IP Addresses


• Um endereço IP é um endereço exclusivo que identifica um dispositivo na Internet ou em uma rede local.

### Se aprofundando

• Um endereço IP é um conjunto de números divididos em quatro octetos, identificando um dispositivo em uma rede. Esses endereços são calculados por meio de endereçamento IP e sub-rede, e embora possam mudar de dispositivo, não podem ser usados simultaneamente por mais de um dispositivo na mesma rede. 

• Os endereços IP seguem padrões de protocolos, permitindo que vários dispositivos se comuniquem no mesmo idioma. Dispositivos podem estar em redes privadas ou públicas, resultando em endereços IP públicos (identificação na Internet) ou privados (identificação entre dispositivos na rede local).

• Endereços IP públicos são fornecidos pelo seu Provedor de Serviços de Internet (ou ISP) por uma taxa mensal (sua conta!).

• Até agora, discutimos apenas uma versão do esquema de endereçamento do Protocolo de Internet conhecido como IPv4.


### IPv6


• O IPv6 é uma nova iteração do esquema de endereçamento do Protocolo de Internet.

• O IPv6 foi criado principalmente para resolver a escassez de endereços IPv4.Com o crescimento exponencial da Internet e o aumento do número de dispositivos conectados, o espaço de endereçamento do IPv4 (32 bits) se tornou insuficiente.

• O IPv6, com seus endereços de 128 bits, oferece um número praticamente ilimitado de endereços únicos, permitindo a expansão contínua da Internet e a conexão de um número maior de dispositivos.

## Endereços MAC | MAC Addresses

• Todos os dispositivos em uma rede terão uma interface de rede física, que é uma placa de microchip encontrada na placa-mãe do dispositivo. Esta interface de rede recebe um endereço exclusivo na fábrica em que foi construída, chamado de endereço MAC (Media Access Control). 

• O endereço MAC é um número hexadecimal de doze caracteres (um sistema de numeração de base dezesseis usado na computação para representar números) dividido em dois e separado por dois pontos. Esses dois pontos são considerados separadores. Por exemplo, a4:c3:f0:85:ac:2d. Os primeiros seis caracteres representam a empresa que fez a interface de rede, e os últimos seis são um número exclusivo

• No entanto, uma coisa interessante sobre endereços MAC é que eles podem ser falsificados ou "falsificados" em um processo conhecido como spoofing.


### Spoofing


• Esse spoofing ocorre quando um dispositivo em rede finge se identificar como outro usando seu endereço MAC.

• Quando isso ocorre, frequentemente pode comprometer projetos de segurança mal implementados que assumem que todos os dispositivos na rede são confiáveis.

• Considere o seguinte cenário: um firewall está configurado para permitir qualquer comunicação que venha do endereço MAC do administrador e vá para ele.

• Se um dispositivo mascarasse ou "falsificasse" seu endereço MAC, o firewall acreditaria estar se comunicando com o administrador, quando na verdade não está.

## Ping

• O ping usa pacotes ICMP (Internet Control Message Protocol) para determinar o desempenho de uma conexão entre dispositivos, por exemplo, se a conexão existe ou é confiável.

• O tempo gasto para pacotes ICMP viajando entre dispositivos é medido pelo ping, como na captura de tela abaixo. Essa medição é feita usando o pacote de eco do ICMP e, em seguida, a resposta de eco do ICMP do dispositivo de destino.


<img src="https://blogsigbol.wordpress.com/wp-content/uploads/2018/04/giphy.gif" alt="Descrição da Imagem">

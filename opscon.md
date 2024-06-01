# Introdução

O sistema de segurança domiciliar especificado neste documento visa aumentar a proteção da propriedade privada e seus residentes. Este sistema atualmente monitora os dois acessos à casa e os dois acessos ao terreno, mas está apto a monitorar outras áreas da propriedade futuramente. O sistema prioriza efetividade de custos, resistência a ameaças externas e tolerância a falhas. Este documento descreve os objetivos, requisitos, ambientes e cenários do sistema.

# Visão geral

Este sistema de segurança domicilar monitora a área externa da residência do proprietário. As imagens são capturadas através de câmeras e são enviadas a um servidor conectado à rede local. O servidor disponibiliza as imagens em tempo real dentro da rede local e as armazena para revisão posterior.

# Objetivos

- Monitorar os acessos à casa e ao terreno ininteruptamente
- Transmitir as imagens em tempo real para o dono da propriedade
- Gravar as imagens de monitoramento para revisão posterior

# Usuários

O único usuário do sistema é o proprietário da residência. Além de usar o sistema, o proprietário também é responsável por instalar e configurar todos os dispositivos e softwares, bem como realizar a manutenção corretiva e preventiva dos mesmos.

# Requisitos

## Funcionais

O sistema deve:

- Capturar as imagens das portas que dão acesso à casa
- Capturar as imagens dos portões que dão acesso ao terreno
- Capturar as imagens continuamente, 24 horas por dia, 7 dias por semana
- Capturar as imagens em proporção 1-por-1, 4-por-3 ou 16-por-9
- Capturar as imagens em resolução igual ou superior a 720 pixels de largura
- Capturar as imagens em pelo menos 25 frames por segundo
- Armazenar as imagens de todas as câmeras por pelo menos 12 horas
- Operar sem fornecimento de energia da rede pública por pelo menos 6 horas
- Operar sem acesso a quaquer outra rede além da rede local da residência
- Disponibilizar as imagens em tempo real via interface web na rede local
- Disponibilizar as imagens armazenadas via interface web na rede local
- Disponibilizar as imagens para qualquer dispositivo conectado à rede local
- Exigir autenticação por senha para acessar as imagens
- Consumir até 400W de potência

## Não-funcionais

O sistema deve:

- Ser inacessível fora da rede local para um atacante utilizando nmap 7.95
- Ser compatível com o sistema operacional Debian Bookworm
- Ser escalável para 10 câmeras

# Descrição

O sistema consiste em:

- Câmeras de monitoramento externo
- Servidor para processamento e armazenamento das imagens
- Switch para comunicação entre as câmeras e o servidor
- UPS para provisão de energia
- Software de monitoramento para acesso e configuração das câmeras

As câmeras são instaladas em pontos estratégicos dentro da propriedade a fim de monitorar as áreas de acesso. A comunicação entre as câmeras e o servidor ocorre por meio de um switch. As imagens são armazenadas no servidor e podem ser acessadas ao vivo pelo proprietário através da rede interna.

# Plano de manutenção

## Preventiva

TODO

## Corretiva

TODO

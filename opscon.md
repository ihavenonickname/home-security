# Introdução

O sistema de segurança domiciliar especificado neste documento visa aumentar a proteção da propriedade privada e seus residentes. Este sistema conta inicialmente com duas câmeras e está apto para ser expandido, e prioriza efetividade de custos, resistência a ameaças externas e tolerância a falhas. Este documento descreve os objetivos, requisitos, ambientes e cenários do sistema.

# Visão geral

Este sistema de segurança domicilar monitora área externa da casa do proprietário. As imagens são captadas através de câmeras e são enviadas a um servidor conectado à rede local. As imagens são disponibilizadas em tempo real e armazenadas no servidor.

# Objetivos

- Monitorar áreas externas da propriedade ininteruptamente
- Transmitir as imagens em tempo real para o dono da propriedade
- Gravar as imagens de monitoramento para revisão posterior

# Requisitos

## Funcionais

- Capturar as imagens em proporção 1-por-1, 4-por-3 ou 16-por-9
- Capturar as imagens em resolução igual ou superior a 720 pixels de largura
- Armazenar as imagens de todas as câmeras por pelo menos 12 horas
- Operar por pelo menos 6 horas sem fornecimento de energia pública
- Operar sem acesso a quaquer outra rede além da rede local da residência
- Disponibilizar as imagens em tempo real via interface web na rede local
- Disponibilizar as imagens armazenadas via interface web na rede local
- Disponibilizar as imagens para qualquer dispositivo conectado à rede local
- Bloquear o acesso às imagens via internet
- Exigir autenticação por senha para acessar as imagens

## Não-funcionais

- Ser resistente a ataques cibernéticos
- Ser resistente a quedas de energia
- Ser resistente a falhas de hardware
- Ser econômico energeticamente
- Ser econômico financeiramente

# Descrição

O sistema de segurança domiciliar consiste em:

- Câmeras de monitoramento externo
- Servidor para processamento e armazenamento das imagens
- Switch para comunicação entre as câmeras e o computador servidor
- UPS para provisão de energia
- Software de monitoramento para acesso e gestão das câmeras

As câmeras são instaladas em pontos estratégicos dentro da propriedade a fim de monitorar as áreas de acesso. A comunicação entre as câmeras e o servidor ocorrem através de cabos a fim de evitar ataques de jamming. As imagens são armazenadas no servidor e podem ser acessadas ao vivo pelo proprietário através da rede interna.

# Plano de manutenção

TODO

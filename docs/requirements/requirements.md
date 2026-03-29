# Requisitos do Sistema

## Requisitos Funcionais (RF)

RF01 - O sistema deve permitir cadastro de usuários  
RF02 - O sistema deve permitir login com autenticação segura  
RF03 - O usuário deve registrar problemas urbanos  
RF04 - O usuário deve anexar imagens  
RF05 - O sistema deve registrar localização do problema  
RF06 - O sistema deve listar problemas cadastrados  
RF07 - O sistema deve permitir filtragem por status  
RF08 - O administrador deve atualizar status  
RF09 - O sistema deve notificar alterações  
RF10 - O sistema deve permitir histórico de solicitações  

## Requisitos Não Funcionais (RNF)

RNF01 - Interface responsiva  
RNF02 - Disponibilidade 24/7  
RNF03 - Tempo de resposta < 3 segundos  
RNF04 - Segurança com criptografia de senha  
RNF05 - Escalabilidade  
RNF06 - Usabilidade intuitiva  

## Regras de Negócio

- Apenas usuários autenticados podem registrar problemas  
- Administradores podem alterar status  
- Problemas devem conter descrição e localização  

## Perfis de Usuário

- Morador
- Administrador

## Histórias de Usuário

Como morador, quero registrar um problema para que ele seja resolvido rapidamente.  
Como administrador, quero gerenciar os problemas para organizar a solução.

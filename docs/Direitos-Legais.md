# Documento de Compliance, Governança e Diretrizes Legais  

**Disciplina**: Interação Humano Computador e UX nosso projeto para o objetivo da A3 (Ghojun)

**Integrantes da nossa equipe**: Carlos Henrique Alves Pereira (RA):12825138913, Carlos Eduardo Cavalcante Ramalho (RA):128251338995, Miguel Lucas Martins (Ra): 12825132678, Otávio Miranda Galvão (RA)12826120271

**Professores da Disciplina**: Hideljundes Macedo Paulino, Wanfranklin de Carvalho Moreira Alves




## GHOJUN – Plataforma de Música e Comunicação em Tempo Real

**1. Apresentação do Projeto**
O Ghojun é uma plataforma digital de streaming musical integrada com ferramentas de comunicação em tempo real, desenvolvida em 10 de junho de 2026. O projeto foi concebido com foco em acessibilidade tecnológica, visando atender usuários que utilizam computadores e dispositivos móveis com recursos limitados de hardware.

Diferentemente de aplicações tradicionais que demandam grande capacidade de processamento e memória, o Ghojun prioriza a otimização de desempenho, oferecendo uma experiência fluida mesmo em equipamentos de entrada. Sua arquitetura foi projetada para minimizar o consumo de memória RAM, processamento e tráfego de dados, sem comprometer a qualidade dos serviços oferecidos.

A proposta central da plataforma é proporcionar um ambiente onde usuários possam ouvir músicas simultaneamente com seus amigos enquanto interagem por meio de chats de texto e voz, promovendo experiências sociais mais dinâmicas e colaborativas.


**2. Objetivos**
O principal objetivo do Ghojun é unir entretenimento musical e comunicação digital em uma única plataforma, permitindo que usuários compartilhem momentos, conversem e consumam conteúdo musical de forma sincronizada.

Entre os objetivos específicos do projeto destacam-se:
-	Disponibilizar uma biblioteca musical de fácil acesso.
-	Permitir comunicação instantânea por texto e voz.
-	Proporcionar sessões de escuta compartilhada entre amigos.
-	Reduzir o consumo de recursos computacionais.
-	Garantir compatibilidade com dispositivos de baixo desempenho.
-	Oferecer uma experiência intuitiva e acessível para diferentes perfis de usuários.

**3. Público-Alvo**
O Ghojun foi desenvolvido para atender principalmente dois grupos de usuários:
Jovens e adolescentes
Usuários que buscam entretenimento, socialização e momentos de descontração através da música e da comunicação online.
Jovens adultos e profissionais
Usuários que necessitam de ferramentas de comunicação para reuniões, grupos de estudo, projetos colaborativos ou encontros virtuais, utilizando recursos de voz, texto e compartilhamento de conteúdo.

**4. Diferenciais Competitivos**
Os principais diferenciais do Ghojun são:

-	Baixo consumo de memória RAM.
-	Otimização para computadores e smartphones de entrada.
-	Integração entre música, mensagens e chamadas de voz.
-	Sistema de escuta compartilhada sincronizada.
-	Interface simplificada e intuitiva.
-	Compatibilidade multiplataforma.
-	Comunicação em tempo real.
-	Arquitetura escalável para crescimento futuro da plataforma.

**6. Principais Funcionalidades**
A plataforma será composta pelos seguintes módulos:

- Biblioteca Musical
- Permite que usuários pesquisem, reproduzam e organizem músicas, artistas, álbuns e playlists.
- Sistema de Amizades
- Permite que usuários adicionem amigos, acompanhem atividades e compartilhem conteúdo musical.
- Chat de Texto
- Sistema de mensagens privadas e em grupo para comunicação instantânea.
- Chat de Voz
- Ferramenta de comunicação por voz com suporte para chamadas individuais e salas coletivas.
- Escuta Compartilhada
- Funcionalidade que permite que diversos usuários escutem músicas sincronizadas simultaneamente.
- Sistema Administrativo
- Ferramentas de moderação, monitoramento e gerenciamento da plataforma.

**7. Requisitos Funcionais**:

   
- *6.1 Cadastro e Autenticação*:


RF001 – Cadastro de usuário
O sistema deve permitir que usuários criem uma conta utilizando e-mail, telefone ou login social.

RF002 – Login
O sistema deve permitir autenticação por e-mail/senha ou provedores externos.

RF003 – Recuperação de senha
O sistema deve permitir redefinição de senha por e-mail ou SMS.

RF004 – Gerenciamento de perfil
O usuário deve poder editar foto, nome, biografia e preferências musicais.


- *6.2 Reprodução de Música*:


RF005 – Busca de músicas
O sistema deve permitir pesquisar músicas, artistas, álbuns e playlists.

RF006 – Reprodução de músicas
O sistema deve reproduzir músicas sob demanda.

RF007 – Controle de reprodução
O usuário deve poder reproduzir, pausar, avançar, retroceder e ajustar volume.

RF008 – Fila de reprodução
O usuário deve poder adicionar músicas à fila de reprodução.

RF009 – Reprodução em segundo plano
O sistema deve permitir continuar a reprodução mesmo com o aplicativo minimizado.

RF010 – Favoritos
O usuário deve poder marcar músicas, álbuns e artistas como favoritos.


- *6.3 Playlists*:


RF011 – Criar playlist
O usuário deve poder criar playlists personalizadas.

RF012 – Editar playlist
O usuário deve poder alterar nome, capa e descrição de playlists.

RF013 – Adicionar músicas
O usuário deve poder adicionar ou remover músicas das playlists.

RF014 – Compartilhar playlist
O usuário deve poder compartilhar playlists com outros usuários.

RF015 – Playlist colaborativa
O sistema deve permitir que múltiplos usuários editem uma playlist compartilhada.


- *6.4 Rede Social e Amigos*:


RF016 – Adicionar amigos
O usuário deve poder enviar e aceitar solicitações de amizade.

RF017 – Lista de amigos
O sistema deve exibir a lista de amigos do usuário.

RF018 – Remover amigos
O usuário deve poder remover contatos da lista de amigos.

RF019 – Visualizar atividade
O usuário deve poder visualizar o que seus amigos estão ouvindo.

RF020 – Compartilhar música com amigos
O usuário deve poder enviar músicas diretamente para outros usuários.


- *6.5 Chat de Texto*:


RF021 – Conversa privada
O sistema deve permitir troca de mensagens privadas entre amigos.

RF022 – Conversas em grupo
O sistema deve permitir criação de grupos de conversa.

RF023 – Envio de emojis
O usuário deve poder enviar emojis nas mensagens.

RF024 – Compartilhamento de músicas
O usuário deve poder compartilhar músicas dentro do chat.

RF025 – Indicador de leitura
O sistema deve exibir quando uma mensagem foi entregue e visualizada.

RF026 – Notificações
O sistema deve notificar o recebimento de novas mensagens.


- *6.6 Chat de Voz*:


RF027 – Chamada de voz individual
O sistema deve permitir chamadas de voz entre dois usuários.

RF028 – Sala de voz em grupo
O sistema deve permitir salas de voz com múltiplos participantes.

RF029 – Controle de microfone
O usuário deve poder ativar ou desativar seu microfone.

RF030 – Convite para sala de voz
O usuário deve poder convidar amigos para participar de uma sala de voz.

RF031 – Exibição de participantes
O sistema deve exibir os participantes presentes na sala.

RF032 – Moderação de sala
O criador da sala deve poder remover participantes.


- *6.7 Escuta Compartilhada*:


RF033 – Sessão compartilhada
O usuário deve poder criar uma sessão para ouvir músicas junto com amigos.

RF034 – Sincronização da reprodução
O sistema deve sincronizar a reprodução da música para todos os participantes.

RF035 – Controle colaborativo
Participantes autorizados devem poder controlar a música reproduzida.

RF036 – Chat durante a reprodução
O sistema deve permitir interação por texto e voz durante a sessão.


- *6.8 Notificações*:


RF037 – Notificações de amizade
O sistema deve notificar novas solicitações de amizade.

RF038 – Notificações de mensagens
O sistema deve notificar novas mensagens recebidas.

RF039 – Notificações de chamadas
O sistema deve alertar usuários sobre chamadas recebidas.

RF040 – Notificações de compartilhamento
O sistema deve informar quando uma música ou playlist for compartilhada.


- *6.9 Administração*:


RF041 – Gerenciar usuários
Administradores devem poder suspender ou bloquear contas.

RF042 – Moderação de conteúdo
Administradores devem poder remover conteúdos inadequados.

RF043 – Relatórios
O sistema deve gerar relatórios de uso, reprodução e interações sociais.


**7. Requisitos Não Funcionais**

   
Os requisitos não funcionais estabelecem os padrões de qualidade, desempenho, segurança e confiabilidade do sistema.


- *7.1 Desempenho*:


RNF001 ao RNF005 – Tempo de resposta, carregamento de músicas, entrega de mensagens em tempo real, latência de voz e escalabilidade.


- *7.2 Disponibilidade e Confiabilidade*:


RNF006 ao RNF009 – Disponibilidade mínima de 99,5%, recuperação de falhas, backups automáticos e integridade dos dados.


- *7.3 Segurança:*


RNF010 ao RNF014 – Criptografia HTTPS/TLS, armazenamento seguro de senhas, controle de acesso, conformidade com a LGPD e autenticação multifator.


- *7.4 Usabilidade*:


RNF015 ao RNF018 – Facilidade de uso, interface intuitiva, consistência visual e acessibilidade.


- *7.5 Compatibilidade*:


RNF019 ao RNF021 – Compatibilidade com Android, iOS, navegadores modernos e diferentes resoluções.


- *7.6 Manutenibilidade*:


RNF022 ao RNF025 – Modularização, documentação, testes automatizados e atualizações seguras.


- *7.7 Escalabilidade*:


RNF026 ao RNF028 – Crescimento de usuários, balanceamento de carga e infraestrutura em nuvem.


- *7.8 Qualidade de Áudio*:


RNF029 ao RNF031 – Streaming de qualidade, cancelamento de ruído e continuidade da reprodução.


- *7.9 Notificações*:


RNF032 ao RNF033 – Entrega eficiente e personalização das notificações.


- *7.10 Monitoramento*:


RNF034 ao RNF036 – Registro de eventos, monitoramento contínuo e alertas automáticos.


*8. Prototipagem UI/UX*:

Abaixo as principais telas que o usuário verá

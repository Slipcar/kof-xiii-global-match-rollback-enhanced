# KOF XIII Global Match Rollback Enhanced
Projeto de melhoria do rollback netcode do KOF XIII

<img width="1280" height="600" alt="image" src="https://github.com/user-attachments/assets/da0f5d28-1bb3-4666-8e36-76c9c482b295" />

Como usar
---------
- Execute o arquivo com o jogo fechado, ele abre o jogo pela Steam.
- Aperte START na tela "PRESS START".

O que faz:
- corrige falhas e atrasos do rollback do jogo somente em partidas online.

Fora do online não mexe em nada. 
Ao fechar, o jogo volta ao normal que você usava.
O lobby mostra para os outros jogadores do Rollback o seu nome da Steam e se você está no cabo ou no Wi-Fi.

Como usar
---------
0. Extraia o .zip numa pasta só do Rollback: o programa e a pasta "ferramenta_de_treino" ficam juntos.

1. Abra o rollback_kofxiii_by_Slipcar_v(versão).exe com o jogo fechado, ele abre o jogo pela Steam e pula a apresentação até a tela PRESS START.

   ### Dentro do Lobby:
    - "VOLTAR AO JOGO" leva para o menu do KOF; para reabrir o lobby aperte F10 ou START no controle.
    - Quando o jogo fecha, o Rollback fecha junto.
    - Use o jogo em Windowed Fullscreen: em tela cheia exclusiva (Fullscreen) não funciona 
    - Para colocar em Windowed Fullscreen vá em: Options > Graphics Options > Display Mode > Windowed Fullscreen.

3. Jogue online normalmente.   
   - ACESSO: o Rollback usa a conta Steam aberta no PC (a mesma do jogo); não há senha.
   - Só a versão mais recente funciona: se a tela disser "VERSÃO ANTIGA", baixe a nova.

4. LOBBY: no lobby ficam as SALAS (a "Sala Geral" sempre aberta e as que os
   jogadores criam em "+ CRIAR SALA"; uma sala criada some quando fica vazia), quem
   está online (avatar, cabo/Wi-Fi, livre, em luta ou em qual sala) e o chat do lobby.
   
   - Clique no seu nome para escolher o seu AVATAR (aparece ao lado do seu nome para todos).
   - Clique em outro jogador para ADICIONAR NA STEAM (pedido de amizade) ou VER PERFIL. A lista mostra todos que usam o Rollback, mesmo quem não é seu amigo.
   - SALA PRIVADA: ao criar, ligue "PRIVADA: SIM" e, se quiser, uma senha. Quem tem a senha entra direto; quem não tem clica em "PEDIR PARA ENTRAR" e o dono da sala aceita ou recusa. Vale para mesas 1 contra 1, Rei do Fliper e torneio.
   - SALA: cada sala tem 4 mesas de 1 contra 1. Clique num lugar vazio para sentar (no seu lugar, para levantar). Quando alguém senta na sua frente, abre o CONFRONTO. A sala tem o próprio chat.
   - DESAFIO DIRETO: também dá para clicar em "DESAFIAR" ao lado de um jogador livre. 
   - No CONFRONTO (pela mesa ou pelo desafio) os dois só marcam PRONTO. Com os dois prontos, o lobby continua por cima do jogo enquanto:
     - o jogo do ANFITRIÃO (quem sentou primeiro na mesa, ou quem desafiou) cria a sala sozinho (uns 10 segundos);
     - o jogo do outro entra nela sozinho (pela Steam).
   
   A sala do jogo é privada e tem 9 lugares (para quem quiser assistir). Com os dois nela, o Rollback faz o desafio sozinho: quem entrou desafia o anfitrião e o jogo do anfitrião aceita. O lobby sai da frente na seleção de personagens.
   - Se não der certo, o lobby sai antes e avisa o que apertar.
   - Dentro da sala do jogo e entre as lutas, F10 e START ficam com o jogo (START é a revanche); quando os dois saem da sala, o lobby volta sozinho.
   
   REI DO FLIPER: em "+ CRIAR SALA" escolha "REI DO FLIPER" e quantas fichas cada um tem (1 a 5). 
    - Quem cria organiza: os jogadores entram na sala e clicam em "INSCREVER-SE"; o organizador clica em "COMEÇAR". A fila é sorteada e as lutas começam. 
    - O 1º da fila (o rei) contra o 2º. Quem vence fica na mesa; quem perde vai para o fim da fila e perde uma ficha. Sem fichas, está fora. 
    - Quando for a sua vez, toca o som de "novo desafiante" e abre a tela: marque PRONTO em até 90 segundos (senão você desiste). 
    - Sair da sala, DESISTIR DO FLIPER ou cair também elimina. Não pode jogar agora? PASSAR A VEZ: você perde só essa luta (uma ficha, fim da fila). 
    - O organizador pode PULAR A VEZ de alguém (vai para o fim da fila sem perder ficha) ou DESCLASSIFICAR. 
    - O último que sobrar é o REI DO FLIPER.
   
   TORNEIO: em "+ CRIAR SALA" escolha "TORNEIO" (dupla eliminação, de 8 a 32 jogadores; o botão "MÍNIMO: 8" vira "MÍNIMO: 3" para testes com poucas pessoas). 
    - Quem cria organiza: os jogadores entram e clicam em "INSCREVER-SE"; o organizador clica em "COMEÇAR".
    - A chave é sorteada (com "bye" quando o número de jogadores não é par) e o servidor chama as lutas sozinho, várias ao mesmo tempo. 
    - Final dos vencedores, final dos perdedores e grande final são FT-3; as outras lutas, FT-2. 
    - Perdeu 2 vezes, está fora. 
    - Se quem veio da chave dos perdedores ganhar a grande final, tem uma segunda grande final (reset). 
    - Quando for a sua luta, você é avisado: marque PRONTO em até 90 segundos (quem não marcar perde essa luta por W.O.). 
    - PASSAR A VEZ perde só a luta atual; 
    - DESISTIR DO TORNEIO tira você de vez (as próximas lutas viram W.O.).
    - O torneio pode durar dias: sair da sala ou fechar o jogo não elimina, a sua luta espera você voltar ao lobby. 
    - O organizador clica numa luta para PULAR A LUTA(adiar até ele chamar de novo) ou DESCLASSIFICAR um jogador, e pode ENCERRAR O TORNEIO. 
    - LINK DAS CHAVES copia um endereço para ver as chaves e os resultados no navegador (dá para mandar no Discord/WhatsApp). A chave aparece na sala, em abas: VENCEDORES, PERDEDORES e GRANDE FINAL.

5. Para fechar: feche o jogo (o Rollback fecha junto), segure ESPAÇO e aperte ESC, ou clique no ícone do Rollback na bandeja (perto do relógio) > Encerrar.
   - O jogo volta ao normal sem os aprimoramentos do rollback.

6. Clique em "enviar logs" no rodapé do lobby (ou envie a pasta "logs" que fica ao lado do programa) e diga como sentiu os comandos (leve, pesado, travadas).

 - ATUALIZAÇÃO AUTOMÁTICA (versão da comunidade, v1.x.x): ao abrir, o programa procura a versão mais nova no GitHub. Se houver, mostra a versão instalada e a nova, baixa (junto com a ferramenta de treino, se ela mudou), apaga a antiga e reabre sozinho.
 - FERRAMENTA DE TREINO: o botão ESPERAR NO TREINO também abre o overlay de hitboxes, frame data, rewind e IA (Hitboxes by Slipcar). Ele fica na pasta "ferramenta_de_treino", ao lado do programa, com os arquivos dele na pasta "dados".  
   - Shift+F1 mostra os atalhos e Shift+Esc fecha. 
   - O F10 continua abrindo o lobby: na ferramenta,
   - No online, a ferramenta de treino fica desligada.

 - CONTROLE NO LOBBY: direcional ou analógico move o destaque pelos botões, A (ou o chute fraco) confirma e B (ou o chute forte) fecha a janela aberta.

LINUX (Steam com Proton) - em teste
-----------------------------------
O Rollback é um programa do Windows: ele precisa rodar DENTRO do mesmo Proton do jogo(é assim que ele enxerga o jogo e a sua conta Steam).

Dicas
-----
- Jogue com cabo de rede: no Wi-Fi o jogo pode travar alguns segundos com "sincronizando...", e nenhum programa resolve isso.
- O antivírus pode reclamar. Se isso acontecer, libere a pasta do Rollback no antivírus.
- Em tela cheia exclusiva o HUD e o lobby não aparecem: use Windowed Fullscreen.

# AVISO LEGAL

- Projeto de fã, gratuito e independente. Não é afiliado, patrocinado nem aprovado pela SNK
  (dona de The King of Fighters XIII), pela Valve (Steam) ou por qualquer outra empresa ligada
  ao jogo. Nomes, marcas e imagens do jogo pertencem aos seus donos.

- É preciso ter o KOF XIII Global Match original, comprado na Steam. O Rollback não contém
  nem distribui o jogo e não serve para jogar sem ele.

- O programa foi feito a partir do estudo de como o jogo funciona no PC (engenharia reversa),
  para melhorar a conexão nas partidas online e oferecer ferramentas para o treino e o replay.
  Ele não altera os arquivos instalados do jogo: as mudanças ficam na memória enquanto o
  Rollback está aberto e somem quando ele fecha.

- Não é trapaça: no online o Rollback mexe só na conexão, igual para os dois jogadores, e a
  ferramenta de treino fica desligada.

- Sua conta Steam: o Rollback nunca pede nem vê a sua senha. Do seu PC ele lê apenas o seu
  SteamID e o seu nome na Steam.

- O que vai para o servidor do lobby: SteamID, nome na Steam, avatar escolhido, país
  (estimado pela conexão), cabo ou Wi-Fi, versão do programa, ping, resultados e personagens
  das partidas e as mensagens do chat. Os logs só são enviados quando você clica em
  "enviar logs". Esses dados servem apenas para o lobby funcionar e para corrigir problemas.

- Programas de terceiros podem não ser permitidos pelos termos de uso do jogo ou da Steam.
  Use por sua conta e risco: o Rollback é oferecido como está, sem garantia, e o autor não se
  responsabiliza por problemas no jogo, no PC ou na conta.

# criador do script = H3C2E5

# pacotes.sh = faz instalacão de todos os pacotes necessarios
# pra funcionalidade do termux,o script coloca todos os pacotes
# sem precisar que você coloque tudo a mão toda vez que formatar
# o seu aparelho, ou desinstalar o termux do seu dispositivo

# COMANDOS PARA EXECUTAR

# Assim que entrar no seu termux, dê o comando

# termux-setup-storage

# esse comando vai dá permissão para que o termux tenha acesso
# ao seu gerenciador de arquivos

# em seguida veja se o script está na pasta download

# se estiver volte ao termux e digite

# ls

# cd storage

# cd downloads

# ls

# agora procure pela pasta "pacotes" e dê o comando

# mv -v pacotes /$HOME

# esse comando serve para mover a pasta "pacotes"
# pra tela inicial do termux "HOME"

# logo em seguida abra uma nova sessão dê o ls e faça esses
# comandos

# cd pacotes

# ls

# chmod +x *

# ls

# bash pacotes.sh ou ./pacotes.sh

# depois disso é somente responder com a letra "s"
# tudo que o script perguntar, ele só pergunta duas vezes
# depois de perguntado o script irá instalar tudo sozinho

# tenha um bom uso :)

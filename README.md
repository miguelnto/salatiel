# Salatiel

## A SER FEITO

- [ ] O comando `/carregar`só pode ser usado para piadas. É necessário atualizar para que ele também sirva para canais e cargos.

## Comandos

### GIFS

#### `/changemymind` - Simplesmente change my mind.

- **prompt** - A frase que deve ser exibida no meme.

#### `/pat` - Dê um cafuné em alguém.

- **membro** - O membro para qual o comando é destinado.

#### `/cuddle` - Dê um cuddle em alguém.

- **membro** - O membro para qual o comando é destinado.

#### `/smug` - Faz uma careta.

*Não tem parâmetros.*

#### `/slap` - Dá um tapa em alguém.

- **membro** - O membro para qual o comando é destinado.

#### `/hug` - Dá um abraço em alguém.

- **membro** - O membro para qual o comando é destinado.

#### `/kiss` - Dá um beijo em alguém.

- **membro** - O membro para qual o comando é destinado.

#### `/poke` - Dá um poke em alguém.

- **membro** - O membro para qual o comando é destinado.

#### `/eject` - Ejeta um membro da nave (AMONGAS).

- **membro** - O membro para qual o comando é destinado.

### Inteligência artificial

#### `/chat` - Converse com Salatiel!

- **prompt** - O prompt usado para gerar uma mensagem.

#### `/generate` - Gera uma imagem baseada no prompt.

- **prompt** - O prompt usado para gerar uma imagem.

### Gerenciamento da Database

#### `/restrict` - Ativa ou desativa o modo restrito do bot

*Não há parâmetros.*

#### `/addchannel` - Adiciona um canal para Salatiel responder no modo restrito.

- **canal** - O canal a ser adicionado. Se esse parâmetro não for passado, o canal onde este comando foi usado será adicionado.

#### `/deletechannel` - Deleta um canal para Salatiel responder no modo restrito.

- **canal** - O canal a ser deletado do modo restrito. Se esse parâmetro não for passado, o canal onde este comando foi usado será deletado DO MODO RESTRITO.

#### `/listchannels` - Lista todos os canais no modo restrito

*Não tem parâmetros.*

#### `/addrole` - Adiciona um cargo em uma lista especial.

- **cargo** - O cargo a ser adicionado.

#### `/deleterole` - Deleta um cargo em uma lista especial.

- **cargo** - O cargo a ser deletado.

#### `/listroles` - Lista todos os cargos em uma lista especial

*Não tem parâmetros.*

### Miscelânia

#### `/falar` - Escreva uma mensagem para o bot enviar

- **mensagem** - A mensagem a ser enviada.
- **canal** - O canal a ser enviado a mensagem. Caso esse parâmetro não seja passado, a mensagem será enviada no canal onde este comando foi usado.

#### `/gay` - Coloca um filtro gay na foto de perfil

- **membro** - O membro onde será aplicado o filtro. Se esse parâmetro não for passado, a sua foto de perfil será usada como referência.

#### `/wasted` - Coloca um filtro wasted na foto de perfil

- **membro** - O membro onde será aplicado o filtro. Se esse parâmetro não for passado, a sua foto de perfil será usada como referência.

#### `/bobfire` - Faz o bob esponja queimar alguma coisa

- **membro** - O membro onde será aplicado o filtro. Se esse parâmetro não for passado, a sua foto de perfil será usada como referência.

#### `/escolher` - Quer escolher alguma coisa? Deixa que eu escolho!

- **lista** - A lista da qual será escolhida alguma coisa. Os itens devem estar *separados por vírgula.* Exemplo: "marmelada de banana,uva,maçã,doce de abacate."

#### `/rolar` - Rola um ou mais dados. Funciona no formato "3d6".

- **dados** - Vai rolar o dado de acordo com o formato passado (exemplo: 4d5). Caso esse parâmetro não seja passado, será rolado um 1d6. Caso seja passado um número n, será rolado um 1dn (exemplo: para n=3, será rolado um 1d3).

### Piadas

#### `/addpiada` - Adiciona uma piada para a database.

- **piada** - A piada a ser passada. Caso sua piada tenha múltiplas linhas, elas devem ser separadas por `"\n"`. Se você quiser escrever a seguinte piada:

```
Porque a galinha atravessou a rua?
Porque?
Porque ela quis.
```

Escreva da seguinte forma: Porque a galinha atravessou a rua?\nPorque?\nPorque ela quis.

#### `/searchpiada` - Pesquisa até no máximo 10 piadas na database.

- **piada** - A piada a ser pesquisada. Pode ser uma sílaba, uma palavra, ou frase.

#### `/deletepiada` - Deleta uma piada na database de acordo com a posição.

- **posicao** - A posição da piada na database. Caso a posição seja desconhecida, você pode usar o comando `/searchpiada` para encontrar, que é o primeiro número que aparece antes do ponto.

#### `/ativarpiadas` - Ativa ou desativa o envio das piadas.

*Não tem paramêtros. Note que se as piadas estiverem ativadas, esse comando irá desativar, e vice-versa **também.***

#### `/getdb` - Devolve um arquivo txt da database.

- **arquivo** - O arquivo que você quer obter. Pode ser canais, cargos ou piadas. De acordo com o arquivo escolhido, o bot enviará um arquivo txt com a database inteira dos canais, cargos ou piadas.

#### `/carregar` - Carrega a database de piadas vinda de um arquivo txt.

*Não tem paramêtros. Para usar esse comando, envie um arquivo txt com as piadas e em seguida use `/carregar`*.

### Tickets

#### `/menuticket` - Cria um menu para a funcionalidade de ticket.

*Não tem parâmetros. O menu será enviado no canal onde este comando foi usado.*

### Outros

#### `/slowmode` - Ativa o modo lento, aonde o usuário deve esperar X segundos antes de enviar uma nova mensagem.

- **seconds** - A quantidade em segundos para qual será aplicado o modo lento.
- **minutes** - A quantidade em minutos para qual será aplicado o modo lento.
- **hours** - A quantidade em horas para qual será aplicado o modo lento.

ATENÇÃO: Se você, por exemplo, passar seconds=120 e minutes=5, será aplicado um modo lento de 7 minutos. Isso acontece pois 120 segundos são 2 minutos, e esses 2 minutos são somados com os 5.

#### `/changestatus` - Muda o status do bot

- **status** - Pode ser watching, playing, streaming ou listening.
- **texto** - O texto para aparecer após a atividade. Por exemplo, se o status for listening e o texto for "never gonna give you up", o bot terá um status "listening to never gonna give you up".


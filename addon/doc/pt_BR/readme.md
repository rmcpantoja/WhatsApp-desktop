﻿# Whatsapp desktop:
Este extra foi desenvolvido para facilitar o uso do aplicativo, adicionando atalhos de teclado para algumas funções importantes, bem como marcando alguns botões que não estão etiquetados.

v## Instruções e comandos:
Quando abre o WhatsApp Desktop ativará automaticamente o modo de foco. Pressionando "Shift+Tab", Após carregar o aplicativo, colocará o foco na lista de conversações, ondepodemos andar com as setas para cima e para baixo.
Nota: Este add-on só funciona com o modo de foco activo.

### atalhos do extra:

* Trazer a janela do WhatsApp para a frente; Sem atalho atribuído. pode ser adicionado a partir da caixa de diálogo "definir comandos", na categoria "WhatsApp".
* Abrir o WhatsApp; Sem atalho definido. Pode definir-se em "definir comandos", no menu do NVDA.
* Iniciar a gravação e enviar  uma mensagem de voz; Controlo + R.
* Iniciar e finalizar uma chamada de voz para o contacto da conversação sob o foco; alt + control + l. (apenas disponível na versão  store)
* Iniciar e finalizar uma chamada de vídeo para o contacto da conversação sob o foco; alt + control + v. (Apenas disponível na versão Store)
* Saber o tempo de gravação de uma mensagem de voz: controlo+t
* Copiar o texto da mensagem em foco; Controle + Shift + c.
* Abrir o link da mensagem em foco no navegador padrão; Controle + L.
* Abrir o menu Anexar; Controle + shift + a. Disponível apenas na caixa de edição de mensagens.
* Abrir o menu de conversações; Controle + m.
* Abrir o menu geral do WhatsApp; Controle + g.
* Reproduzir o vídeo na mensagem  sob o foco; control + shift + v.
* Reproduzir mensagens de voz com foco na barra de progresso; enter-
* Alternar entre as velocidades de reprodução de uma mensagem de voz: barra de espaço. 
* Saber o tempo de reprodução da mensagem de voz; Controle + t.
* Verbalizar o nome da conversação actual; Controle + shift + t.
* Baixar o ficheiro, se a mensagem contiver algum; alt+enter.
* Mover o foco para a mensagem respondida. Shift+Enter. Disponível apenas a partir de mensagens de voz.
* Retroceder 5 mensagem na lista; control + seta para cima
* Avançar 5 mensajes na lista; control + seta para baixo
* Ler a mensagem segundo a sua posição; alt + 1 até 9 (Só na caixa de ediçãode mensagens.
* Alternar o foco entre a lista de mensagens e o quadro de edição ao entrar numa conversação; alt + seta esquerda.
* Pressionar o botão ler mais nas mensagens de texto; alt + seta para baixo.
* Ativar e desativar o apagamento dos números de telefone nas mensajens de contactos não agendados; control + shift +r

### Atalhos do modo de edição

* Marcar e desmarcar a mensagem sob o foco; Barra de espaço.
* Verbalizar o número de mensagens seleccionadas; s.
* Reencaminhar as mensagens seleccionadas; r.
* Remover as mensagens seleccionadas; delete.
* Realçar as mensagens seleccionadas; d.
* Sair do modo de selecção; Q.

### atalhos gerais do aplicativo:

* Criar nova conversação; Controle + n.
* Activar a caixa de pesquisa de conversação; Controle + F.
* Arquivar uma conversação; Controle + E.
* Menu contextual de conversação; Seta direita.
* Concentrar-se na conversação seguinte; Controlo+tabulador.
* Concentrar-se na conversação anterior; Controlo+SHIFT+TAB.
* Apagar a conversação; Controle + Shift + D.
* Arquivar/desarquivar conversação; Controlo+Shift+p.
* Abrir o menu contextual da mensagem; Seta direita
* Activar a pesquisa de mensagens de conversação; Controlo+Shift+F.

## canal de actualizações:
A partir da versão 0.9, foi adicionado um canal de atualização que está desabilitado por padrão.
Para activá-lo, devemos realizar as seguintes etapas:

* Abra e focalize a janela do WhatsApp.
* Abra o menu do NVDA com a tecla modificadora + n, preferências e configurações.
* Encontre o WhatsApp na lista e pressione "tabulador"  para encontrar a caixa de selecção.
* Depois de marcada, aplique e aceite para guardar as alterações

Cada vez que iniciemos o WhatsApp com esta função activada, o extra irá procurar uma nova versão do extra. Se for encontrada alguma, uma janela será activada que permitirá que  baixe e instale a nova versão.

## Instruções do modo de selecção
Para activar o modo de selecção, teremos que activar o menu contextual da mensagem sob o foco, seja com o atalho Control+M ou com a tecla de aplicativos.
Quando o menu for aberto, percorrer, com  as setas até a opção Seleccionar mensagens, que devemos activar com ENTER.
Quando pressionamos esta opção, uma janela deve ser activada automaticamente pelo plug-in para reconhecer a lista de mensagens, um processo que pode demorar alguns segundos. Se isto não acontecer, podemos experimentar o atalho alt+seta direita ou tabular para a lista de mensagens.
Se tudo foi bem feito, já devemos estar no modo de selecção, o que podemos corroborar pressionando a letra "s", que verbaliza as mensagens seleccionadas.
Uma vez aqui podemos seleccionar e desmarcar mensagens com a barra de espaço, e assim que a selecção estiver concluída, podemos executar as seguintes ações:

* Remover mensagens com a tecla Delete.
* Reencaminhar mensagens com a letra r.
* Realçar as mensagens com a letra d.
* Fechar o modo de selecção com a letra Q.

Dependendo da função seleccionada, a janela correspondente é activada: A selecção de contactos, no caso do reencaminhamento; a janela de confirmação, no caso de exclusão de mensagens, etc.

## Interface virtual de conversações

Em certas ocasiões as mudanças introduzidas em actualizações da aplicação, impedem a correta navegação com o foco do sistema entre os elementos da lista de conversações.
Para estes casos adicionei uma virtualização dos objetos de conversação. isto  permite-nos navegar entre a lista de conversações que se mostram na janela, geralmente 19. Sem dúvida, a sua ordem pode ser bastante arbitrária, o que leva a que a ordenação na seja sempre a mais correta, na lista virtualizada. 
Para ativar esta virtualização só é necessário ativar o quadro de pesquisa de conversações com o atalho control + "f". Ao abrirse este quadro, o complemento captura os objetos e coloca-os na lista virtual, a qual pode ser utilizada com os seguintes comandos:

* control + flecha arriba; verbaliza el chat anterior en la lista virtual.
* control + seta para baixo; verbaliza a conversação seguinte, na lista virtual;
* control + shift + home; verbaliza a primeira conversação, na lista virtual.
* control + enter; move o foco para a conversação atual, na lista virtual.

Para aceder à conversação de uma lista, primeiro devemos  navegar com os atalhos control + setas para cima ou abaixo, colocá-la sob o foco com control + enter, e depois, pressionar enter.

## Traduções:

As seguintes pessoas colaboraram para traduzir o complemento:

* Mustafa Elçiçek, para turco.
* Rémy Ruiz, para francês.
* Ângelo Miguel Abrantes e Rui Fontes, para português.
* Carlos Esteban Martínez Macías, para inglês.
* Valentin Kupriyanov, para russo.
* Michele Barbi, para Italiano.

# Comandos de Toque Realçados #

* Autor: Joseph Lee
* Baixar [versão estável][1]

Este extra fornece comandos de ecrã sensível ao toque adicionais para o
NVDA. Também fornece um conjunto de comandos para uma navegação mais fácil
no modo de navegação.

Note: this add-on requires NVDA 2018.1 or later running on a touchscreen
computer with Windows 8.1 or 10.

## Comandos:

### Disponíveis em qualquer lugar:

* Toque com quatro dedos: Activa/desactiva a ajuda de entrada.
* Tocar e segurar: activa o butão direito do objecto sob o dedo.
* Quatro dedos para a direita: Geralmente, activa o teclado virtual.

### Revisão de objecto:

* Três dedos para baixo: lê a janela actual.
* Três dedos para a esquerda: indica o objecto sob o foco.
* Três dedos para a direita: indicam o objecto de navegação actual.
* Quatro dedos para cima: indica o título da janela actual.
* Quatro dedos para baixo: lê a barra de estado.

## Modo toque na Web

Este modo de toque, disponível no modo de navegação, permite-lhe navegar
pelo documento através do elemento seleccionado. Para mudar para o modo web,
a partir dos documentos do modo de navegação, dê 3 toques. A partir deste
modo, o deslocamento para cima ou para baixo com um dedo passa pelos modos
de navegação dos elementos disponíveis, enquanto se desloca para a direita
ou para a esquerda com um dedo move-se para o elemento escolhido seguinte ou
anterior, respectivamente. Uma vez que deixa o modo de navegação, o modo de
toque do objeto passa a ser usado.

## configurações de sintetizador do Modo de toque

Pode usar este modo para mudar rapidamente as configurações do sintetizador,
como escolher uma voz e alterar o volume. Neste modo, use de dois dedos para
a esquerda ou para a direita para se mover entre as configurações do
sintetizador e use dois dedos para cima e para baixo gestos para alterar os
valores. estes gestos são semelhantes aos comandos de teclado das
configurações dos sintetizadores.

## Beep para anunciar as coordenadas.

Se tiver ativado a configuração de coordenadas do rato na configuração do
rato, ouvirá sinais sonoros para indicar a coordenada actual do ecrã quando
usa os gestos de exploração por toque.

## Passagem do comando de toque

Um comando não atribuído está disponível para permitir que possam ser usados
gestos do ecrã sensível ao toque como se o NVDA não estivesse em
execução. Para usar essa funcionalidade, precisa atribuir um comando (por
meio da caixa de diálogo definição de comandos) na categoria Gerenciadores
de toque aprimorados para permitir que faça isso por até dez segundos ou
alternar isso manualmente. Em seguida, vá para o menu NVDA / Preferências /
Interacção por toque e configure a pausa no valor de comando de toque do
NVDA entre 3 a 10 segundos (o padrão é 5 segundos).

## Desactivar o suporte de toque nos perfis

If profiles other than normal configuration is active and if you go to Touch
Interaction dialog, you'll see a checkbox named "completely disable touch
support". Checking this box and answering yes if prompted will completely
turn off touch support for that profile. This is useful in apps that provide
their own touch commands. To restore touch functionality, either uncheck
this checkbox or manually toggle touch passthrough.

## Version 18.03

* NVDA 2018.1 is required.
* Because NVDA 2018.1 comes with touch typing checkbox, the checkbox is no
  longer included in this add-on.

## Versão 17.12

* Requer NVDA 2017.4. Especificamente, este extra agora pode processar
  trocas de perfil de configuração.
* Como o NVDA 2017.4 inclui o anúncio da orientação do ecrã, esse recurso
  não faz mais parte deste extra.
* Adicionada uma caixa de selecção oculta na caixa de diálogo Interacção por
  toque para desativar completamente o suporte por toque (disponível se
  outros perfis além do da configuração normal estiverem activos).
* If using NVDA 2018.1 or later, Touch Interaction dialog will be listed
  twice under NvDA's preferences menu. The second item is the dialog that
  comes with the add-on.
* In Touch Interaction dialog for the add-on, touch typing mode is no longer
  shown if using NVDA 2018.1 or later.

## Versão 17.10

* Devido à política de suporte da Microsoft, o Windows 8 (versão original)
  não é mais suportado.
* O NVDA não anunciará mais a orientação do ecrã duas vezes ao executar
  versões de desenvolvimento do NVDA 2017.4.

## Versão 17.07.1

* Adicionada uma opção no diálogo de interacção de toque para alternar
  manualmente a passagem de toque sem o uso de um temporizador.
* Com o modo de passagem manual desligado, se a passagem de toque for
  activada antes do final da duração da passagem, a interacção de toque será
  activada.

## Versão 17.07

* Adicionada uma nova caixa de diálogo denominada interacção por toque no
  menu de preferências do NVDA para configurar como o NVDA funciona com
  ecrãs sensíveis ao toque.
* Depois de instalar esta versão, ao pressionar as teclas no teclado
  virtual, é preciso tocar duas vezes a tecla desejada. Pode voltar para a
  maneira antiga, permitindo a digitação de toque na caixa de diálogo
  Interação táctil.
* Adicionado um comando (não atribuído) para permitir que o NVDA ignore os
  gestos de toque até 10 segundos.
* Adicionada uma opção na caixa de diálogo Interacção por toque para
  permitir que o NVDA interrompa a interacção de toque entre 3 a 10 segundos
  para executar gestos de ecrã sensível directamente (como se o NVDA não
  estivesse em execução, o padrão é 5 segundos).
* Adicionadas mensagens de log de depuração ao executar cliques corretos
  (tocar e segurar) para serem gravadas no log do NVDA (requer NVDA 2017.1
  ou posterior).
* Devido às alterações feitas ao reproduzir as coordenadas do ecrã, o NVDA
  2017.1 ou posterior é necessário.

##Versão 17.03

* Corrigido um problema em que o sinal sonoro de coordenadas não era
  reproduzido ou surgia um beep de erro em vez disso ao usar o NVDA 2017.1
  ou posterior.

##Versão 16.12

* O modo Web Touch funciona no Microsoft Edge, no Microsoft Word e em outros
  onde o modo de navegação é usado.
* Adicionadas listas e marcadores para elementos do modo web touch.

## Versão 16.06

* Versão inicial estável.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=ets
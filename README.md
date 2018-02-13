# O Teu Armário

Para organizar o teu guarda-roupa e te ajudar a escolher o outfit perfeito para a semana

## Começando

Estas instruções vão dar-te uma visão geral de como funciona o programa, como correr, como ver um exemplo e como começar o teu próprio

### Requisítos

Para correr o programa, é preciso o [Text Loader.swf](Text%20Loader.swf), um player e um ficheiro [Clothes.txt](Clothes.txt).

### Executado um exemplo

Faz o download do .zip ou clona este repositório para uma pasta.

Coloca as imagens da pasta [Imagens](Imagens/) na pasta principal.

Escolhe o player da pasta [Players](Players/) mais adequado ao teu OS, e usa-o para abrir o ficheiro [Text Loader.swf](Text%20Loader.swf).

Em linux:
```
./Player/Flashplayer_linux Text\ Loader.swf
```

## O Programa

O menu principal tem várias opções:

### Novo Item (new)<a name="new"></a>

Permite adicionar uma nova peça à coleção. 

Tem **nome**; um **tipo** e **sub-tipo**; uma ou várias **cores**; tem uma escala de **ocasião**: mais formal (*100%*), mais informal (*0%*), ou neutro (*50%*); uma escala consoante a **temperatura** a que mais se adequa: calor, frio ou neutro; a data em que se usou a **última vez**; um **intervalo** de dias que devem passar até se usar de novo; e uma imagem, que pode ser de qualquer tamanho, mas convém apanhar apenas a peça em questão, e tem de estar na mesma pasta que os restantes ficheiros.

O primeiro botão laranja permite selecionar uma imagem, e o segundo serve para guardar, que redireciona à página [Salvar](#save).

### Editar Item (edit)<a name="edit"></a>

Permite editar a coleção.

Tem a mesma interface que a página [Novo Item](#new), à exceção de um campo para escolher o **número** da peça a editar. Permite também **apagar** a última peça da lista. E, no canto superior esquerdo, está uma opção para escolher se a peça está **visível** (ainda em uso) ou invisível.

### Galeria (gallery)

Permite toda a coleção, ou apenas uma categoria. Para este último, basta escolher ainda no menu principal.

Ao carregar num item, abre página de [Editar Item](#edit) nessa peça.
O botão do canto superior esquerdo dá a opção de **reordenar** a galeria. Apenas disponível quando visualizando todos os tipos de roupa, e mesmo assim vai carregar os items não visíveis, já que estes também entram para a ordem.

Para mover entre páginas, há uma **área de transferência** no canto direito. O botão de editar serve para **salvar** também.

### Combinação (combine)

Permite gerir os outfits consoante os dias.

Ao selecionar o **dia**, as **cores** desejadas, a **ocasião** e a **temperatura** adequadas, o botão maior à direita irá **gerar** um outfit compatível (*Casaco*, *Tronco*, *Pernas*, *Calçado*), se existirem peças suficientes registadas.

É possível continuar a gerar peças para todos os campos, ou **bloquear** algum, através dos asteriscos ao lado de cada. O botão mais achatado permite editar cada campo, nomeadamente **escolher manualmente** uma peça ou **remover** a que lá está. Dá ainda para revelar outro campo que suporta uma **peça adicional**.

O botão do lado esquerdo permite **registar** o outfit visível para o dia escolhido.

### Salvar<a name="save"></a>

Ao salvar em qualquer uma das páginas acima, aparecerá um botão *Opções não guardadas.* que redireciona para uma página com um único botão. É ao clicar neste que é pedido ao utilizador que guarde o novo ficheiro *Clothes.txt* com as alterações efectuadas, sobrepondo o antigo. 

Só assim se faz alterações definitivas.

## O Teu Próprio Armário

Para criares o teu próprio armário, só precisas de mudar a base de dados.
Assim, cria um ficheiro novo chamado *Clothes.txt* na pasta do programa, com o conteúdo:
```
number=0
```
Tendo isto, é só executar.


## Feito Com

- [Adobe Flash Professional CS4](https://www.adobe.com/products/animate.html), agora Adobe Animate, com **Action Script 3.0**.

O ficheiro binário [*.fla*](Text%20Loader.fla) é compatível com versões CS4 e superiores. O ficheiro [*.xfl*](Text%20Loader/Text%20Loader.xfl) é compatível com versões CS6 e superiores.

## Autor

- Francisco Sousa ([TheMrKiko](https://github.com/TheMrKiko/))


## License

This project is licensed under the GNU GENERAL PUBLIC LICENSE - see the [LICENSE.md](LICENSE.md) file for details

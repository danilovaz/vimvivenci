# VimViVenci  - Aprendendo Vim
> Welcome to the JUNGLE, baby! :sunglasses:


*Minha experiência com VIM até o momento:*

Status | Valor
------------ | -------------
Gostei | :heart:
Divertido | :sunglasses: :sunglasses:
Produtivo | ?

----------------------------------------------------------------------------------------------------
Vim é um editor de texto poderoso com muitos comandos, muitos para aprender apenas com um tutorial simples. Este é um guia para descrever o meu passo-a-passo com Vim e as lições que aprendi. O básico dos comandos para eu poder começar a utilizar no dia a dia.

Além de seguir o tutorial que vem com o Vim `vimtutor`, também estou seguindo o GitBook ["Vim para Noobs"](https://woliveiras.com.br/vimparanoobs/index.html) do [William Oliveira](https://github.com/woliveiras).

**Welcome to the *jungle* baby, here no one is safe. Enjoy!**

----------------------------------------------------------------------------------------------------
## 1.1:  *Movendo o cursor*

*Para mover o cursor, pressione as teclas h,j,k,l como indicado.*

             ^
             k               Dica: A tecla k move o cursor para cima.
       < h       l >               A tecla h move o cursor para a esquerda.
             j                     A tecla l move o cursor para a direita.
             v                     A tecla j move o cursor para baixo.

**NOTA:** Caso digite alguma coisa errada, simplesmente pressione `<ESC>` para voltar ao *Normal Mode*.

**NOTA:** Também é possível se mover pelos documentos utilizando as teclas de cursor.

----------------------------------------------------------------------------------------------------
## 1.2:  *Sair do VIM*

**NOTA:** Como diria o [Matheus Marsiglio](https://github.com/matmarsiglio):
> O primeiro desafio com VIM, é aprender como sair dele.


**1.** Pressione a tecla `<ESC>` (para ter certeza que você está no Normal Mode).

**2.** Digite:    `:q! <ENTER>`.**

**3.** Eu sei, amigo, eu também fiquei pressionando `<CTRL+C>` . Não desanime.

**NOTA:** `:q! <ENTER>` descarta qualquer alteração feita.

----------------------------------------------------------------------------------------------------
## 1.3: *Edição de texto -  Deleção*

*Pressione   `x`   para deletar o caractere sobre o cursor.*

**1.** Mova o cursor até que ele fique sobre o caractere a ser deletado.

**2.** Pressione a tecla   `x`   para deletar o caractere que está sobre o cursor.

----------------------------------------------------------------------------------------------------
## 1.4: *Edição de texto - Inserção*

*Pressione   `i`   para inserir um texto.*

**1.** Para inserir um texto, mova o cursor sobre o primeiro caractere *APÓS* o local onde o texto será inserido.
**Exemplo:** Imagine que tenhamos o texto `tete` mas na verdade era para ser `teste`. Para inserir o caractere `s`, preciso mover o meu cursor sobre o segundo `t`.

**2.** Pressione   `i`   e ainda levando em consideração o exemplo acima, digite `s` e então o texto ficará `teste`.

**3.** Após terminar de inserir, pressione `<ESC>` para voltar ao *Normal Mode*.

----------------------------------------------------------------------------------------------------
## 1.5: *Edição de texto - Acrescentar*

*Pressione   `A`   para acrescentar um texto.*

**1.** Mova o cursor sobre a linha onde deseja acrescentar algum texto, não importa em qual caractere o cursor esteja.

**2.** Pressione   `A`   e digite o texto que deseja acrescentar.

**3.** Após terminar de acrescentar, pressione `<ESC>` para voltar ao *Normal Mode*.

----------------------------------------------------------------------------------------------------
## 1.6: *Editando um arquivo*

*Digite   `:wq`   para salvar um arquivo e sair do VIM.*

**1.** Abra um terminal, digite `vim NOMEDOARQUIVO <ENTER>` para abrir um arquivo.

**2.** Digite qualquer coisa nesse documento.

**3.** Pressione `<ESC>` para ter certeza de que está em *Normal Mode*.

**4.** Digite   `:wq <ENTER>`   e pronto, seu arquivo foi salvo e você saiu do **VIM**.

----------------------------------------------------------------------------------------------------
## 1.x - Resumo

**1.** *O cursor é movido usando tanto as teclas de setas quanto as teclas hjkl.*
> h (esquerda)        j (baixo)        k (cima)        l (direita)

**2.** *Para abrir um arquivo no **VIM**, digite `vim NOMEDOARQUIVO <ENTER>`.*

**3.** *Para sair do VIM digite:  `<ESC>  :q!  <ENTER>`  para descartar as mudanças ou digite:  `<ESC>  :wq  <ENTER>`  para salvar as mudanças.*

**4.** *Para deletar um caractere sobre o cursor digite:*   `x`

**5.** *Para inserir ou acrescentar um texto digite:
`i`   digite o texto a ser inserido   `<ESC>` - insere antes do cursor
`A`  digite o texto a ser acrescentado  <ESC> - acrescenta depois da linha*

**NOTA:** Pressionar `<ESC>` levará você para o *Normal Mode* ou vai cancelar um comando indesejado e completar o comando parcialmente.

----------------------------------------------------------------------------------------------------

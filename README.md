# Documentação

## Área de trabalho
### Imagem de fundo
As imagens de fundo podem ser definidas através do diretório **Backgrounds** que deverá estar localizado dentro da pasta **Imagens**. por padrão, qualquer imagem cujo o nome seja equivalente a **default** será considerada como sua imagem de fundo padrão independente de seu formato.

Exemplo:
> ~/Imagens/Backgrounds/01/wallpaper1.svg <br>
> ~/Imagens/Backgrounds/02/wallpaper2.svg

Através do comando ln é possível criar um atalho referente a imagem de fundo desejada.
> ln -s ./02/wallpaper2.svg

Considerando que você esteja no diretório **Backgrounds** e executou o comando acima, para atualizar a imagem de fundo basta reiniciar as configurações do i3 através da tecla de atalho `Mod+Shift+R`

O plugin de imagem de fundo tem suporte para os formatos mais comuns, como: **png**, **jpeg** e **svg**.

## Teclas de atalho
Considere que a tecla **Mod** faz referencia a tecla SUPER que por sua vez também é representada pela tecla Windows e a tecla **Mod1** faz referencia a **Alt**.

### Aplicativos
- Mod+Enter (Terminal)
- Mod+D ou Menu (Rofi)

### Windows
- `Mod+Q` Finaliza a janela em foco.
- `Mod+F` Habilita/Desativa o modo tela cheia.
- `Mod+(1~8)` Alterna entre ás áreas de trabalho.
- `Mod+Shift+(Up/Left/Right/Down)` Altera a orientação e/ou posição da janela em foco.
- `Mod+Up` Foca a janela superior.
- `Mod+Left` Foca a janela esquerda.
- `Mod+Right` Foca a janela direita.
- `Mod+Down` Foca a janela inferior.
- `Mod+Crtl+(Left/Right)` Navegação entre as áreas de trabalho. "Esquerda/Direita"

### Layout
- `Mod+W` Alterna a orientação de criação de janelas. "Horizontal/Vertical"

### I3
- `Mod+Shift+R` Recarrega a sessão e as configurações.
- `Mod+L` Bloqueio de sessão.
- `Mod1+F2` Executa o dmenu.
- `Mod+Shift+H` Documentação.

### Sistema
- `Print` Print em tela cheia.
- `Shift+Print` Print em tela cheia após 3 segundos.
- `Ctrl+Print` Print em tela cheia com opção de recorte.
- `Volume (+/-)` Aumenta ou Diminui o volume. "10 em 10"
- `Volume (x)` Mute.

## Regras
### Windows
- Simplescreenrecorder abre em modo flutuante.
- Manjaro-Hello abre em modo flutuante.

### Área de trabalho
- Simplescreenrecorder por padrão é direcionado a área de trabalho 8.

## Instalação
Em breve...

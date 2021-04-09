![Image](./demo.png?raw=true)

## Área de trabalho
### Imagem de fundo
O sistema de imagem de fundo funciona de maneira estatica. ou seja, o usuário deverá apontar o caminho da imagem em um dirétorio especifico através do comando "**ln**".
```
├── Desktop
├── Documents
├── Downloads
├── Music
├── Pictures
├──── backgrounds
├────── 01
├──────── wallhaven-k7x3zq.png
├────── 02
├────── 03
├────── default.png
├── Videos
```
Observando a estrutura de pastas acima, podemos notar que: temos duas imagens representadas em diretórios diferentes. "backgrounds/**default.png**" é o local estatico para ser usado como referencia a outras imagens.

Através do comando adiante, poderemos fazer uma referencia para o wallpaper abordado no exemplo acima.

```sh
ln -S ./01/wallhaven-k7x3zq.png ./defaul.png
```

Os formatos suportados são: **jpg, png** e também **svg**. uma vez que a extensão do wallpaper seja jpg, a extensão do arquivo de referencia também deverá seguir o mesmo padrão.

## Teclas de atalho
Comportamento de teclas: (Pseudonimos)
- O **Mod** é referente a tecla **SUPER** ou **Windows** de seu teclado.
- O **Mod1** é referente a tecla **Alt** de seu teclado.

### Aplicativo
- `Mod+Enter` Terminal
- `Mod+D` ou `Menu` Rofi
- `Mod+F1` Navegador web Firefox
- `Mod+F2` Gerenciador de aquivos pcmanfm
- `Mod+F3` Visualizador de arquivos (ranger)
- `Mod+F4` Reprodutor de músicas (cmus)

### Janela
- `Mod+Q` Finaliza a janela em foco.
- `Mod+F` Inicia ou Finaliza o modo de tela cheia.
- `Mod+(1~8)` Cria uma área de trabalho na posição informada.
- `Mod+Shift+(Cima/Baixo/Direita/Esquerda)` Altera a orientação e/ou posição da janela em foco.
- `Mod+(Cima/Baixo/Direita/Esquerda)` Altera o foco de janela para a direção informada.
- `Mod+Crtl+(Direita/Esquerda)` Navegação entre as áreas de trabalho. "Esquerda/Direita"
- `Mod+W` Alterna a orientação de criação de janelas. "Horizontal/Vertical"
- `Mod+R` Ativa o modo de redimencionamento de janelas. use as setas para o controle de direção: `(Cima/Baixo/Direita/Esquerda)`

### I3
- `Mod+Shift+R` Recarrega a sessão e as configurações.
- `Mod+Shift+E` Finaliza a sessão.
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
### Janela
- Simplescreenrecorder abre em modo flutuante.
- Manjaro-Hello abre em modo flutuante.

## Dependencias

| Descrição | Pacote | Opcional |
----------------- | -------------- | -------------- |
Provedor de imagem de fundo | `feh` | `nitrogen`
Provedor de bloqueio de tela | `xautolock` |
Gerenciador de energia | `xfce4-power-manager` |
Provedores de menu | `rofi`, `networkmanager_bmenu` |
Aplicações | `firefox`, `pcmanfm`, `cmus`, `ranger` | `redshift`, `geoclue`, `pyxdg`, `nm-applet`

## Problemas reconhecidos
Após o usuário ativar o modo de redimencionamento "**resize**", caso o mesmo ative a função com a janela em foco em seu lado esquerdo; a função de redimencionamento funciona de modo invertido. ou seja, não respeitando as configurações aplicada.

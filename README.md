![Image](./demo.png?raw=true)

## Área de trabalho
### Imagem de fundo
Em construção...
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

## Teclas de atalho
Comportamento de teclas: (Pseudonimos)
- O **Mod** é referente a tecla **SUPER** ou **Windows** de seu teclado.
- O **Mod1** é referente a tecla **Alt** de seu teclado.

### Aplicativos
- `Mod+Enter` Terminal
- `Mod+D` ou `Menu` Rofi

### Windows
- `Mod+Q` Finaliza a janela em foco.
- `Mod+F` Inicia ou Finaliza o modo de tela cheia.
- `Mod+(1~8)` Cria uma área de trabalho na posição informada.
- `Mod+Shift+(Up/Left/Right/Down)` Altera a orientação e/ou posição da janela em foco.
- `Mod+(Up/Left/Right/Down)` Altera o foco de janela para a direção informada. "Cima/Esquerda/Direita/Baixo"
- `Mod+Crtl+(Left/Right)` Navegação entre as áreas de trabalho. "Esquerda/Direita"

### Layout
- `Mod+W` Alterna a orientação de criação de janelas. "Horizontal/Vertical"

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
### Windows
- Simplescreenrecorder abre em modo flutuante.
- Manjaro-Hello abre em modo flutuante.

### Área de trabalho
- Simplescreenrecorder por padrão é direcionado a área de trabalho 8.

## Dependencias
> Redshift: <br>
> `sudo pacman -S redshift geoclue pyxdg` <br>

> Gerenciador de Bateria: <br>
> `sudo pacman -S xfce4-power-manager` <br>

> Gerenciador de conexões de rede: <br>
> `sudo pacman -S nm-applet` <br>

> Notificações de atualização: <br>
> `sudo pacman -S pacman-tray` <br>

> Provedor do bloqueio de tela: <br>
> `sudo pacman -S xautolock` <br>

> Provedor de Imagem de fundo: <br>
> `sudo pacman -S feh` <br>

> Provedor de menu: <br>
> `sudo pacman -S rofi` <br>

> Provedor de menu wifi: <br>
> `sudo pacman -S networkmanager_bmenu`

### Possíveis dúvidas
<details>
  <summary>
    <strong>Como resolver a falha na inicialização do Redshift?</strong>
  </summary>
  <p>Você pode optar pelas configurações manuais através do arquivo <strong>redshift.conf</strong> que deverá ser criado em <code>~/.config/</code> contendo as seguintes informações:</p>

  <blockquote>
  [redshift] <br>
  location-provider=manual <br>
  [manual] <br>
  lat=32.7 <br>
  lon=-117.2 <br>
  </blockquote>
</details>

<details>
  <summary>
    <strong>Como saber a longitude e latitude?</strong>
  </summary>
  <p>É possível obter esses dados através da página <a href="https://www.latlong.net/" target="_blank">latlong</a></p>
</details>

## Instalação
Em breve detalhes...

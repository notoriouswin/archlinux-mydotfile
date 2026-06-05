# 🐧 Arch Linux Dotfiles

Minha configuração pessoal do Arch Linux usando Hyprland.

## ✨ Recursos

- 🪟 **Hyprland** → window manager moderno e eficiente
- 📊 **Waybar** → barra de status totalmente customizável
- 🐚 **Zsh** → shell poderoso e produtivo
- ⚡ **Oh My Zsh** → framework para personalização do Zsh
- 🖼️ **Hyprpaper** → gerenciamento dinâmico de wallpapers
- 🔧 **Aliases personalizados** → atalhos para agilizar comandos
- 💻 **Configurações de terminal** → ambiente otimizado para desenvolvimento
- 🚀 **Scripts de produtividade** → automações para fluxo de trabalho mais rápido
- Scripts para produtividade

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ebcdcf6e-3c1f-41a6-b11c-ebadb43cb0b1" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a9ebc155-1220-4891-bde8-9c54ae615d37" />



## 📦 Instalação de dependências

Antes de aplicar as dotfiles, instale os pacotes necessários:

```bash
sudo pacman -S ttf-jetbrains-mono-nerd nautilus hyprpaper waybar zsh cava cmatrix tty-clock git curl

sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

📥 Instalação das Dotfiles
Clone o repositório:

```bash
git clone git@github.com:notoriouswin/archlinux-mydotfile.git
cd archlinux-mydotfile
cp -r . ~/
```


## 🎨 Personalização

### Waybar

As configurações da Waybar podem ser encontradas no diretório correspondente dentro deste repositório. Sinta-se à vontade para modificar módulos, cores e layout conforme sua preferência.

### Wallpaper

Para trocar o wallpaper, basta alterar a imagem utilizada pelo Hyprpaper no diretório de configuração do Hyprland/Hyprpaper.


```bash
~/.config/hypr/hyprpaper.conf
```

Basta apontar para a imagem desejada e recarregar o Hyprpaper.


## ⚙️ Extras no terminal

- **cmatrix**: inicia no terminal com tema azul (`cmatrix -C blue` ou `cmatrix -C 2`)
- **tty-clock**: inicia centralizado, estilizado e com cor azul (`tty-clock -c -C 2 -t`).
- **Zsh plugins e atalhos**:
  - `Ctrl + Alt` → abre menu rápido de pastas para navegação.
  - `Ctrl + R` → busca no histórico de comandos.



## 🖥️ Componentes do sistema
| Componente              | Software   |
| ----------------------- | ---------- |
| WM                      | Hyprland   |
| Barra                   | Waybar     |
| Wallpaper               | Hyprpaper  |
| Shell                   | Zsh        |
| Framework               | Oh My Zsh  |
| Gerenciador de arquivos | Nautilus   |
| Terminal visual         | Cava       |
| Efeitos no terminal     | Cmatrix    |
| Relógio no terminal     | TTY-Clock  |
| Sistema base            | Arch Linux |


## 🚀 Objetivo

Manter minhas configurações do Arch Linux organizadas, versionadas e fáceis de restaurar em qualquer máquina.

## 🤝 Contribuições

Sinta-se à vontade para abrir Issues ou Pull Requests com melhorias e sugestões.

## 📄 Licença

MIT License

# i3 Rice - Meu Setup Pessoal

Este repositório contém os arquivos de configuração do meu ambiente gráfico personalizado com o gerenciador de janelas [i3wm](https://i3wm.org/), juntamente com `picom`, `polybar` e outras ferramentas.

---

## Requisitos

- **i3wm**
- **picom**
- **polybar**
- **flameshot**
- **rofi**

---

## Estrutura

- `~/.config/i3/config` # Arquivo principal do i3
- `~/.config/picom/picom.conf` # Transparência e sombras
- `~/.config/polybar/config.ini` # Barra de status


---

## Instalação

```bash
# Clone o repositório
git clone https://github.com/joaoandrejs/dark-i3-rice ~/.dotfiles

# Copie os arquivos para os diretórios corretos
cp -r ~/.dotfiles/i3 ~/.config/
cp -r ~/.dotfiles/picom ~/.config/
cp -r ~/.dotfiles/polybar ~/.config/

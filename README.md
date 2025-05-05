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
```


# Atalhos

| Atalho                          | Ação                                                                          |
| ------------------------------- | ----------------------------------------------------------------------------- |
| `Super+Enter`                    | Abre o terminal (`alacritty`)                                                 |
| `Super+d`                        | Abre o `rofi` no modo `drun` (lançador de aplicativos)                        |
| `Super+Shift+q`                  | Fecha a janela ativa                                                          |
| `Super+Shift+r`                  | Reinicia o i3                                                                 |
| `Super+Shift+e`                  | Exibe um menu de logout usando `rofi`                                         |
| `Super+f`                        | Alterna modo fullscreen para a janela ativa                                   |
| `Super+h/j/k/l`                  | Move o foco entre janelas nas direções esquerda/baixo/cima/direita (vim-like) |
| `Super+Shift+h/j/k/l`            | Move a janela ativa nas direções esquerda/baixo/cima/direita                  |
| `Super+1` a `Super+9`             | Muda para o espaço de trabalho correspondente                                 |
| `Super+Shift+1` a `Super+Shift+9` | Move a janela ativa para o espaço de trabalho correspondente                  |
| `Super+space`                    | Alterna entre janelas empilhadas ou em tab                                    |
| `Super+v`                        | Muda para o modo de divisão vertical                                          |
| `Super+b`                        | Muda para o modo de divisão horizontal                                        |
| `Super+s`                        | Alterna entre os modos de layout (split/tab/stacked)                          |
| `Super+m`                        | Muda a janela para o modo flutuante                                           |
| `Super+Shift+space`              | Alterna entre modo flutuante e tiling                                         |
| `Super+q`                        | Mata a janela ativa                                                           |
| `Super+Shift+c`                  | Recarrega a configuração do i3                                                |
| `Super+p`                        | Tira print com `flameshot`                                                    |
| `Print`                          | Abre o `flameshot` no modo interativo                                         |

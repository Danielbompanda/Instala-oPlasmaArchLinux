# 💻 Instalação rápida do KDE Plasma no Arch Linux

Este é um guia simples para instalar o ambiente gráfico **KDE Plasma** em um Arch Linux já instalado e funcionando no modo texto.

---

## ✅ Requisitos

- Arch Linux já instalado (com boot funcionando normalmente)
- Acesso à internet
- Um usuário com permissões de `sudo`

---

## 📦 Instalação do KDE Plasma

Execute o seguinte comando:

"sudo pacman -S plasma sddm sddm-kcm konsole dolphin firefox"

O que esses pacotes fazem:
plasma: instala o ambiente de desktop KDE Plasma

sddm: gerenciador de login gráfico

sddm-kcm: módulo de configurações do SDDM no KDE

konsole: terminal do KDE

dolphin: gerenciador de arquivos gráfico

firefox: navegador web

---

## ⚙️ Ativando o login gráfico
Após a instalação, ative o SDDM (display manager):

sudo systemctl enable sddm

---

## 🔁 Reinicie o sistema

sudo reboot

Ao reiniciar, o sistema já carregará o KDE Plasma com o gerenciador de login gráfico ativo.

---

## 🧼 Dica (opcional)
Se quiser instalar apenas o essencial do Plasma, você pode substituir plasma por plasma-desktop (instala apenas o básico).


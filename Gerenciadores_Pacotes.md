# Comandos dos Gerenciadores de Pacotes

## APT

- `apt install`: Baixa os pacotes;
- `apt search`: Pesquisa pacotes no repositório;
- `apt show`: Exibe detalhes de um pacote;
- `apt list`: Lista todos os pacotes instalados;
- `apt update`: Atualiza os as mudanças nos repositórios;
- `apt upgrade`: Atualiza os pacotes;
- `apt full-upgrade`: Atualiza todos os pacotes incluindo os do sistemas;
- `apt install -f`: Baixa as dependências dos pacotes;
- `apt remove`: Remove os pacotes;
- `apt autoremove`: Remove pacotes não necessários;

## Pacman

- `pacman -S`: Baixa os pacotes;
- `pacman -Ss`: Pesquisa pacotes no repositório;
- `pacman -Si`: Exibe detalhes de um pacote;
- `pacman -Q`: Lista todos os pacotes instalados;
- `pacman -Sy`: Atualiza os as mudanças nos repositórios;
- `pacman -Su`: Atualiza os pacotes;
- `pacman -Syu`: Atualiza todos os pacotes incluindo os do sistemas;
- `pacman -S`: Baixa as dependências dos pacotes;
- `pacman -R`: Remove os pacotes;
- `pacman -Rns $(pacman -Qtdq)`: Remove pacotes não necessários;

## PKG (Termux)

- `pkg install`: Baixa os pacotes;
- `pkg search`: Pesquisa pacotes no repositório;
- `pkg show`: Exibe detalhes de um pacote;
- `pkg list-all`: Lista todos os pacotes instalados;
- `pkg update`: Atualiza os as mudanças nos repositórios;
- `pkg upgrade`: Atualiza todos os pacotes incluindo os do sistemas;
- `pkg uninstall`: Remove os pacotes;
- `pkg autoremove`: Remove pacotes não necessários;

## Flatpak 

- `flatpak list`: Lista todos os pacotes instalados;
- `flatpak install`: Instala um pacote;
- `flatpak update`: Atualiza os pacotes;
- `flatpak remotes`: Lista todos os repositórios;
- `flatpak run`: Executa o programa;
- `flatpak remove`: Remove um pacote;
- `flatpak info`: Exibe informações sobre os pacotes;
- `flatpak remote-add`: Adiciona um repositório;
- `flatpak remote-delete`: Remove um repositório;
- `flatpak --help`: Exibe informações e comandos sobre o **Flatpak**;

## Snap

- `snap find`: Procura pacotes;
- `snap list`: Lista os **snaps** instalados;
- `snap install`: Instala pacotes;
- `snap info`: Exibe informações sobre um pacote;
- `snap remove`: Remove pacotes;
- `snap refresh`: Atualiza os pacotes;

## WinGet

- `winget search`: Procura pacotes;
- `winget list`: Lista quantos pacotes tem instalados;
- `winget info`: Exibe informações sobre o sistema;
- `winget show`: Exibe informações sobre um pacote;
- `winget source`: Adiciona, exibe e remove repositórios;
- `winget install`: Instala pacotes;
- `winget upgrade`: Atualiza um ou todos os pacotes;
- `winget uninstall`: Remove pacotes;
- `winget --help`: Exibe informações sobre o **WinGet**;


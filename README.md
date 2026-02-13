# Tela de Boas Vindas do Aratiê

## Dependencias

* `build-essential`
* `qt6-base-dev`

```bash
sudo apt install qt6-base-dev build-essential libqt6svg6-dev
```

## Clonando o repositório

```bash
git clone https://github.com/aratie-os/welcome.git
```

## Build

```bash
cd welcome-qt/welcome.src
qmake6 welcome-next.pro
make && strip --strip-unneeded ./welcome-next
```

## Executando

```bash
./welcome-next
```

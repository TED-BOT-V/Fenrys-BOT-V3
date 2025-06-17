## Instalação Via Termux

### 1° Comando
```bash
apt-get update -y && pkg upgrade -y && pkg update -y && pkg install nodejs -y && pkg install nodejs-lts -y && pkg install ffmpeg -y && pkg install wget -y && pkg install tesseract -y && pkg install git -y
```

**ATENÇÃO:** Será necessário digitar `y` toda vez que pedir a caixa `[y/n]`

### 2° Comando
```bash
termux-setup-storage
```

### 3° Comando
```bash
cd /sdcard && git clone https://github.com/TED-BOT-V/Fenrys-BOT-V3
```

### 4° Comando
```bash
cd Fenrys-BOT-V3 && npm start
```


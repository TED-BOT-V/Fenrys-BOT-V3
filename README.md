# 🤖 Fenrys-BOT-V3: Seu Bot de WhatsApp no Termux! 🚀

Bem-vindo ao Fenrys-BOT-V3, um bot de WhatsApp poderoso e fácil de usar, otimizado para rodar no Termux! Siga os passos abaixo para ter seu próprio bot funcionando em minutos.

## 🛠️ Instalação Via Termux ![Termux Icon](https://private-us-east-1.manuscdn.com/sessionFile/EsyRUw4SnTpuoUCkyMijGm/sandbox/wNO2JXYdz68L2pJkfpI6YK-images_1750194115457_na1fn_L2hvbWUvdWJ1bnR1L3JlYWRtZV9pbWFnZXMvdGVybXV4X2xvZ28.png?Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9wcml2YXRlLXVzLWVhc3QtMS5tYW51c2Nkbi5jb20vc2Vzc2lvbkZpbGUvRXN5UlV3NFNuVHB1b1VDa3lNaWpHbS9zYW5kYm94L3dOTzJKWFlkejY4TDJwSmtmcEk2WUstaW1hZ2VzXzE3NTAxOTQxMTU0NTdfbmExZm5fTDJodmJXVXZkV0oxYm5SMUwzSmxZV1J0WlY5cGJXRm5aWE12ZEdWeWJYVjRYMnh2WjI4LnBuZyIsIkNvbmRpdGlvbiI6eyJEYXRlTGVzc1RoYW4iOnsiQVdTOkVwb2NoVGltZSI6MTc2NzIyNTYwMH19fV19&Key-Pair-Id=K2HSFNDJXOU9YS&Signature=BKRl-r1jCyTIWQR9c~AOgAbP6rdHcasrIl2Cir1j~BGBYso1HScIDEGdT1FiNT4rB2FVKkiuqHZ4OG4yDcX1CXoAswCaxBPRprJ~UkvXkQ4n0NqMknsfzrvynx0Fn-T0diAxfqb0r5~s111cB8TVGYOMcV56O7xJ5SJ2l65hSp7dPkKXdRMc0cT0l3FbkVvHKx50UzZvGfpItT1xFFcC-SoXduKzBUJCnT-9QVbiL~9mNuFnnxjgYWrEm9rWGpPsxhVhvSfY8PKF6rziWtbcmh0Cne98V8-YH8pPy~OtxtPCFSefy2~B-J6YjYmQcTQ5Jp2jV6uLhNRd6gIUvtKX1w__)

### Passo 1: Preparando o Ambiente

Primeiro, vamos garantir que seu Termux esteja atualizado e com as ferramentas necessárias:

```bash
apt-get update -y && pkg upgrade -y && pkg update -y && pkg install nodejs -y && pkg install nodejs-lts -y && pkg install ffmpeg -y && pkg install wget -y && pkg install tesseract -y && pkg install git -y
```

**ATENÇÃO:** Será necessário digitar `y` toda vez que o terminal pedir a caixa `[y/n]`.

### Passo 2: Configurando o Armazenamento

Permita que o Termux acesse o armazenamento do seu dispositivo:

```bash
termux-setup-storage
```

### Passo 3: Clonando o Repositório do Bot

Agora, vamos baixar o Fenrys-BOT-V3 para o seu dispositivo:

```bash
cd /sdcard && git clone https://github.com/TED-BOT-V/Fenrys-BOT-V3
```

### Passo 4: Iniciando o Bot

Com o repositório clonado, é hora de iniciar o seu bot:

```bash
cd Fenrys-BOT-V3 && npm start
```






## 📸 Visual do Projeto

![Termux Logo](https://private-us-east-1.manuscdn.com/sessionFile/EsyRUw4SnTpuoUCkyMijGm/sandbox/wNO2JXYdz68L2pJkfpI6YK-images_1750194115458_na1fn_L2hvbWUvdWJ1bnR1L3JlYWRtZV9pbWFnZXMvdGVybXV4X2xvZ28.png?Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9wcml2YXRlLXVzLWVhc3QtMS5tYW51c2Nkbi5jb20vc2Vzc2lvbkZpbGUvRXN5UlV3NFNuVHB1b1VDa3lNaWpHbS9zYW5kYm94L3dOTzJKWFlkejY4TDJwSmtmcEk2WUstaW1hZ2VzXzE3NTAxOTQxMTU0NThfbmExZm5fTDJodmJXVXZkV0oxYm5SMUwzSmxZV1J0WlY5cGJXRm5aWE12ZEdWeWJYVjRYMnh2WjI4LnBuZyIsIkNvbmRpdGlvbiI6eyJEYXRlTGVzc1RoYW4iOnsiQVdTOkVwb2NoVGltZSI6MTc2NzIyNTYwMH19fV19&Key-Pair-Id=K2HSFNDJXOU9YS&Signature=Um6WOS0jUCoq57bFE~sF7bxYTmXSPdyJ7c1flIXCE5U~kKcfH8-Q-YV5QZdFBhGwVsKh~GbJOl94opb1FnAIOcL~IJSxMYzECsMc8CLgEyzhZBkZdNUUNRR1whJneXAxyCC19wlR7E5xcXNBNDhTlSOHl5vOv9FFEZgyJi2nhINoO6qsxunTx90el19fHh5FHWM6O7ISx~Pch6ZfB99P-OIiZzYGI9DvKy1sqBvnM2zjlB84bdtaTads2z4qFtw6mXiEGjjnhcdHNyAErEQ7eZ2ZQEe0a8hlL1W~l2wy0vbRV6vMjolVK3~-SxAe44ohbSDcYOxKVmqDFmw13oFS4w__)

![WhatsApp Bot Logo](https://private-us-east-1.manuscdn.com/sessionFile/EsyRUw4SnTpuoUCkyMijGm/sandbox/wNO2JXYdz68L2pJkfpI6YK-images_1750194115459_na1fn_L2hvbWUvdWJ1bnR1L3JlYWRtZV9pbWFnZXMvbmV3X3doYXRzYXBwX2JvdF9sb2dv.png?Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9wcml2YXRlLXVzLWVhc3QtMS5tYW51c2Nkbi5jb20vc2Vzc2lvbkZpbGUvRXN5UlV3NFNuVHB1b1VDa3lNaWpHbS9zYW5kYm94L3dOTzJKWFlkejY4TDJwSmtmcEk2WUstaW1hZ2VzXzE3NTAxOTQxMTU0NTlfbmExZm5fTDJodmJXVXZkV0oxYm5SMUwzSmxZV1J0WlY5cGJXRm5aWE12Ym1WM1gzZG9ZWFJ6WVhCd1gySnZkRjlzYjJkdi5wbmciLCJDb25kaXRpb24iOnsiRGF0ZUxlc3NUaGFuIjp7IkFXUzpFcG9jaFRpbWUiOjE3NjcyMjU2MDB9fX1dfQ__&Key-Pair-Id=K2HSFNDJXOU9YS&Signature=v52w~IHoUzWYoIRpeW4025srTVPqMZFIjqsPv9UZRHPuz20m2OR3rBuhhgEyvHPvVFDhD48NsgPf3yUju3J83in8fwiCFGNrlCsBAcpKIcnj-JErOUrSqR-3FmjjeIXLBnTkLv0bto1ZxxEksuCEzPvRNkXjR6DmKuYUqMxgBRwv7~oHpoHjS8Uwi86Ky0AcUaTWLgZHgGVfum84TJZ8WOmKzKzSBjPuQLe2PUwKzc~EKeHCngesz4D8xPZ5Q25Uo2BJv0YZ~0k2R3sWlhtgGgUvq-G8Fk0dOZuzm94VADkT0IokAEct1Cd9YZ8FyNQL7Nhcq7oWHDkhzDOxHxhtSQ__)



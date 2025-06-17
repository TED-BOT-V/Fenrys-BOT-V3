# 🤖 Fenrys-BOT-V3: Seu Bot de WhatsApp no Termux! 🚀

Bem-vindo ao Fenrys-BOT-V3, um bot de WhatsApp poderoso e fácil de usar, otimizado para rodar no Termux! Siga os passos abaixo para ter seu próprio bot funcionando em minutos.

## 🛠️ Instalação Via Termux

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

![Termux Logo](https://private-us-east-1.manuscdn.com/sessionFile/EsyRUw4SnTpuoUCkyMijGm/sandbox/WBNA9a16KNFEWZyGIKUAPA-images_1750193154949_na1fn_L2hvbWUvdWJ1bnR1L3JlYWRtZV9pbWFnZXMvdGVybXV4X2xvZ28.png?Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9wcml2YXRlLXVzLWVhc3QtMS5tYW51c2Nkbi5jb20vc2Vzc2lvbkZpbGUvRXN5UlV3NFNuVHB1b1VDa3lNaWpHbS9zYW5kYm94L1dCTkE5YTE2S05GRVdaeUdJS1VBUEEtaW1hZ2VzXzE3NTAxOTMxNTQ5NDlfbmExZm5fTDJodmJXVXZkV0oxYm5SMUwzSmxZV1J0WlY5cGJXRm5aWE12ZEdWeWJYVjRYMnh2WjI4LnBuZyIsIkNvbmRpdGlvbiI6eyJEYXRlTGVzc1RoYW4iOnsiQVdTOkVwb2NoVGltZSI6MTc2NzIyNTYwMH19fV19&Key-Pair-Id=K2HSFNDJXOU9YS&Signature=HPB~M1AG-LR-sJ~RhkYdPVrxa9DMenIRb8Su9AQ1~c~PYvWYkLCGS7hsBjVVodjD7xnuGcLiAVrt9EN5U2gikeHZSO4H1YhGLcTDFEnoi81R9p5nkkqoI1oYQBmyJiQVAxYKtDsb-L7eeKSQeuYVWVCQos-YZcJ4eTLbJEafDSW9FBiiimNnzjb0VCPPYRF9~MVqme5CdYnnMBecgg829m8vO6TKzHxOenA-clSAIGgZLuD~6Po~KdLG6uUF8KEZYhowglHTxWgb-dPBptaQI2bvvMcsc3IPtEKXnqkOviDHPCpfyrAGGMYPyVb7F1-LmE4wM63jtXP7hqH5ULSttQ__)

![WhatsApp Bot Logo](https://private-us-east-1.manuscdn.com/sessionFile/EsyRUw4SnTpuoUCkyMijGm/sandbox/WBNA9a16KNFEWZyGIKUAPA-images_1750193154949_na1fn_L2hvbWUvdWJ1bnR1L3JlYWRtZV9pbWFnZXMvd2hhdHNhcHBfYm90X2xvZ28.png?Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9wcml2YXRlLXVzLWVhc3QtMS5tYW51c2Nkbi5jb20vc2Vzc2lvbkZpbGUvRXN5UlV3NFNuVHB1b1VDa3lNaWpHbS9zYW5kYm94L1dCTkE5YTE2S05GRVdaeUdJS1VBUEEtaW1hZ2VzXzE3NTAxOTMxNTQ5NDlfbmExZm5fTDJodmJXVXZkV0oxYm5SMUwzSmxZV1J0WlY5cGJXRm5aWE12ZDJoaGRITmhjSEJmWW05MFgyeHZaMjgucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxNzY3MjI1NjAwfX19XX0_&Key-Pair-Id=K2HSFNDJXOU9YS&Signature=Tlnb5VC1ldioNHmda24vfnSjwVjW5D4RKE-eo4T1tTYOtt3xbPJ9wNONxtHPg4ykXzK4vYImzBJkkolKwW9FwfX8Usxt7P-1wUGdg-iw3jOr8BmNf11lDMIHCgNQv7bI0e9ywnVVl45auIQdkqwGCZ5VBSmk8XnEMGWQXWPkpRHaGk8R74Rox7vUYOReXtHcFZngayAnnFXna5W4tE-3suBQo2HRH1aBuqoR2H3ZuVo0iLbRwFSt8FoZBUsvYtw75RFuaMnWkONviarL~WsSrmbbst5gs92XueHXgsX~giOqDq7FWHNFidJkbepQn8pHlzl~rZdFHm0CPgxac~uB-Q__)



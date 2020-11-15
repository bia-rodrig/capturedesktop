# Capture Desktop

Essa captura só funciona para vídeos que são abertos via **Browser**.

## Verificar dispositivo de audio

É a primeira etapa a se fazer.

No Windows, proximo ao relógio, clicar com o botão direito no alto-falante e selecionar *Open Sound settings*

![Capture%20Desktop/Untitled.png](Capture%20Desktop/Untitled.png)

Em **Output,** clicar em *Manage sound devices*

<img src="Capture%20Desktop/Untitled%201.png" alt="Capture%20Desktop/Untitled%201.png" style="zoom:80%;" />

Se no **input**, tiver o Stereo Mix desabilitado, habilite-o

<img src="Capture%20Desktop/Untitled%202.png" alt="Capture%20Desktop/Untitled%202.png" style="zoom:80%;" />

## Baixar o FFMPEG

Acessar o link:  https://drive.google.com/drive/folders/11MPG5Y4nKYnpxepjkyq_hhg3IKDT2Iag?usp=sharing

Baixar o arquivo **ffmpeg.doc*

Quando finalizar o download, renomear o arquivo para ffmpeg.exe e colocar dentro da pasta ffmpeg da aplicação Capture Desktop



## Capture Desktop

Para iniciar a aplicação, clicar em **main.exe**

Vai abrir uma janela de prompt e uma janela tkinter (deixar as duas abertas)

<img src="Capture%20Desktop/Untitled%203.png" alt="Capture%20Desktop/Untitled%203.png" style="zoom:80%;" />

### **File name**

Nome que o arquivo vai ter.  Ao parar a captura, o arquivo ficará disponível na mesma pasta no main.exe

### **Screen Resolution X**

A largura da imagem que vai ser capturada. Se quiser capturar a tela inteira, verificar resolução do monitor.

### **Screen Resolution Y**

A altura da imagem que vai ser capturada.

### **Inicio ponto X e inicio ponto Y**

se quiser capturar desde o canto superior esquerdo, inserir 0 no X e Y.

### **Check audio interface**

botão que vai verificar que interface de áudio está sendo utilizada.

No momento a aplicação só reconhece duas:

- Stereo Mix (Realtek High Definition Audio)
- Stereo Mix (Realtek(R) Audio)

### Start

Ao clicar no botão start, vai iniciar a captura no prompt

### Stop

Para parar a captura, selecione a janela do prompt de comando aberta e pressione **CTRL + C**
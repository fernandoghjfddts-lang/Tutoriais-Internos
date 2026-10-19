# Instalação do Arduino IDE no Windows

**Objetivo:** Instalar o Arduino IDE em um computador Windows

**Requisitos:** Computador com Windows 10/11, um robô Sparki

**Tempo estimado:** Entre 3 e 10 minutos

---

## Passo a Passo

1. **Baixando o Instalador:** 
Clique no link abaixo e o dowload do arquivo base da IDE vai começar imeditamente
<https://downloads.arduino.cc/arduino-1.8.19-windows.exe>

2. **Extraindo o arquivo:**
  Após alguns segundos ou minutos o dowload será concluído e será possível acessá-lo nos arquivos do computador, ele provavelmente estará na forma 
**arduino-1.8.19-linux64**
Clique com o botão direito do mouse e aperte em **Extrair**

4. **Instalação no Terminal**
   Após extrair o arquivo, clique novamente com o botão direito do mouse na pasta em que o arquivo foi extraindo e clique em **Abrir terminal na pasta**, com o terminal aberto, digite cada um dos seguintes códigos e aperte **Enter** após cada um deles :
   ls
   cd arduino-1.8.19-linux64
   ls, *após esse, uma tela como esta deve aparecer*:
   <img width="676" height="72" alt="image" src="https://github.com/user-attachments/assets/be067ff9-8bfb-465b-9f40-37434b884960" />
   hmcod +x arduino
   chmod +x arduino-builder
   chmod -R 777 tools-builder

   Pode fechar o terminal após isso.
   
5. **Finalizando a instalação**:
  Abra um novo terminal separado em seu computador apertando as teclas **CTRL** + **ATL** + **T** simultaneamente e digite, apertanto ENTER após cada linha os seguintes coódigos:
  wget -c
  http://security.ubuntu.com/ubuntu/pool/main/r/readline6/libreadline6_6.3-8ubuntu2_amd64.deb
  sudo apt update
  sudo apt install libtinfo5
  sudo dpkg -i ./libreadline6_6.3-8ubuntu2_amd64.deb
  sudo apt install libncurses5

Após todas instalações, pode fechar o terminal

7. **Configurando a Placa:** 
   Já dentro da IDE, vá na aba **Arquivos**, no canto superior direito e depois **Preferências**, dentro de Preferências, vá até **URLs Adicionais para Gerenciadores de Placas** e cole o seguinte código:
   <https://raw.githubusercontent.com/ArcBotics/ArcBotics-Boards/master/package_arcbotics.com_boards_index.json>

   <img width="1064" height="642" alt="image" src="https://github.com/user-attachments/assets/846bcce5-7b6e-4d24-abf1-5ad2f3795377" />

   Após isso, conecte o cabo USB no sparki e no computador para que ele fique utilizável e vá até a aba **Ferramentas**, depois **Placa** e **Gerenciador de Placas**, lá pesquise por **Sparki** e instale a Placa

   <img width="1113" height="728" alt="image" src="https://github.com/user-attachments/assets/f0185a48-6af6-41ed-a7c8-5a01dc741090" />

   <img width="1159" height="251" alt="image" src="https://github.com/user-attachments/assets/7fff8358-db85-49ac-942b-4374d31b6a2e" />

   

   Após esse processo, o seu computador estará concectado com o Sparki e pronto para ser usado, basta selecionar a porta conectada ao USB e a placa que tem como nome ArcBotics Sparki.

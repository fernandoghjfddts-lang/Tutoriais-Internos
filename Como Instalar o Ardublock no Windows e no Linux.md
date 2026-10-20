# Instalação do Ardublock no Windows e no Linux 

**Objetivo:** Instalar e utilizar o Ardublock para o Sparki em um computador Windows ou Linux

**Requisitos:** Computador com Windows 10/11 com o Arduino IDE instalado

**Tempo estimado:** 5 minutos

---

## Passo a Passo

1. **Instalando o arquivo do ardublock**:
   Clique no link abaixo e o download do arquivo iniciará imediatamente, caso esteja com o Sparkiduino no Windows, estes passos não são necessários, já que o ardublock já estará presente na aba **Ferramentas**.<https://github.com/ArcBotics/Sparki/blob/master/ArduBlock/ArduBlockTool/tool/ardublock.jar?raw=true>
2. **Localizando a pasta da IDE:** 
   Abra o arduino IDE no computador e vá para **Arquivo** e depois **Preferências**, clique em Preferências e procure por **Local do sketchbook**



   
3. **Modificando a pasta:**
   Após descobrir o local do sketchbook, vá até os arquivos de seu computador e pesquise pelo nome da pasta ali descrito, uma vez dentro da pasta siga o seguinte:
   -Crie uma uma pasta chamada **“tools”**
   -Crie uma pasta dentro de tools chamada “**ArduBlockTool**”
   -Crie outra pasta dentro de ArduBlockTool chamada “**tool**”
   -Por fim, envie o arquivo **ardublock**, previamente instalado para a pasta tool e feche o arduino IDE.
   
5. **Abrindo o Ardublock:**
   Abra o arduino IDE novamente e vá em **Ferramentas**, na parte superior e por lá, será possível acessar o Ardublock, que estará pronto para uso.

   <img width="818" height="637" alt="image" src="https://github.com/user-attachments/assets/5603bde2-9e61-4b84-8e7a-50193d804d79" />

---

## Possíveis Erros e Soluções
*   **Problema:** O Ardublock não aparece na aba Ferramentas do Arduino IDE.
*   **Solução:** Certifique-se de que a estrutura de pastas foi criada exatamente com os nomes corretos **(tools > ArduBlockTool > tool)** e que o arquivo está dentro da última pasta. Lembre-se de reiniciar o Arduino IDE após fazer alterações.

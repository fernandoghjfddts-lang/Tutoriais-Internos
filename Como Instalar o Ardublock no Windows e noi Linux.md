# Instalação do Ardublock no Windows 

**Objetivo:** Instalar e utilizar o Ardublock para o Sparki em um computador Windows

**Requisitos:** Computador com Windows 10/11 com o Arduino IDE instalado

**Tempo estimado:** 5 minutos

---

## Passo a Passo

1. **Instalando o arquivo do ardublock**:
   Clique no link abaixo e o download do arquivo de iniciará imediatamente, caso esteja com o Sparkiduino no Windows, estes passos não são necessários, já que o ardublock já estará presente na aba **Ferramentas**.<https://github.com/ArcBotics/Sparki/blob/master/ArduBlock/ArduBlockTool/tool/ardublock.jar?raw=true>
2. **Localizando a pasta da IDE:** 
   Abre o arduino IDE no computador e vá para **Arquivo** e depois **Preferências**, clique em Preferências e procure por **Local do sketchbook**



   
3. **Modificando a pasta:**
   Após descobrir o local do sketchbook, vá até os arquivos de seu computador e pesquise pelo nome da pasta ali descrito, uma vez dentro da pasta siga o seguinte:
   Crie uma uma pasta chamada **“tools”**, criar uma pasta dentro de tools chamada “**ArduBlockTool**”, e depois crie outra pasta dentro de ArduBlockTool chamada “**tool**”
   Por fim, envie o arquivo **ardublock**, previamente instalado para a pasta tool e feche o arduino IDE.
   
4. **Abrindo o Ardublock:**
   Abra o arduino IDE novamente e vá em **Ferramentas**, na parte superior e por lá, será possível acessar o Ardublock, que estará pronto para uso.

   <img width="818" height="637" alt="image" src="https://github.com/user-attachments/assets/5603bde2-9e61-4b84-8e7a-50193d804d79" />

---

## Possíveis Erros e Soluções
*   **Problema:** [Ex: "O computador não reconhece a placa na porta COM"]
*   **Solução:** [Ex: "Verifique se o cabo USB transmite dados ou instale o driver CH340 no link X."]

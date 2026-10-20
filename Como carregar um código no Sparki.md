# Como carregar um código no Sparki
**Objetivo:** Carregar um código para que o Sparki realize uma ação

**Requisitos:** Computador com o Sparkiduino ou Arduino IDE instalado, um cabo USB e o Sparki.

**Tempo estimado:** 5 minutos

---

## Passo a Passo

1. **Conectando o computador ao sparki** 
   Abra sparkiduino ou a IDE que desejada para carregar o código e conecte o USB no computador e no Sparki
   Após isso, certifique que a porta **ArcBotics Sparki** está conectada, em caso positivo, o Sparki está pronto para receber o código, após alguns detalhes que serão demonstrados no passo 3.
   
  
2. **Carregando o código:**
   Antes de começar a escrever o código, na primeira linha, logo acima de **void setup()**. você deve digitar: **#include <Sparki.h>** para que a biblioteca do robô possa ser acessada

   <img width="1436" height="761" alt="image" src="https://github.com/user-attachments/assets/715aeaa5-5316-4b13-a292-d0e8b233f6f0" />

   Depois disso, está tudo pronto, escreva o código que deseja enviar com a as ações que o Sparki deve fazer, caso não conheça os seus movimentos clique no link a seguir com algumas explicações do que ele pode fazer:
   <https://arcbotics.com/lessons/sparki/>
   Por fim, clique na seta apontando para a direita no canto superior esquerdo e, se tudo der certo, o sparki receberá o comando após alguns segundos de carregamento, não se esqueça de ligar o robô.
   <img width="553" height="352" alt="image" src="https://github.com/user-attachments/assets/4d5b3c40-d7fd-4459-81d0-71f5ce0dd460" />

   Caso algum erro tenha sido cometido o Arduino irá te avisar, basta corrigir e enviar o código novamente.


   



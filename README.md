# Hiper-LGBT

Um poliedro hiperdimensional (Politopo) que representa as definições pessoais de cada um

---

[12/05/2025 02:30] João Vítor Fernandes Dias: Fiquei com vontade de definir a comunidade LGBT matematicamente.

Num espaço N dimensional onde N eu o tamanho do conjunto de espectros possíveis tipo identidade de gênero, orientação sexual, etc.

O problema é que nem tudo consegue se encaixar em uma linha de números reais 🤔
Talvez alguma dessas dimensões precisaria ter uma estrutura diferente
[12/05/2025 02:33] João Vítor Fernandes Dias: Como algumas coisas seriam intervalos, provável um conjunto disso geraria um hyper-poliedro
[12/05/2025 02:38] João Vítor Fernandes Dias: Seria interessante um questionário com um cubo com eixos selecionáveis e que de acordo com as respostas ele fosse sendo preenchido
[12/05/2025 02:38] João Vítor Fernandes Dias: Digo cubo porque todos os valores devem ir de [-1, 1]
[12/05/2025 02:44] João Vítor Fernandes Dias: Orientação sexual
Orientação romântica
Identidade de gênero (a galera fluida seria um hiperpoliedro pulsante)
Sexo
Expressão de gênero
[12/05/2025 02:44] João Vítor Fernandes Dias: Aiai
[12/05/2025 02:45] João Vítor Fernandes Dias: Talvez algumas dessas possam ser discretas e não contínuas
[12/05/2025 02:45] João Vítor Fernandes Dias: Enfim

---

Para desenhar um cubo no GeoGebra 3D que represente o espaço $[0,1] \times [0,1] \times [0,1]$, você pode seguir estes passos simples:

## **Passo a passo no GeoGebra 3D:**

1. **Abrir o GeoGebra 3D:**
   Vá para o site [GeoGebra 3D Graphing Calculator](https://www.geogebra.org/3d) ou abra o aplicativo 3D da sua instalação.

2. **Inserir os vértices do cubo:**
   Digite no campo de entrada (pressione Enter após cada linha):

   ```geogebra
   A = (0, 0, 0);
   B = (1, 0, 0);
   C = (1, 1, 0);
   D = (0, 1, 0);
   E = (0, 0, 1);
   F = (1, 0, 1);
   G = (1, 1, 1);
   H = (0, 1, 1);
   ```

3. **Criar as arestas:**
   Use o comando `Segmento` para ligar os vértices. Você pode digitar:

   ```geogebra
   Segmento[A, B]
   Segmento[B, C]
   Segmento[C, D]
   Segmento[D, A]
   Segmento[E, F]
   Segmento[F, G]
   Segmento[G, H]
   Segmento[H, E]
   Segmento[A, E]
   Segmento[B, F]
   Segmento[C, G]
   Segmento[D, H]
   ```

4. **(Opcional) Criar as faces como polígonos para deixar o cubo sólido:**
   Para isso, você pode usar o comando `Polígono` em cada face:

   ```geogebra
   Polígono[A, B, C, D]
   Polígono[E, F, G, H]
   Polígono[A, B, F, E]
   Polígono[B, C, G, F]
   Polígono[C, D, H, G]
   Polígono[D, A, E, H]
   ```

Depois disso, você verá um cubo 3D exatamente no intervalo $[0,1]$ em cada dimensão.

Deseja também rotacionar ou animar o cubo?

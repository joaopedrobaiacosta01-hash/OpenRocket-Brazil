# Guide 02 — Understanding the Nose Cone (Ogiva)

**Language / Idioma:** [English](#english) | [Português](#português)

------------------------------------------------------------------------------------------

## English

### Before we start
OpenRocket is a simulator — don't expect perfectly realistic results.
Its real power is letting you **test small, medium, or drastic changes**
to your design before building anything physically.

### Do not use the pre-defined library
When you open the nose cone component, OpenRocket will suggest
pre-defined models. **Close this window.** Those models are designed
for solid-propellant rockets with conventional body tubes — not PET
bottle rockets, which have different dimensions and attachment methods.
We will build our own from scratch.

### Measuring your nose cone
Before configuring anything in OpenRocket, measure your physical nose
cone with a ruler, tape measure, or preferably a **caliper** (most
precise). The most critical measurement is the **base diameter** —
this must match the mouth of your bottle exactly, or the nose cone
will detach during flight.

> 💡 **Brazilian tip:** For 2L returnable Coca-Cola bottles, a base
> diameter of **10.3 to 10.4 cm** fits perfectly.

------------------------------------------------------------------------------------------


### Nose Cone Shape
Choose your shape based on your own test results and altitude records.
**Conical shapes are not recommended.** The most common choices are:

- **Ogive** — classic shape, good stability
- **Haack series** — minimizes drag for fixed length and diameter
- **Parabolic** — good general performance

Each shape has a description on the right side of the configuration window.

------------------------------------------------------------------------------------------


### Length
Choose a length that works for your design, but remember: this directly
affects your rocket's **Center of Gravity (CG)** and **Center of
Pressure (CP)**. Lengths between 12 and 25 cm have worked well in
Brazilian competitions — but every rocket is different.

------------------------------------------------------------------------------------------


### Base Diameter
As mentioned, this is critical. Measure carefully. A nose cone that
is too loose will fly off at launch.

------------------------------------------------------------------------------------------


### Wall Thickness
Import your real-world nose cone dimensions using a caliper or tape
measure. Recommended thickness: **below 0.08 cm**. Thinner values
like 0.04 cm are used by many Brazilian competitors, but be careful —
thinner walls break more easily when pressing the cone onto the bottle.

------------------------------------------------------------------------------------------


### Component Material
Most materials in OpenRocket are too heavy for PET bottle rockets —
they are designed for solid-propellant rockets. Use only:

- **PLA or ABS** (3D printed nose cones)
- **PET bottle + durapoxi** (epoxy putty used to shape and harden
  the tip — widely used in Brazilian competitions)

If your material is not listed, calculate its density and create a
custom material in OpenRocket.

------------------------------------------------------------------------------------------


### Surface Finish
Not critical, but if you polished or modified the external surface
of your nose cone, update this field to match.

------------------------------------------------------------------------------------------


### Override Tab
Use this tab to manually enter your **real nose cone mass** — the
value calculated automatically by OpenRocket from dimensions alone
is often imprecise. You can also manually override the CG position
to run experimental simulations.

------------------------------------------------------------------------------------------


### Mass Component (Nose Weight)
Adding mass to the nose cone tip improves rocket stability by moving
the CG forward. This is where **durapoxi** comes in for PET rockets.

To add it in OpenRocket:
1. Click your nose cone to select it
2. Go to **"Add new component"** on the right panel
3. Scroll to the bottom and select **"Mass component"**
4. Enter the mass in grams that matches your real nose weight
5. Length and diameter fields won't affect simulation — focus on mass

> 💡 Adjust this value across multiple simulations to find the
> optimal nose weight for your CG target.

------------------------------------------------------------------------------------------


## Português

### Antes de começar
O OpenRocket é um simulador — não espere resultados perfeitamente
realistas. Seu verdadeiro poder está em te permitir **testar mudanças
pequenas, médias ou drásticas** no seu projeto antes de construir
qualquer coisa fisicamente.

### Não use a biblioteca pré-definida
Ao abrir o componente de ogiva, o OpenRocket vai sugerir modelos
pré-definidos. **Feche essa janela.** Esses modelos são projetados
para foguetes de propulsão sólida com corpos tubulares convencionais
— não para foguetes de garrafa PET, que têm dimensões e formas de
encaixe diferentes. Vamos montar a nossa do zero.

### Medindo sua ogiva
Antes de configurar qualquer coisa no OpenRocket, meça sua ogiva
física com uma régua, trena ou, de preferência, um **paquímetro**
(mais preciso). A medida mais importante é o **diâmetro da base** —
ele precisa corresponder exatamente à boca da sua garrafa, ou a ogiva
sairá voando no lançamento.

> 💡 **Dica brasileira:** Para garrafas retornáveis de Coca-Cola 2L,
> um diâmetro de base de **10,3 a 10,4 cm** encaixa perfeitamente.

------------------------------------------------------------------------------------------


### Forma da Ogiva
Escolha a forma com base nos seus testes e maiores altitudes
registradas. **Não recomendamos o uso de cônicas.** As mais comuns são:

- **Ogival** — forma clássica, boa estabilidade
- **Série de Haack** — minimiza o arrasto para comprimento e diâmetro fixos
- **Parabólica** — bom desempenho geral

Cada forma tem uma descrição no lado direito da janela de configuração.

------------------------------------------------------------------------------------------


### Comprimento
Escolha um comprimento favorável ao seu projeto, mas lembre-se: isso
afeta diretamente o **Centro de Gravidade (CG)** e o **Centro de
Pressão (CP)** do seu foguete. Comprimentos entre 12 e 25 cm já
funcionaram bem em competições brasileiras — mas cada foguete é diferente.

------------------------------------------------------------------------------------------


### Diâmetro da Base
Como dito, isso é fundamental. Meça com cuidado. Uma ogiva folgada
demais sairá no momento do lançamento.

------------------------------------------------------------------------------------------


### Espessura da Parede
Importe as dimensões reais da sua ogiva usando paquímetro ou trena.
Espessura recomendada: **abaixo de 0,08 cm**. Valores menores como
0,04 cm são usados por muitos competidores brasileiros, mas atenção —
paredes mais finas quebram com mais facilidade ao encaixar na garrafa.

------------------------------------------------------------------------------------------


### Material do Componente
A maioria dos materiais no OpenRocket é pesada demais para foguetes
de garrafa PET — são voltados para foguetes de propulsão sólida.
Use apenas:

- **PLA ou ABS** (ogivas impressas em 3D)
- **Garrafa PET + durapoxi** (massa epóxi usada para moldar e
  endurecer a ponta — muito usada em competições brasileiras)

Se o seu material não estiver na lista, calcule sua densidade e crie
um material personalizado no OpenRocket.

------------------------------------------------------------------------------------------


### Acabamento do Componente
Não é crítico, mas se você poliu ou modificou a superfície externa
da ogiva, atualize este campo para corresponder.

------------------------------------------------------------------------------------------


### Aba Modificar
Use esta aba para inserir manualmente a **massa real da sua ogiva** —
o valor calculado automaticamente pelo OpenRocket a partir das dimensões
costuma ser impreciso. Você também pode sobrescrever a posição do CG
para rodar simulações experimentais.

------------------------------------------------------------------------------------------


### Componente de Massa (Peso da Ponta)
Adicionar massa na ponta da ogiva melhora a estabilidade do foguete,
movendo o CG para frente. É aqui que entra o **durapoxi** nos foguetes
de PET.

Para adicionar no OpenRocket:
1. Clique na sua ogiva para selecioná-la
2. Vá em **"Adicionar novo componente"** no painel direito
3. Desça até o final e selecione **"Componente de massa"**
4. Insira a massa em gramas correspondente ao peso real da sua ponta
5. Comprimento e diâmetro não afetam a simulação — foque na massa

> 💡 Ajuste esse valor em múltiplas simulações para encontrar o
> peso ideal de acordo com o seu CG alvo.

------------------------------------------------------------------------------------------


*Next guide: [03 - Rocket Body & Fins](03-body-and-fins.md)* / Próximo guia: [03 - Corpo e Aletas do Foguete](03-body-and-fins.md)*

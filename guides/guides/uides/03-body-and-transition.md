# Guide 03 — Body Tube & Transition

**Language / Idioma:** [English](#english) | [Português](#português)

---

## English

> If you haven't completed the previous guide, go back before continuing.
> Understanding the nose cone configuration is essential for this step.

### Overview
OpenRocket gives us a wide range of options to import our physical
bottle into the software. I'll show you **two methods** — simple and
complex. Both require more than one bottle if you don't already have
a ready-made file.

**We'll start with the simple method.**

Your rocket will look something like this:

<img width="841" height="231" alt="image" src="https://github.com/user-attachments/assets/9f0703cf-93ce-4d0a-abdd-c07bbaef501c" />


Don't underestimate this method — I've seen record-breaking medalists
use it and reach altitudes above 300m.

---

### Body Tube

In the **"Add new component"** panel (next to the nose cone tab),
click **"Body tube"**. A configuration window will open.

<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/40dd5c46-4d8d-4e9c-9d3b-7e5c69625753" />



**Length** — measure with a tape measure or caliper.

**External Diameter** — you'll need to measure your bottle's
circumference first. Two ways to do this:

1. **Tape measure** — wrap it around the bottle directly
2. **String method** — wrap a string or white ribbon around the
   bottle, mark where it completes the loop, then lay it flat on
   a ruler to read the circumference

Once you have the circumference, divide by **π (3.14)** to get
the external diameter:
```
diameter = circumference ÷ 3.14
```

The **internal diameter** is set automatically by OpenRocket.

**Wall thickness** — bottles rated for up to 200 PSI
(the pressure commonly used in Brazilian competitions) typically
have a wall thickness of **0.1 cm**. Standard cheap bottles cannot
handle even 110 PSI — their walls are thinner and the material
is lower quality.

---

### Transition

The transition component is in the tab next to the body tube tab.

- **Shape & form parameter** — depende do tipo de garrafa usada,
- então você terá que ver qual é o melhor pra sua garrafa
- **Length** — measure physically
- **Internal diameter** — leave on automatic, it will follow the body tube
- **Stern diameter** — cut the neck of the bottle and measure the diameter of the resulting cut.

> 💡 Separate the transition section from the body as shown:

<img width="500" height="800" alt="image" src="https://github.com/user-attachments/assets/2d3bd9ad-fe0a-4dd4-8141-f4f3c6f6c9d6" />

Some bottles have a **different wall thickness** in the transition
area — measure this separately for better accuracy.

**Don't forget to weigh each physical part of your rocket** and
enter the mass manually for maximum simulation precision.

With everything configured correctly, your project should look like:

<img width="533" height="287" alt="image" src="https://github.com/user-attachments/assets/ff918b9d-6c71-49e3-bbb4-4ec361a127da" />

---

## Português

> Se você não completou o guia anterior, volte antes de continuar.
> Entender a configuração da ogiva é essencial para esta etapa.

### Visão geral
O OpenRocket nos abre um verdadeiro leque de opções para importarmos
nossa garrafa física para o software. Mostrarei **duas formas** —
a simples e a mais complexa. Ambas precisam de mais de uma garrafa,
caso você não tenha um arquivo pronto.

**Começaremos pela forma simples.**

Seu foguete ficará basicamente assim:

<img width="841" height="231" alt="image" src="https://github.com/user-attachments/assets/68bcac21-7ea3-43d1-852e-1c1767fb1fc0" />


Não se engane com a simplicidade — já vi muitos medalhistas
recordistas usarem este método e baterem altitudes absurdas,
passando dos 300m.

---

### Tubo do Corpo

No painel **"Adicionar novo componente"** (ao lado da aba da ogiva),
clique em **"Tubo do corpo"**. Uma janela de configuração será aberta.

<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/40dd5c46-4d8d-4e9c-9d3b-7e5c69625753" />

**Comprimento** — meça com trena ou paquímetro.
**Diâmetro externo** — você precisará medir a circunferência da
garrafa primeiro. Duas formas de fazer isso:

1. **Trena** — enrole diretamente ao redor da garrafa
2. **Método do barbante** — enrole um barbante ou fita branca ao
   redor da garrafa, marque onde ela completa a volta, depois
   coloque sobre uma régua para ler a circunferência

Com a circunferência em mãos, divida por **π (3,14)** para obter
o diâmetro externo:
```
diâmetro = circunferência ÷ 3,14
```

O **diâmetro interno** é definido automaticamente pelo OpenRocket.

**Espessura da parede** — garrafas que suportam até 200 PSI
(pressão comum nas competições brasileiras) têm espessura de
**0,1 cm**. Garrafas convencionais baratas não aguentam nem 110 PSI
— suas paredes são mais finas e o material é de menor qualidade.

---

### Transição

O componente de transição fica na aba ao lado da aba do tubo do corpo.

<img width="350" height="360" alt="image" src="https://github.com/user-attachments/assets/560c3081-9814-48b1-8f24-5ce402bc16a6" />

- **Forma e parâmetro de forma** — depende do tipo de garrafa usada,
- então você terá que ver qual é o melhor pra sua garrafa
- **Comprimento** — meça fisicamente
- **Diâmetro interno** — deixe no automático, seguirá o do corpo
- **Diâmetro da popa** — corte o gargalo da garrafa e meça o diametro do
- corte que ficou

> 💡 Separe a parte de transição do corpo como mostrado:

<img width="500" height="800" alt="image" src="https://github.com/user-attachments/assets/2d3bd9ad-fe0a-4dd4-8141-f4f3c6f6c9d6" />


Algumas garrafas têm **espessura diferente** na região de transição
— meça separadamente para maior precisão.

**Não se esqueça de pesar cada parte física do seu foguete** e
inserir a massa manualmente para maior precisão na simulação.

Com tudo configurado corretamente, seu projeto deve estar assim:

<img width="533" height="287" alt="image" src="https://github.com/user-attachments/assets/ff918b9d-6c71-49e3-bbb4-4ec361a127da" />

---

## The Complex Method / Método Complexo

### English

Now that you've mastered the simple method, let's go deeper.

If you've followed everything so far and have more than one bottle,
this won't be difficult — but it will require **precise measurements
of every curve and section** of your bottle.

Take this bottle as an example:

<img width="900" height="518" alt="image" src="https://github.com/user-attachments/assets/6318bb69-fcf2-448b-9c41-2a72c6b2dc1f" />


Notice how it has **multiple curves**. Each one needs to be carefully
measured and imported. Here is how the same bottle looks in OpenRocket:

<img width="877" height="196" alt="image" src="https://github.com/user-attachments/assets/ffd635da-1b54-451f-8693-d954769827a4" />

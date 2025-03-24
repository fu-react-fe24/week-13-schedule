# Schema, vecka 13
###### Frontendramverk, vecka 1 av 7

## Introduktion

React är ett av de mest populära ramverken för att bygga moderna webbapplikationer. I denna modul kommer vi att gå igenom grunderna i React, inklusive hur vi bygger komponenter och skickar data mellan dem med hjälp av props. 
Vi kommer också att utforska JSX och varför det är så kraftfullt. Efter denna modul kommer du ha en stabil grund för att skapa dina första React-appar!

## Mål för veckan:

1. Förstå poängen med att använda ett ramverk framför vanilla JS
2. Förstå hur man skapar ett Reactprojekt
3. Förstå den grundläggande syntaxen och strukturen i React
4. Förstå vad komponenter är och vilken funktion de fyller
5. Förstå hur vi kan använda props för att skicka data mellan komponenter

## Resurser

### Presentationer

* [01 - Kursintro](https://docs.google.com/presentation/d/1GD7EeyVyZ6WR3PbXdQeKzbsS1x_TVF34/edit?usp=sharing&ouid=117251319654116712560&rtpof=true&sd=true)
* [02 - React Intro](https://docs.google.com/presentation/d/1KKuerOHMcscaWzk3Nr5wqKFiR2A0KsLS/edit?usp=sharing&ouid=117251319654116712560&rtpof=true&sd=true)
* [03 - Props](https://docs.google.com/presentation/d/1gfgpzW9069iKEDTRGBTnXBNnlKIuEiUM/edit?usp=sharing&ouid=117251319654116712560&rtpof=true&sd=true)

### Inspelade föreläsningar

**LIVE**

* [Kursintro](https://funet-my.sharepoint.com/:v:/g/personal/jesper_nyberg_folkuniversitetet_se/EfXcKuIrEDJKvFTDmQMcSuwBwA51tOAYiouMu0xVw3xptw?e=1k6KX4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) - Måndag eftermiddag
* [React grunder del 1](https://funet.sharepoint.com/:v:/s/FrontendutvecklareYH-Fe24Karlstad-Arvika/EaMt287a-YFAlBcp2CLvMa0BJ9HQ3BBCMayRn3NBVg0GbQ?e=VwJK4R&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) - Måndag förmiddag Karlstad
* [React grunder del 2](https://funet.sharepoint.com/:v:/s/FrontendutvecklareYH-Fe24Karlstad-Arvika/EYM33SAky7lIlOQ9l0_iXFABl3QmhjXYZjRsSBMnAeSayg?e=NucvjE&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) - Måndag förmiddag Karlstad
* [Props](https://funet-my.sharepoint.com/:v:/g/personal/jesper_nyberg_folkuniversitetet_se/EQ0D5ZbTuRRAvjKFPcmMJzQB-Qj3cWMnefs7E5TPnNddKg?e=YqwsQH&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) - Måndag eftermiddag

**Förinspelat** (för distansklassen)

* [01 - Introduktion till Ramverk](https://vimeo.com/1037398603/1c3556aede?share=copy) - till måndag
* [02 - React Intro](https://vimeo.com/1036790690/e4876fe825?share=copy) - till måndag
* [03 - Props](https://vimeo.com/1036792261/c39e695e41?share=copy) - inte nödvändigt, detta kommer vi gå igenom och koda upp tillsammans på måndag eftermiddag!

### Lektionsrepon

* [24 mars](https://github.com/fu-react-fe24/week-13-lecture-24-mars) - gemensam
* [25 mars](https://github.com/fu-react-fe24/week-13-lecture-25-mars) - distans
* [26 mars](https://github.com/fu-react-fe24/week-13-lecture-26-mars) - Karlstad-Arvika

### Filmer

* [ReactJS Tutorial](https://www.youtube.com/playlist?list=PLSsAz5wf2lkK_ekd0J__44KG6QoXetZza) - Film 1 till 20 är relevanta för den första veckan
* [Learn React JS - Full Beginner’s Tutoria, 16h](https://www.youtube.com/watch?v=x4rFhThSX04)

### Länkar

* [React-dokumentation](https://react.dev/)
* [Node.js installation](https://nodejs.org/en)
* [Node Package Manager - hitta bibliotek](https://www.npmjs.com/)
* [Scrimba React Course](https://scrimba.com/learn-react-c0e)
* [React Developer Tools](https://chromewebstore.google.com/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en&pli=1)

### Övningar 

* [Min första React-app](https://github.com/fu-react-fe24/week-13-exercise-first-react-app)
* [Components Bootcamp](https://github.com/fu-react-fe24/week-13-exercise-components-bootcamp)
* [Book Store](https://github.com/fu-react-fe24/week-13-exercise-props-bookstore) - Veckans Code Review-uppgift







<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Esse repositório é uma cópia do repositório do meu professor.

AQUI EU ADICIONEI NO FINAL DA PÁGINA O MEU MODELO DE PROMPT
- Fiz isso para treinar o que aprendi na aula.
-
-   projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta gerado através do prompt proposto pela aluna

Perfeito! Vamos montar um treino para chegarmos juntos no seu objetivo

Biotipo: Endomorfo (tem mais facilidade para ganhar gordura, então o foco é queimar calorias e manter músculo)

Frequência: 5 dias por semana

Divisão: Treino ABCDE

Estilo: Funcional e Crossfit (exercícios dinâmicos, corpo inteiro, intensidade alta)

🏋️‍♀️ Treino ABCDE Funcional + CrossFit 

 A - MEMBROS INFERIORES (PERNAS + GLÚTEOS)
 
Aquecimento: 5 min de polichinelo + agachamento com peso corporal

Agachamento com halteres – 4x12

Afundo alternado com passada – 3x12 por perna

Stiff com kettlebell – 3x10

Pliometria (caixa/step up com salto) – 3x10

Finalização: 3 rounds – 30 seg de corrida no lugar + 10 agachamentos + 10 burpees


B - PEITO + CARDIO INTENSO

Aquecimento: 2 rounds de 20 mountain climbers + 10 flexões

Flexão de braço – 4x10 (ajoelhado ou tradicional)

Flexão com batida de ombro – 3x8

Supino com halteres ou elástico – 4x12

Corrida estacionária + burpee (EMOM) – 10 min (a cada minuto: 5 burpees + 20 seg de corrida)

C - COSTAS + CORE
 
Aquecimento: 3x 15 seg prancha + 10 anjos invertidos

Remada com halteres ou elástico – 3x12

Superman com pausa – 4x15

Prancha isométrica – 3x 30 seg

Abdominal com perna estendida + toque no pé – 3x20

Finalização: 3 rounds – 20 Russian twists + 15 mountain climbers + 10 burpees


D – PERNAS E CORE (foco em potência e queima calórica)

Aquecimento: 4 min circuito – 20 agachamentos + 10 saltos verticais

Agachamento com salto – 4x12

Pistol squat assistido (ou agachamento unilateral) – 3x8 cada perna

Prancha com joelho ao cotovelo – 3x10 cada lado

Sit-up completo com bola ou halteres leves – 3x20

Finalização estilo Tabata (20 seg on / 10 seg off por 4 min)

Polichinelo

Burpee

Abdominal

Corrida estacionária


E – OMBROS + HIIT GERAL

Aquecimento: 3 rounds – 10 polichinelos + 10 giros de braço + 10 agachamentos

Desenvolvimento com halteres – 3x10

Elevação frontal + lateral combinada – 3x12

Pike push-up (flexão para ombros) – 3x8

Final: circuito de 15 min AMRAP (o máximo de rounds possível)

10 burpees

10 swings com kettlebell ou mochila

20 mountain climbers

15 agachamentos



Dicas extras maromba:
Alimente-se bem antes e após o treino, focando em proteínas e controle de carboidratos.

Priorize o descanso e o sono para recuperar e evitar acúmulo de gordura.

Treinos intensos e variados como esse ajudam a acelerar o metabolismo e queimar gordura mantendo o músculo.






 
 




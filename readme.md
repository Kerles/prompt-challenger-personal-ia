<h3 align="center">Criando um Personal Trainer IA com Boas Práticas de Prompt Engineer usando Claude 3.5 Sonnet</h3>
<p align="center">
    <img width="300px" src="https://github.com/user-attachments/assets/24c920b5-c50e-41ae-b355-a64517a8a53f">

</p>

<p align="center">
<a href="https://en.wikipedia.org/wiki/Artificial_intelligence"><img src="https://img.shields.io/badge/AI-Project-FED564?logo=openai" alt="AI - Project"></a>
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=vimeo" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Vá para a página inicial do Bash"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Feito com Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS"><img src="https://img.shields.io/badge/Powered%20by-aws-FED564?logo=icloud&logoColor=white" alt="Powered by AWS"></a>
<a href="https://aws.amazon.com/bedrock/claude/?sec=bcomfai&pos=3" title="Powered by Anthropic"><img src="https://img.shields.io/badge/Powered%20by-Anthropic-FED564?logo=Anthropic&logoColor=white" alt="Powered by Anthropic"></a>

</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---


## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** 
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
 
</table>


2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
 
| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino Funcional            |
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
4. Use o prompt do assistente para gerar um plano de treino personalizado.
<p>Este plano de treino foi desenvolvido especificamente para um biotipo ectomorfo, focando em exercícios compostos e funcionais que estimulam o ganho de massa muscular e força. Aqui estão algumas observações adicionais:</p> 

1. Frequência: O plano distribui o trabalho ao longo de 5 dias, permitindo um bom equilíbrio entre estímulo e recuperação.
2. Progressão: À medida que você se adaptar, aumente gradualmente o número de repetições ou adicione peso aos exercícios.
3. Nutrição: Para um ectomorfo, é crucial manter uma dieta hipercalórica rica em proteínas para suportar o ganho de massa muscular.
4. Descanso: Garanta 7-9 horas de sono por noite para uma recuperação adequada.
5. Core: Embora não haja treinos abdominais específicos, muitos exercícios engajam o core, proporcionando fortalecimento indireto.

---

# 🎯 Prompt de Resposta Proposto 


# Plano de Treino Funcional para Ectomorfo - 5 dias por semana

## Objetivo: Ganho de massa muscular e força

### Dia 1: Pernas e Glúteos
1. Agachamento com peso corporal: 3 séries de 15 repetições
2. Afundo alternado: 3 séries de 12 repetições por perna
3. Ponte de glúteos: 3 séries de 15 repetições
4. Subida no step: 3 séries de 12 repetições por perna
5. Agachamento com salto: 3 séries de 10 repetições

### Dia 2: Peito e Tríceps
1. Flexão de braço: 3 séries de 10-12 repetições
2. Mergulhos em banco: 3 séries de 10-12 repetições
3. Flexão com pés elevados: 3 séries de 10 repetições
4. Tríceps no banco: 3 séries de 12 repetições
5. Prancha com toque no ombro: 3 séries de 30 segundos

### Dia 3: Costas e Bíceps
1. Remada invertida: 3 séries de 12 repetições
2. Superman: 3 séries de 15 repetições
3. Flexão de braço com remada: 3 séries de 10 repetições
4. Rosca bíceps com garrafa d'água: 3 séries de 12 repetições
5. Prancha lateral: 3 séries de 30 segundos (cada lado)

### Dia 4: Ombros e Core
1. Elevação lateral com garrafa d'água: 3 séries de 12 repetições
2. Pike push-up: 3 séries de 10 repetições
3. Círculos com os braços: 3 séries de 15 repetições
4. Mountain climbers: 3 séries de 30 segundos
5. Prancha com elevação alternada de pernas: 3 séries de 30 segundos

### Dia 5: Circuito Full Body
1. Burpees: 45 segundos
2. Polichinelos: 45 segundos
3. Agachamento com salto: 45 segundos
4. Flexão de braço: 45 segundos
5. Corrida parada: 45 segundos
- Repita o circuito 3-4 vezes, com 1 minuto de descanso entre cada rodada

### Observações:
- Realize um aquecimento de 5-10 minutos antes de cada sessão
- Descanse 30-60 segundos entre as séries
- Mantenha-se hidratado durante os treinos
- Aumente gradualmente a intensidade e o peso conforme sua adaptação
- Inclua exercícios de alongamento ao final de cada sessão

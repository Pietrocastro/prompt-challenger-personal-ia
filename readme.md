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
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
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

## 🎯 Prompt de Resposta Proposto

Contexto
Você é um Personal Trainer expert e dedicado, especializado em criar programas de treinamento personalizados. Sua missão é desenvolver um plano de treino sob medida para cada cliente, considerando suas características individuais, objetivos e limitações. Inicie a interação com uma saudação apropriada ao horário (Bom dia, Boa tarde ou Boa noite) e peça o nome do cliente.

Variáveis a serem coletadas
{{nome_cliente}}
{{idade}}
{{sexo}}
{{peso}}
{{altura}}
{{nível_atividade_física_atual}}
{{objetivo_principal}}
{{objetivo_secundário}}
{{disponibilidade_treino}}
{{tipo_de_treino_preferido}}
{{equipamentos_disponíveis}}
{{restrições_alimentares}}
{{restrições_médicas}}
{{hábitos_de_sono}}
{{nível_de_estresse}}
{{preferências_musicais}}
Escopos das variáveis
{{biotipo}}

A) Ectomorfo: Corpo naturalmente magro, metabolismo acelerado, dificuldade em ganhar peso e massa muscular. B) Mesomorfo: Corpo atlético, facilidade em ganhar massa muscular e perder gordura, boa resposta ao treinamento. C) Endomorfo: Corpo com tendência a acumular gordura, metabolismo mais lento, maior dificuldade em perder peso.

{{disponibilidade_treino}}

A) 1-2 dias por semana: Treino Full Body B) 3-4 dias por semana: Treino ABC ou Upper/Lower Split C) 5-6 dias por semana: Treino ABCDE ou Push/Pull/Legs

{{tipo_de_treino}}

A) Funcional: Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais e múltiplos grupos musculares. B) Maquinário: Exercícios realizados em equipamentos, focados em isolar grupos musculares específicos. C) Peso Livre: Exercícios com pesos livres (halteres, barras, kettlebells) para trabalhar múltiplos grupos musculares simultaneamente. D) Cardio: Exercícios aeróbicos para melhorar a resistência cardiovascular (corrida, natação, ciclismo). E) HIIT: Treinos intervalados de alta intensidade, eficientes para queima de gordura e condicionamento.

{{faixa_etaria}}

A) 18 a 29 anos B) 30 a 39 anos C) 40 a 49 anos D) 50 anos ou mais

{{objetivo_principal}}

A) Perda de gordura B) Ganho de massa muscular C) Melhora do condicionamento físico D) Aumento da força E) Melhora da flexibilidade e mobilidade

{{nivel_condicionamento}}

A) Iniciante: Pouca ou nenhuma experiência com exercícios regulares B) Intermediário: Pratica exercícios há alguns meses, familiarizado com técnicas básicas C) Avançado: Treina consistentemente há anos, bom conhecimento de técnicas e princípios de treino

{{restricoes_medicas}}

A) Nenhuma restrição conhecida B) Problemas articulares (especifique: joelho, ombro, costas, etc.) C) Condições cardiovasculares (hipertensão, etc.) D) Outras (especifique)

{{nível_atividade_física_atual}}

A) Sedentário B) Levemente ativo C) Moderadamente ativo D) Ativo

{{tipo_de_treino_preferido}}

A) Não tem preferência B) Treinos em grupo C) Treinos individuais D) Treinos ao ar livre E) Treinos em casa

{{equipamentos_disponíveis}}

A) Nenhum equipamento B) Halteres C) Barra fixa D) Bandas elásticas E) Outros (especificar)

{{restrições_alimentares}}

A) Nenhuma restrição B) Vegetariano C) Vegano D) Intolerância à lactose E) Alergia a algum alimento (especificar) F) Restrições por motivos religiosos ou culturais

{{hábitos_de_sono}}

A) Durmo bem e acordo descansado B) Tenho dificuldade para dormir C) Acordo cansado com frequência D) Durmo pouco (menos de 7 horas por noite)

{{nível_de_estresse}}

A) Baixo B) Moderado C) Alto

{{preferências_musicais}}

(livre)

Conduta
Cumprimente o cliente e peça seu nome.
Coleta de dados: Faça perguntas detalhadas sobre cada variável, incluindo:
Objetivos: Perguntar sobre objetivos específicos (ex: perder 5kg em 3 meses) e o motivo pelo qual o cliente deseja alcançar esse objetivo.
Hábitos: Perguntar sobre hábitos alimentares, rotina de sono, nível de estresse e outras atividades físicas.
Preferências: Perguntar sobre preferências de exercícios, horários para treinar, tipo de música que o motiva, etc.
Restrições: Perguntar sobre quaisquer restrições alimentares, médicas ou de equipamentos.
Confirmação dos dados: Repetir as informações coletadas para garantir que estejam corretas.
Criação do plano: Desenvolver um plano de treino personalizado, incluindo:
Exercícios específicos
Séries e repetições
Frequência e duração dos treinos
Progressão gradual dos exercícios
Dicas de nutrição e recuperação
Calendário visual dos treinos
Entrega do plano: Apresentar o plano de treino ao cliente de forma clara e concisa, utilizando uma linguagem simples e exemplos práticos.
Educação:
Base de conhecimento: Crie uma base de conhecimento com artigos e vídeos sobre nutrição, exercícios, anatomia e outros temas relevantes.
Quizzes e testes: Desenvolva quizzes para avaliar o conhecimento do usuário e oferecer conteúdo personalizado.
Dicas diárias: Envie dicas rápidas e concisas sobre diversos temas, como a importância da hidratação ou os benefícios do sono.
Motivação:
Histórias de sucesso: Compartilhe histórias de outros usuários que alcançaram seus objetivos.
Desafios semanais: Crie desafios personalizados para manter o usuário engajado.
Celebração de conquistas: Reconheça e celebre as conquistas do usuário.
Resultados esperados
Com base nas informações coletadas, você deverá:

Criar um plano de treino personalizado que inclua:
Frequência semanal de treinos
Tipos de exercícios recomendados
Intensidade e volume apropriados
Progressão sugerida ao longo do tempo
Fornecer uma breve explicação sobre como o plano se adequa às necessidades específicas do cliente.
Oferecer dicas de nutrição e recuperação que complementem o plano de treino.
Sugerir formas de monitorar o progresso e ajustar o plano conforme necessário.
Perguntar se o cliente tem dúvidas ou precisa de esclarecimentos adicionais.
Criar um calendário visual e realizar a entrega personalizada do plano.
Personalização e engajamento:
Linguagem natural: Utilize uma linguagem natural e amigável para criar uma conversa mais humana.
Personalização: Adapte as mensagens e o conteúdo de acordo com as preferências e o progresso do usuário.
Feedback: Incentive o feedback do usuário para melhorar o serviço. Exemplo de diálogo:
Chatbot: E aí, campeão! Preparado para mais um dia de treino? Lembre-se, cada gota de suor te leva mais perto dos seus objetivos!
Usuário: Tô na luta! Mas tô sentindo um pouco de dor no joelho. O que faço?
Chatbot: Entendo sua preocupação! Que tal darmos uma olhada em alguns exercícios alternativos para fortalecer os joelhos? Tenho um vídeo bem legal pra te mostrar.
Lembre-se de manter um tom profissional, motivador e empático durante toda a interação

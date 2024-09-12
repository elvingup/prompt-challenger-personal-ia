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
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt é capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto foi feito utilizando as boas práticas de prompt engineer.
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

Este projeto é um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

Obs.: o prompt inicial inclui um [arquivo anexo](prompt.xml) junto com a instrução.

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
gere o output para o input do arquivo prompt.xml que está anexo
#### arquivo anexo
O conteúdo do arquivo anexo [prompt.xml](prompt.xml) segue abaixo:
<input>
    <info>
        
        <info>
            a tag reference se refere a referência, que é a relação estabelecida entre um signo linguístico e o objeto ao qual ele se refere conforme um determinado contexto. Essa relação pode ser direta ou indireta, concreta ou abstrata, e varia de acordo com a natureza do signo e do referente. Características da referência: § intencionalidade: a referência pressupõe a intenção de um falante ou escritor em designar algo específico; § contextualidade: o significado de um signo e sua referência podem variar de acordo com o contexto em que são utilizados; § arbitrariedade: a relação entre um signo e seu referente é, em grande parte, arbitrária e culturalmente determinada; § ambiguidade: um mesmo signo pode ter diferentes referências em diferentes contextos ou para diferentes pessoas. Tipos de referência: o signo se refere a um objeto ou entidade existente no mundo real; o signo se refere a um conceito abstrato, uma propriedade ou uma relação entre objetos; o signo depende do contexto situacional para determinar sua referência; o signo se refere a um elemento mencionado anteriormente no texto. A referência é um conceito central para a semântica e a pragmática, e sua exploração permite uma análise mais profunda da linguagem e do pensamento humano.
        </info>
        <info>
            a tag bizz se refere à lógica de negócio.
        </info>
        <info>
            a tag do-not se refere a prompt negativo: então, evite fazer o que está determinado na tag do-not
        </info>
    </info>

    <requirements>
        <demand>
            a tag goal§info contém as informações disponibilizadas pelo usuário. Portanto, referencie-se à tag goal§info para gerar o regime de exercícios físicos.
        </demand>
        <bizz>
            <do-not>
                Informação inexata
                Falta de referências técnicas
                Tom informal 
            </do-not>
        
            <to-do>
                Informação exata 
                Cada informação está referenciada a alguma fonte técnica 
                Tom formal 
            </to-do>
        </bizz>
        
        <view>
            Tabela.
        </view>
        <caution>
            <caution>
                Se não souber a informação: então, responda o seguinte: 'Não sei!'
            </caution>
        </caution>
    </requirements>

    <reference>
        <reference>
            ### Biotipo Corporal
            Os biotipos corporais são geralmente classificados em três categorias principais:
            1. **Ectomorfo**: Corpo magro, dificuldade para ganhar massa muscular.
            2. **Endomorfo**: Corpo mais arredondado, tendência a acumular gordura.
            3. **Mesomorfo**: Corpo musculoso, facilidade para ganhar e manter massa muscular²⁸.

            ### Quantidade de Sessões por Semana
            Para um regime de exercícios eficaz, uma sessão por dia é uma boa frequência. Isso permite um equilíbrio entre treino e recuperação, essencial para evitar lesões e promover ganhos consistentes.

            ### Tipo de Treino
            O tipo de treino deve ser adaptado ao biotipo e aos objetivos pessoais. Aqui estão algumas sugestões:
            - **Ectomorfos**: Treinos de força com foco em ganho de massa muscular, utilizando pesos mais pesados e menos repetições⁴.
            - **Endomorfos**: Combinação de treinos de força e aeróbicos para promover a perda de gordura e ganho de massa muscular⁵.
            - **Mesomorfos**: Treinos variados que incluem força, resistência e flexibilidade para manter a composição corporal equilibrada⁴.

            ### Referências Técnicas
            Profissionais de educação física consultam diversas referências técnicas para elaborar programas de treino eficazes. Algumas das principais incluem:
            - **Conselho Federal de Educação Física (CONFEF)**: Normas e diretrizes para a prática profissional¹.
            - **Estudos Científicos**: Pesquisas sobre treinamento de força, biotipos e somatotipos¹².
            - **Publicações Especializadas**: Artigos e livros sobre fisiologia do exercício, biomecânica e nutrição esportiva¹⁴.

            (1) Biotipo e Somatotipo: O que é, diferenças e tipos - Treino Mestre. https://treinomestre.com.br/biotipo-e-somatipo-aprenda-o-conceito-correto/.
            (2) Biotipo corporal: o que é, tipos e como identificar - Tua Saúde. https://www.tuasaude.com/como-identificar-o-seu-biotipo/.
            (3) Treino de força: o que é, benefícios e como fazer (com exemplos). https://www.tuasaude.com/treino-de-forca/.
            (4) Biotipos: quais os melhores treinos e dietas para cada um?. https://blog.ciaathletica.com.br/definicao/treinos/biotipos/.
            (5) A IMPORTÂNCIA DO PERSONAL TRAINER NO TREINAMENTO DE FORÇA: UMA REVISÃO .... https://revistaft.com.br/a-importancia-do-personal-trainer-no-treinamento-de-forca-uma-revisao-da-literatura/.
            (6) Biótipos Físicos - Entenda a diferença para cada esporte. https://horadotreino.com.br/biotipos-fisicos-atividades-fisicas/.
            (7) 7 Exercícios para o treino de força: Como deve ser!. https://treinomestre.com.br/exercicios-de-forca-aspectos-praticos-para-seu-treino/.
            (8) Treino de força: o que é, como fazer e exercícios | Growth Blog. https://blog.gsuplementos.com.br/treino-de-forca/.
            (9) Somatótipo - O que é, conceito e definição. https://bing.com/search?q=biotipo+e+somatotipo.
            (10) Biotipos corporales: Conoce los diferentes tipos de cuerpos. https://grullapsicologiaynutricion.com/blog/biotipo-tipos-cuerpos.
            (11) Somatótipo - O que é, conceito e definição. https://conceito.de/somatotipo.
            (12) Os tipos de corpo: somatotipo e biotipo - portalfato.com.br. http://portalfato.com.br/noticia.php?n=10815/Os-tipos-de-corpo:-somatotipo-e-biotipo.
        </reference>
        <reference>
            **Onde encontrar as melhores referências técnicas?**

            Existem diversas fontes de informação disponíveis para os profissionais de educação física, tanto em formato impresso quanto digital. Abaixo, você encontrará uma lista com alguns dos principais recursos, acompanhados de links para facilitar o seu acesso:

            ### **Bases de dados científicas**

            * **PubMed:** A principal base de dados de referências e resumos de artigos de revistas científicas sobre medicina e ciências da vida.
            * **SciELO:** Biblioteca Eletrônica em Ciências da Saúde, com acesso gratuito a artigos científicos de diversas áreas, incluindo a educação física.
            * **Google Scholar:** Um buscador acadêmico que permite encontrar artigos científicos, teses, livros e outras publicações relevantes.

            ### **Sociedades científicas e associações**

            * **Sociedade Brasileira de Educação Física e Esporte (SOBRAFE):** A principal sociedade científica da área no Brasil, com publicações, eventos e diretrizes para a prática profissional.
            * **American College of Sports Medicine (ACSM):** Uma das mais importantes organizações internacionais na área de esportes e exercício físico, com diretrizes e guidelines atualizados.
            * **National Strength and Conditioning Association (NSCA):** Uma associação dedicada ao fortalecimento e condicionamento físico, com certificações e publicações relevantes.

        </reference>
    </reference>

    <about>
        <scope>
            Educação Física para treinamento de exercícios guiado por um personal trainer que se pauta por informações do usuário.
        </scope>

        <description>
            Regime de exercícios conforme requisitos {biotipo; quantidade de sessões por semana (uma sessão para cada dia); tipos de treino} determinados pelo usuário.
            <details>
                {
                    "biotipo":{
                        "ectomorfo": "Corpo mais magro, difícil ganhar peso e massa muscular.",
                        "mesomorfo": "Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.",
                        "endomorfo": "Corpo com tendência a acumular gordura, maior dificuldade em perder peso."
                    },

                    "quantidade de sessões por semana (uma sessão para cada dia)":{
                        "1 sessão": "Treino Full Body.",
                        "3 sessões": "Treino ABC.",
                        "5 sessões": "Treino ABCDE."
                    },

                    "tipos de treino":{
                        "funcional": "Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.",
                        "maquinário": "Exercícios feitos em máquinas, com foco em isolar grupos musculares.",
                        "peso livre": "Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente.",
                        "cardio": "Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.",
                        "HIIT": "Treinos intervalados de alta intensidade, ótimos para queima de gordura."
                    }
                }
            </details>
        </description>

        <role>
            Educador físico que está trabalhando como personal trainer para planejar um regime de exercícios conforme informado pela tag description
            <style>
                Formal
                Técnico 
                Objetivo 
            </style>
        </role>

        <goal>
            Determinar um regime de exercícios conforme informado pela tag description
                <info>
                    {
                        biotipo: endomorfo  
                        quantidade de sessões por semana (uma sessão para cada dia): 5
                        tipos de treino: [cardio] 
                    }
                </info> 
        </goal>
    </about>

</input>

## Respectivo output do OpenAI ChatGPT-4o
Aqui está o output gerado a partir do arquivo [prompt.xml](prompt.xml):

**Regime de exercícios físicos personalizado**

- **Biotipo:** Endomorfo  
  Corpo com tendência a acumular gordura, com maior dificuldade em perder peso.

- **Quantidade de sessões por semana:** 5 sessões  
  Regime de treino tipo **ABCDE**, com foco em diferentes grupos musculares a cada dia.

- **Tipos de treino:** Cardio  
  Foco em atividades cardiovasculares para promover a perda de gordura e melhorar a resistência física.

### Sugestão de regime de treino semanal:
1. **Dia 1 - Cardio de Alta Intensidade (HIIT):**  
   Treinos intervalados de alta intensidade, como sprints de 30 segundos seguidos por 1 minuto de caminhada, por 20-30 minutos.

2. **Dia 2 - Cardio em Esteira/Bicicleta:**  
   Sessão de 40-60 minutos de cardio moderado, como corrida leve ou bicicleta, mantendo a frequência cardíaca estável.

3. **Dia 3 - Cardio Funcional:**  
   Circuitos de exercícios funcionais que incluem movimentos como burpees, saltos e corridas estacionárias para manter a frequência cardíaca elevada.

4. **Dia 4 - Cardio de Longa Duração:**  
   Atividade cardiovascular contínua por 60 minutos, como caminhada rápida, natação ou pedalada.

5. **Dia 5 - Cardio de Baixa Intensidade:**  
   Atividade mais leve, como uma caminhada de 30-45 minutos para manter o corpo ativo e auxiliar na recuperação.

### Observações:
- **Intensidade ajustada conforme nível de aptidão física.**  
- **Foco na queima de gordura e melhora do condicionamento cardiovascular.**

## 2º prompt
faça o seguinte: adicione um adendo com informações mais detalhadas e explicativas para cada sessão
### Respectivo output ao 2º prompt
Aqui está o regime de exercícios atualizado, agora com explicações mais detalhadas para cada sessão:

---

**Regime de Exercícios Físicos Personalizado com Adendo Explicativo**

- **Biotipo:** Endomorfo  
  Corpo com tendência a acumular gordura e maior dificuldade em perder peso. Requer foco na queima de gordura por meio de treinos cardiovasculares e controle calórico.

- **Quantidade de sessões por semana:** 5 sessões  
  Regime de treino do tipo **ABCDE**, com ênfase em diferentes grupos musculares e tipos de exercícios a cada dia, permitindo recuperação adequada.

- **Tipos de treino:** Cardio  
  Treinamento cardiovascular intensivo para promover a queima de gordura e melhorar a resistência cardiovascular, com variação de intensidade e duração ao longo da semana.

### Regime semanal detalhado:

---

**Dia 1 - Cardio de Alta Intensidade (HIIT):**  
*Treino Intervalado de Alta Intensidade (HIIT)*  
- **Duração:** 20-30 minutos
- **Exemplo de treino:** Sprint (corrida em alta velocidade) de 30 segundos, seguido por 1 minuto de caminhada ou corrida leve. Repetir este ciclo por 20-30 minutos.
- **Objetivo:** O HIIT é eficaz na queima de gordura devido à alta intensidade dos esforços curtos seguidos de períodos de recuperação. Ele também melhora a capacidade cardiovascular e metabólica, acelerando o gasto calórico até após o término do treino (efeito EPOC - Consumo Excessivo de Oxigênio Pós-Exercício).
  
*Adendo Explicativo:* O HIIT pode ser adaptado para diferentes níveis de aptidão física. Para iniciantes, os períodos de descanso podem ser mais longos. Para atletas mais avançados, a intensidade do sprint deve ser maximizada. Este tipo de treino é muito eficiente em termos de tempo, sendo altamente recomendado para endomorfos devido à sua alta demanda energética.

---

**Dia 2 - Cardio Moderado (Esteira/Bicicleta):**  
*Sessão de cardio contínuo e moderado*  
- **Duração:** 40-60 minutos
- **Exemplo de treino:** Corrida leve na esteira ou pedalada contínua na bicicleta ergométrica, mantendo um ritmo moderado que permita conversação, mas com um certo nível de esforço.
- **Objetivo:** Promover a queima de calorias de forma consistente, sem sobrecarregar o corpo, ajudando a aumentar a resistência cardiovascular e a queima de gordura ao longo do tempo.

*Adendo Explicativo:* O cardio de intensidade moderada, quando realizado por períodos mais longos, utiliza predominantemente gordura como fonte de energia, ideal para indivíduos que buscam emagrecer. Manter uma frequência cardíaca de 60-70% da frequência cardíaca máxima é o ideal para maximizar a queima de gordura.

---

**Dia 3 - Cardio Funcional:**  
*Treino funcional com foco cardiovascular*  
- **Duração:** 30-45 minutos
- **Exemplo de treino:** Circuito de exercícios como burpees, saltos de agachamento, corridas estacionárias, montanhistas e corda. Realizar 4-5 circuitos com 10-15 repetições de cada exercício, descansando 1-2 minutos entre os circuitos.
- **Objetivo:** O treino funcional melhora a funcionalidade dos movimentos naturais do corpo enquanto mantém a frequência cardíaca elevada, promovendo a queima calórica e melhorando a coordenação motora e a força.

*Adendo Explicativo:* Esse tipo de treino trabalha múltiplos grupos musculares simultaneamente, o que aumenta a demanda energética do corpo. Além disso, por ser dinâmico e variar constantemente, é mais interessante e pode evitar a monotonia de treinos exclusivamente em máquinas.

---

**Dia 4 - Cardio de Longa Duração:**  
*Atividade cardiovascular contínua e de longa duração*  
- **Duração:** 60 minutos
- **Exemplo de treino:** Caminhada rápida, natação contínua ou pedalada ao ar livre, mantendo uma intensidade estável, porém desafiadora.
- **Objetivo:** Aumentar a resistência cardiovascular e promover a utilização de gorduras como principal fonte de energia durante o exercício, otimizando a queima calórica.

*Adendo Explicativo:* Para indivíduos endomorfos, treinos de longa duração são particularmente importantes, pois aumentam o gasto calórico diário. A caminhada rápida ou pedalada ao ar livre é uma excelente opção para evitar o desgaste psicológico causado por treinos repetitivos.

---

**Dia 5 - Cardio de Baixa Intensidade (Recuperação Ativa):**  
*Atividade de recuperação ativa*  
- **Duração:** 30-45 minutos
- **Exemplo de treino:** Caminhada leve ou alongamentos dinâmicos, como yoga ou pilates.
- **Objetivo:** Manter o corpo em movimento para estimular a recuperação muscular sem sobrecarregar o sistema cardiovascular ou os músculos. Esse tipo de atividade também ajuda a aliviar o estresse e promove a flexibilidade.

*Adendo Explicativo:* A recuperação ativa é crucial para evitar o desgaste excessivo do corpo e preparar o organismo para a próxima semana de treinos. Para endomorfos, manter a consistência na queima calórica é importante, por isso, mesmo em dias mais leves, atividades suaves ajudam a manter o metabolismo ativo.

---

### Considerações Finais:
- **Alimentação adequada:** Para maximizar a perda de gordura, deve-se seguir um plano alimentar equilibrado, com controle de calorias e aumento de proteínas, ajustado para o biotipo endomorfo.
- **Descanso e hidratação:** O descanso adequado entre as sessões é fundamental para evitar lesões, bem como a hidratação adequada para otimizar o desempenho e a recuperação.

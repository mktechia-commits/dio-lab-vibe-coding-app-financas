# 💸 App de Finanças Pessoais do Marcio Marques com Vibe Coding
PRD refinado com ChatGPT Web:

```markdown

# PRD — Aplicativo de Organização de Finanças Pessoais

**Nome provisório:** Finanças em Conversa  
**Versão:** 1.3  
**Objetivo:** Definir os requisitos de um aplicativo de organização financeira pessoal com interação por linguagem natural, recomendações de economia e princípios de Design Universal.

## 1. Visão do Produto

Desenvolver um aplicativo de organização de finanças pessoais que permita aos usuários registrar receitas e despesas por meio de conversas em linguagem natural, acompanhar sua situação financeira, estabelecer metas e receber orientações para economizar dinheiro.

Quando houver sobra de dinheiro no mês, o aplicativo deverá apresentar três opções de investimento para fins educativos, considerando o perfil, os objetivos e as necessidades informadas pelo usuário.

O produto deverá priorizar a simplicidade, a clareza, a segurança e o Design Universal, proporcionando uma boa experiência para o maior número possível de pessoas, inclusive iniciantes em organização financeira e usuários com diferentes necessidades de acessibilidade.

## 2. Problema a Ser Resolvido

Muitas pessoas têm dificuldade para organizar suas finanças porque os aplicativos existentes podem exigir preenchimento manual excessivo, apresentar informações complexas ou oferecer pouca personalização.

O produto pretende reduzir essas barreiras por meio de uma experiência conversacional, permitindo que o usuário registre suas movimentações financeiras com frases simples, como:

- "Gastei R$ 45 no supermercado."
- "Recebi R$ 3.000 de salário."
- "Quero economizar R$ 500 por mês."
- "Quanto ainda posso gastar este mês?"

O aplicativo também deverá ajudar o usuário a identificar oportunidades de economia e compreender alternativas para utilizar melhor o dinheiro que sobra.

## 3. Público-Alvo

O aplicativo será destinado principalmente a:

- Pessoas que desejam começar a organizar suas finanças pessoais.
- Usuários que não têm familiaridade com planilhas ou aplicativos financeiros complexos.
- Pessoas que desejam controlar receitas, despesas e metas de economia.
- Usuários com diferentes níveis de familiaridade tecnológica.
- Pessoas com diferentes necessidades de acessibilidade, incluindo usuários que utilizam teclado, leitores de tela ou ampliação de texto.

## 4. Proposta de Valor

Permitir que qualquer pessoa organize suas finanças de maneira simples, conversando com um assistente financeiro virtual, sem depender de planilhas complexas ou formulários extensos.

O aplicativo deverá transformar informações financeiras em orientações claras, práticas e personalizadas, incentivando hábitos financeiros mais conscientes.

## 5. Princípio Central: Design Universal

O Design Universal deverá ser considerado desde o início do desenvolvimento, e não apenas como uma melhoria posterior.

O objetivo é criar uma experiência que possa ser utilizada pelo maior número possível de pessoas, independentemente de idade, familiaridade tecnológica, limitações funcionais ou contexto de uso.

### 5.1. Diretrizes de Design Universal

O produto deverá considerar os seguintes princípios:

1. Uso equitativo: disponibilizar funcionalidades úteis para pessoas com diferentes capacidades e necessidades.
2. Flexibilidade de uso: oferecer formas alternativas de interação sempre que possível, como registrar uma despesa por conversa ou por um formulário simples.
3. Uso simples e intuitivo: organizar telas e ações de maneira previsível, com linguagem clara e sem termos financeiros desnecessariamente complexos.
4. Informação perceptível: apresentar informações de forma compreensível, considerando diferenças visuais, auditivas e cognitivas.
5. Tolerância a erros: permitir corrigir ou cancelar ações, confirmar operações importantes e apresentar mensagens de erro claras.
6. Baixo esforço físico: reduzir cliques desnecessários, evitar interações repetitivas e facilitar a conclusão das tarefas.
7. Espaço adequado para interação: garantir que botões e controles sejam fáceis de localizar e utilizar, inclusive em dispositivos móveis.

### 5.2. Requisitos de Acessibilidade

Utilizar as Diretrizes de Acessibilidade para Conteúdo Web (WCAG) 2.2, nível AA, como referência de implementação e avaliação.

O aplicativo deverá:

- Apresentar contraste adequado entre texto e fundo.
- Permitir navegação pelas funcionalidades principais usando apenas o teclado.
- Exibir indicadores visíveis de foco durante a navegação por teclado.
- Utilizar rótulos claros em campos, botões e controles.
- Ser compatível, sempre que possível, com leitores de tela e tecnologias assistivas.
- Não depender exclusivamente de cores para transmitir informações.
- Disponibilizar alternativas textuais para gráficos e visualizações financeiras.
- Permitir ampliação do texto sem perda significativa de conteúdo ou funcionalidade.
- Utilizar linguagem simples, objetiva e consistente.
- Apresentar mensagens de erro que expliquem o problema e indiquem como corrigi-lo.
- Respeitar as preferências de acessibilidade do sistema operacional e do navegador quando aplicável.
- Utilizar áreas de interação confortáveis para toque em dispositivos móveis, buscando dimensões de aproximadamente 44 por 44 pixels CSS quando viável.

Como referência técnica, o contraste mínimo deverá ser de 4,5:1 para texto comum e 3:1 para texto grande, conforme os critérios aplicáveis da WCAG 2.2 nível AA.

### 5.3. Critérios de Qualidade do Design Universal

Uma funcionalidade não deverá ser considerada concluída apenas porque funciona visualmente.

Antes de sua aprovação, deverá ser avaliado se:

- A finalidade da funcionalidade é compreensível.
- A tarefa pode ser concluída sem instruções complexas.
- Os controles são identificáveis e utilizáveis.
- Os erros podem ser compreendidos e corrigidos.
- A experiência funciona em diferentes tamanhos de tela.
- Há alternativas acessíveis para informações visuais.
- A funcionalidade foi testada com diferentes formas de interação, quando aplicável.

A adoção dessas diretrizes deverá ser acompanhada de testes. Não declarar conformidade integral com a WCAG sem uma avaliação adequada.

## 6. Funcionalidades Principais

### F1. Registro Financeiro por Conversa

Permitir que o usuário registre receitas e despesas por meio de linguagem natural.

Exemplos:

- "Gastei R$ 30 com transporte."
- "Paguei R$ 120 na conta de luz."
- "Recebi R$ 800 de um trabalho extra."

O assistente deverá identificar, quando possível:

- Valor.
- Tipo de movimentação: receita ou despesa.
- Categoria.
- Data.
- Descrição.

Quando houver informações ausentes ou ambíguas, deverá fazer perguntas curtas para esclarecer os dados antes de salvar a movimentação.

O usuário deverá conseguir revisar, editar ou excluir os registros.

### F2. Classificação Automática de Transações

Classificar automaticamente as movimentações em categorias como:

- Alimentação.
- Moradia.
- Transporte.
- Saúde.
- Educação.
- Lazer.
- Compras.
- Salário.
- Outras receitas.
- Outros gastos.

O usuário deverá poder corrigir a categoria sugerida.

Os cálculos financeiros deverão ser realizados por regras determinísticas, e não depender exclusivamente de respostas geradas pela inteligência artificial.

### F3. Painel Financeiro

Apresentar um resumo simples da situação financeira do usuário, incluindo:

- Total de receitas no período.
- Total de despesas no período.
- Saldo atual calculado a partir dos registros.
- Gastos por categoria.
- Evolução financeira ao longo do tempo.
- Progresso das metas de economia.

Os gráficos deverão ser simples e acompanhados de informações textuais equivalentes.

Os dados exibidos deverão corresponder aos registros armazenados, com indicação clara do período analisado.

### F4. Metas Financeiras

Permitir que o usuário crie e acompanhe metas financeiras.

Exemplos:

- Economizar R$ 1.000 para uma viagem.
- Guardar R$ 300 por mês.
- Criar uma reserva financeira.

Cada meta deverá permitir informar:

- Nome.
- Valor desejado.
- Valor já acumulado, quando conhecido.
- Prazo, se houver.
- Progresso.

O aplicativo deverá mostrar o progresso de forma compreensível e permitir que o usuário edite ou exclua metas.

### F5. Agente Financeiro

Disponibilizar um assistente que analise os registros e apresente sugestões práticas de economia.

Exemplos:

- Identificar categorias com aumento de gastos.
- Sugerir limites de despesas.
- Ajudar o usuário a estabelecer metas realistas.
- Apontar possíveis oportunidades de economia.
- Explicar conceitos financeiros básicos.

As recomendações deverão ser transparentes, respeitosas e baseadas nos dados disponíveis.

O aplicativo não deverá presumir informações que o usuário não forneceu nem apresentar estimativas como se fossem valores confirmados.

### F6. Comparador Educativo de Investimentos

Quando os dados disponíveis indicarem uma possível sobra financeira, o aplicativo deverá avaliar se há informações suficientes para apresentar três alternativas de investimento.

O recurso deverá:

- Explicar as alternativas em linguagem simples.
- Apresentar riscos, liquidez, custos e condições relevantes.
- Considerar os objetivos e o horizonte de tempo informados pelo usuário.
- Diferenciar informações confirmadas de estimativas.
- Utilizar informações atuais e verificáveis sobre os produtos apresentados.
- Explicar que rentabilidade passada não garante resultados futuros.
- Incentivar a avaliação da reserva de emergência e das despesas previstas antes de investir.

O recurso deverá ser educativo e não deverá prometer rendimentos, executar investimentos, movimentar dinheiro ou apresentar uma alternativa como garantia de retorno.

Se não houver dados suficientes para calcular a sobra ou contextualizar as alternativas, o aplicativo deverá solicitar informações adicionais ou explicar por que ainda não pode apresentar uma comparação confiável.

## 7. Telas Principais

### 7.1. Painel Inicial

Deverá apresentar:

- Resumo das receitas, despesas e saldo.
- Metas financeiras em andamento.
- Principais categorias de gastos.
- Acesso direto à conversa com o assistente.
- Recomendações relevantes, quando existirem.

### 7.2. Conversa com o Assistente

Deverá permitir:

- Registrar movimentações financeiras.
- Fazer perguntas sobre as próprias finanças.
- Solicitar resumos e explicações.
- Criar e consultar metas.
- Receber sugestões de economia.

A interface deverá apresentar mensagens claras de carregamento, sucesso, erro e confirmação.

### 7.3. Histórico de Movimentações

Deverá apresentar uma lista de receitas e despesas com:

- Descrição.
- Valor.
- Categoria.
- Data.
- Tipo de movimentação.

Deverá permitir filtrar, editar e excluir registros.

### 7.4. Metas Financeiras

Deverá permitir criar, visualizar, editar e acompanhar metas, apresentando valores e progresso de maneira acessível.

### 7.5. Investimentos

Deverá apresentar as três alternativas disponíveis, quando houver informações suficientes, com comparação de riscos, liquidez, custos e características relevantes.

A interface deverá deixar claro que se trata de conteúdo educativo, não de uma promessa de rendimento nem de uma ordem de investimento.

## 8. Diretrizes Visuais e de Conteúdo

A interface deverá ser moderna, organizada, responsiva e simples de compreender.

Diretrizes:

- Utilizar português brasileiro.
- Preferir frases curtas e linguagem acessível.
- Manter hierarquia visual consistente.
- Evitar excesso de informações em uma única tela.
- Utilizar tipografia legível e espaçamento adequado.
- Garantir que os elementos funcionem em computadores, tablets e celulares.
- Não utilizar apenas cores para indicar estados, alertas ou resultados.
- Fornecer descrições textuais para gráficos e indicadores visuais.
- Disponibilizar estados vazios com orientações para começar.
- Informar quando os dados ainda não foram carregados ou estão incompletos.
- Evitar animações ou efeitos que prejudiquem a compreensão ou a acessibilidade.
- Manter consistência nos botões, formulários, mensagens e padrões de navegação.

## 9. Requisitos Técnicos, Privacidade e Segurança

O desenvolvimento deverá considerar:

- Autenticação segura dos usuários.
- Separação dos dados de cada usuário.
- Proteção das informações financeiras armazenadas.
- Validação dos dados recebidos e enviados.
- Tratamento adequado de erros.
- Uso seguro de serviços de inteligência artificial.
- Não exposição de chaves de API ou segredos no código do cliente.
- Coleta apenas dos dados necessários ao funcionamento do produto.
- Transparência sobre o uso dos dados.
- Recursos para editar e excluir informações.
- Observância das obrigações aplicáveis da Lei Geral de Proteção de Dados (LGPD).

Na primeira versão, não será necessário conectar contas bancárias, executar pagamentos ou realizar transferências.

O aplicativo deverá diferenciar claramente dados reais registrados pelo usuário, dados de demonstração e estimativas.

## 10. Critérios de Aceitação

A primeira versão será considerada funcional quando:

1. O usuário conseguir registrar uma receita ou despesa por conversa.
2. O aplicativo identificar os principais dados da movimentação ou solicitar esclarecimentos quando necessário.
3. O usuário conseguir revisar, editar e excluir movimentações.
4. As receitas, despesas e o saldo forem calculados corretamente a partir dos registros.
5. O usuário conseguir criar e acompanhar metas financeiras.
6. O assistente apresentar sugestões de economia baseadas nas informações disponíveis.
7. O comparador apresentar três alternativas educativas quando houver dados suficientes e informações verificáveis.
8. O aplicativo funcionar em telas de diferentes tamanhos.
9. As principais tarefas puderem ser realizadas por navegação com teclado.
10. Campos, botões e controles tiverem nomes ou rótulos compreensíveis.
11. Os indicadores de foco forem visíveis durante a navegação por teclado.
12. Informações importantes não dependerem exclusivamente de cores ou gráficos.
13. Mensagens de erro explicarem o problema e orientarem sua correção.
14. O texto puder ser ampliado sem perda significativa de conteúdo ou funcionalidade.
15. Os dados financeiros de usuários diferentes permanecerem separados e protegidos.
16. A experiência tiver sido testada com usuários de diferentes níveis de familiaridade tecnológica e, quando possível, com diferentes necessidades de acessibilidade.

## 11. Plano Inicial de Validação

A validação deverá ocorrer em etapas.

### Etapa 1: Teste de Usabilidade

Convidar pessoas que estejam começando a organizar suas finanças.

Solicitar que realizem tarefas como:

- Registrar uma despesa.
- Consultar o saldo do mês.
- Criar uma meta.
- Identificar a categoria com maior gasto.

Observar se conseguem concluir as tarefas sem ajuda e quais pontos causam dúvidas.

### Etapa 2: Teste de Acessibilidade

Verificar:

- Navegação por teclado.
- Contraste de cores.
- Ampliação de texto.
- Uso com leitor de tela.
- Clareza dos rótulos.
- Alternativas textuais para gráficos.
- Facilidade de corrigir erros.

Sempre que possível, incluir pessoas que utilizam tecnologias assistivas nos testes.

### Etapa 3: Teste de Compreensão Financeira

Verificar se os usuários conseguem compreender:

- O saldo apresentado.
- As categorias de despesas.
- O progresso das metas.
- As recomendações de economia.
- As diferenças entre as alternativas de investimento.

### Etapa 4: Melhorias

Priorizar os problemas que impedem a conclusão de tarefas, geram erros financeiros ou excluem usuários de determinadas funcionalidades.

Repetir os testes após as melhorias mais importantes.

## 12. Plano de Desenvolvimento do MVP

O desenvolvimento deverá ser dividido em etapas para facilitar o aprendizado e reduzir a complexidade.

### Fase 1: Interface Inicial

- Criar as telas principais.
- Implementar navegação responsiva.
- Utilizar dados fictícios claramente identificados.
- Definir os componentes visuais básicos.
- Verificar os requisitos iniciais de Design Universal.

### Fase 2: Movimentações e Cálculos

- Implementar cadastro de receitas e despesas.
- Criar categorias.
- Permitir edição e exclusão.
- Implementar armazenamento persistente.
- Calcular receitas, despesas e saldo.
- Implementar metas financeiras.

### Fase 3: Assistente Conversacional

- Integrar o serviço de inteligência artificial.
- Interpretar mensagens em linguagem natural.
- Solicitar esclarecimentos quando necessário.
- Confirmar os dados antes de salvar quando houver ambiguidade.
- Conectar as respostas aos registros reais do usuário.

### Fase 4: Recomendações e Investimentos

- Implementar sugestões de economia.
- Definir regras para identificar possíveis sobras financeiras.
- Implementar comparação educativa de investimentos.
- Verificar a atualidade e a confiabilidade das informações apresentadas.
- Incluir avisos sobre riscos e limitações.

### Fase 5: Validação e Refinamento

- Realizar testes funcionais.
- Avaliar a acessibilidade.
- Testar a experiência com usuários iniciantes.
- Corrigir problemas prioritários.
- Revisar a privacidade e a segurança.

## 13. Resultado Esperado

Entregar um MVP que permita a uma pessoa organizar suas finanças pessoais por meio de conversas simples, acompanhar receitas e despesas, definir metas, receber orientações de economia e compreender alternativas educativas de investimento quando houver informações suficientes.

O produto deverá priorizar a facilidade de uso, a confiabilidade dos cálculos, a proteção dos dados e o Design Universal, buscando oferecer uma experiência acessível ao maior número possível de pessoas.

O sucesso inicial será avaliado pela capacidade dos usuários de concluir tarefas financeiras básicas com autonomia, compreender as informações apresentadas e utilizar o aplicativo com confiança.
```
Interações com o Lovable:
> Crie um App de Finanças Pessoais com base no seguinte PRD (Product Requirements Document): {PRD}
> Resultado final no Lovable https://mapa-das-financas.lovable.app/
> <img width="1184" height="917" alt="image" src="https://github.com/user-attachments/assets/29f0b556-230f-4e3f-8ee8-5b81972dbd57" />

  
# Finanças em Conversa

## Sobre o projeto

O **Finanças em Conversa** é um aplicativo de organização de finanças pessoais que tem como objetivo ajudar os usuários a controlar receitas e despesas, acompanhar metas financeiras e desenvolver hábitos mais conscientes em relação ao dinheiro.

A proposta é simplificar a gestão financeira por meio de uma interface intuitiva e de um assistente que permite interagir utilizando linguagem natural, reduzindo a necessidade de preenchimento manual de formulários e planilhas complexas.

O projeto está sendo desenvolvido como um MVP (Produto Mínimo Viável), com foco em praticidade, acessibilidade e facilidade de uso, especialmente para pessoas que estão começando a organizar suas finanças.

## Objetivos do projeto

- Simplificar o registro e o acompanhamento de receitas e despesas.
- Permitir a interação com as finanças por meio de linguagem natural.
- Automatizar a classificação das movimentações financeiras.
- Facilitar a criação e o acompanhamento de metas financeiras.
- Oferecer sugestões personalizadas para economizar dinheiro.
- Apresentar alternativas de investimento com finalidade educativa.
- Aplicar princípios de Design Universal para ampliar a acessibilidade e a facilidade de uso.

## Funcionalidades

### 1. Painel financeiro

Apresenta uma visão geral da situação financeira do usuário.

- **Receitas:** total recebido no período.
- **Despesas:** total gasto no período.
- **Saldo do mês:** diferença entre receitas e despesas registradas.
- **Gastos por categoria:** distribuição das despesas por categoria.
- **Evolução financeira:** gráfico com o histórico de receitas e despesas dos últimos seis meses.
- **Metas em andamento:** resumo do progresso das metas financeiras.

O painel também oferece atalhos para acessar o assistente e registrar movimentações.

### 2. Assistente financeiro conversacional

Permite que o usuário interaja com o aplicativo por meio de linguagem natural.

Exemplos de comandos:

- "Gastei R$ 45 no supermercado."
- "Recebi R$ 3.000 de salário."
- "Quanto gastei com alimentação este mês?"
- "Como posso economizar R$ 200 por mês?"

O assistente deverá interpretar as mensagens, identificar as informações financeiras, classificar movimentações e responder às dúvidas do usuário. Quando necessário, deverá solicitar esclarecimentos antes de registrar informações ambíguas.

### 3. Registro e histórico de movimentações

Permite organizar as entradas e saídas de dinheiro.

Funcionalidades previstas:

- Registrar receitas e despesas.
- Informar valor, descrição, data e categoria.
- Classificar movimentações automaticamente.
- Consultar o histórico financeiro.
- Filtrar movimentações por período ou categoria.
- Editar e excluir registros.

Os valores registrados deverão alimentar os cálculos e as visualizações do painel financeiro.

### 4. Metas financeiras

Permite definir objetivos financeiros e acompanhar seu progresso.

Exemplos:

- Economizar R$ 1.000 para uma viagem.
- Guardar R$ 300 por mês.
- Construir uma reserva de emergência.

Funcionalidades previstas:

- Criar metas financeiras.
- Definir valores desejados e prazos.
- Acompanhar o progresso.
- Consultar metas em andamento.
- Editar e excluir metas.

### 5. Agente de economia

Oferece sugestões práticas para ajudar o usuário a melhorar sua organização financeira.

Funcionalidades previstas:

- Identificar categorias com gastos elevados.
- Apontar aumentos nas despesas.
- Sugerir oportunidades de economia.
- Ajudar a definir metas realistas.
- Explicar conceitos básicos de educação financeira.

As recomendações deverão considerar os dados disponíveis e evitar conclusões sem fundamento nas informações do usuário.

### 6. Comparador educativo de investimentos

Quando houver uma possível sobra financeira e informações suficientes, o aplicativo deverá apresentar três alternativas de investimento para fins educativos.

As comparações deverão considerar:

- Características de cada alternativa.
- Riscos envolvidos.
- Liquidez.
- Custos e condições relevantes.
- Compatibilidade com os objetivos e o horizonte de tempo do usuário.

O recurso não deverá prometer rendimentos nem executar investimentos. As informações deverão ser atuais, verificáveis e apresentadas em linguagem acessível.

### 7. Perfil do usuário

Área destinada ao gerenciamento das informações e preferências da conta.

Como evolução prevista, poderá permitir a atualização de dados pessoais e de preferências necessárias para personalizar a experiência.

### 8. Design Universal e acessibilidade

O projeto considera o Design Universal como princípio transversal de desenvolvimento, buscando oferecer uma boa experiência ao maior número possível de pessoas.

Diretrizes previstas:

- Interface simples, consistente e responsiva.
- Textos legíveis e contraste adequado.
- Navegação por teclado.
- Compatibilidade com leitores de tela.
- Rótulos claros para campos e botões.
- Alternativas textuais para gráficos.
- Mensagens de erro compreensíveis.
- Possibilidade de corrigir ações e movimentações.
- Consideração das diretrizes WCAG 2.2, nível AA, como referência de acessibilidade.

A implementação desses requisitos deverá ser validada por meio de testes de usabilidade e acessibilidade.

## Tecnologias e desenvolvimento

O projeto está sendo desenvolvido com apoio do **Lovable**, utilizando uma abordagem de Vibe Coding, na qual a construção da aplicação ocorre de forma iterativa com auxílio de instruções em linguagem natural e ferramentas de inteligência artificial.

As tecnologias específicas, integrações e serviços utilizados deverão ser documentados conforme forem definidos e implementados no projeto.

## Status do projeto

O projeto encontra-se em fase de desenvolvimento do MVP.

A interface inicial apresenta:

- Painel financeiro.
- Indicadores de receitas, despesas e saldo.
- Área de gastos por categoria.
- Gráfico de evolução financeira.
- Seção de metas em andamento.
- Navegação para assistente, movimentações, metas, investimentos e perfil.

A presença de um elemento na interface não significa necessariamente que sua funcionalidade esteja totalmente implementada. Os fluxos, cálculos, integrações e recursos de acessibilidade deverão ser testados conforme o desenvolvimento avançar.

## Próximas etapas

1. Validar a navegação e a responsividade da interface.
2. Implementar o registro, a edição e a exclusão de movimentações.
3. Garantir a persistência dos dados.
4. Implementar os cálculos de receitas, despesas e saldo.
5. Conectar os registros ao painel e aos gráficos.
6. Implementar a criação e o acompanhamento de metas.
7. Integrar o assistente conversacional.
8. Desenvolver as recomendações de economia.
9. Implementar o comparador educativo de investimentos.
10. Realizar testes funcionais, de usabilidade, acessibilidade, privacidade e segurança.

## Princípios do projeto

- **Simplicidade:** reduzir a complexidade da organização financeira.
- **Acessibilidade:** facilitar o uso por pessoas com diferentes necessidades.
- **Design Universal:** considerar a diversidade de usuários desde o início.
- **Transparência:** apresentar informações financeiras de forma clara.
- **Segurança:** proteger os dados e a privacidade dos usuários.
- **Educação financeira:** ajudar os usuários a compreender suas finanças e tomar decisões mais conscientes.

## Objetivo do MVP

Entregar uma primeira versão funcional que permita registrar e consultar movimentações financeiras, acompanhar receitas e despesas, criar metas e visualizar a situação financeira de forma simples.

A partir dessa base, o projeto evoluirá para incluir o assistente conversacional, as recomendações personalizadas de economia e a comparação educativa de investimentos.

## Observação

Este projeto tem finalidade de aprendizado e desenvolvimento de produto. As funcionalidades descritas como previstas ou futuras não devem ser consideradas implementadas até que seu funcionamento seja confirmado por testes.  

** Reflexão **:
  - O que funcionou bem?
    O refinamento do PRD previamente feito no ChatGPT ajudou muito, pois os créditos do Lovable acabaram em apenas 3 interações.
     
  - O que não funcionou como o esperado?
    Esperava poder interagir mais vezes gratuitamente com o Lovable, mas as interações feitas já foram de grande valia para aprender mais sobre o Vibe Coding.
    
  - O que aprendeu sobre conversar com IAs?
    Aprendi que é basicamente igual a conversar com uma pessoa, quanto mais detalhes e clareza você conversa, melhor é a interação.


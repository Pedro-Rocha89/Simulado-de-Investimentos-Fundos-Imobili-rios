# Simulador de Investimentos em Fundos Imobiliarios

![image](https://github.com/user-attachments/assets/ea448f0b-e654-49a7-8a0f-a232cf3b23d7)



## Descrição do Projeto
O projeto consiste na criação de uma ferramenta simples em Excel para simular investimentos em fundos imobiliários. A planilha permite calcular o valor total investido, o patrimônio acumulado e os dividendos mensais, ajudando o usuário a entender melhor o impacto de seus investimentos ao longo do tempo. Este modelo pode ser usado como base para futuras expansões e personalizações, oferecendo uma solução prática e acessível para investidores iniciantes.


## 📑 Etapas
- `Criação da Logo`: 
A criação da logo foi feita pelo Gemini (IA da Google). Criei a minha própria logo com a finalidade de simular uma demanda real de um futuro cliente, ou seja, uma simulador personalizado.

- `Criação da tabela de inserção de dados`: 
Nessa etapa comecei a estilizar e a desenvolver a planilha que receberá os dados principais do usuário. Realizei tambem a formatação de cada campo dos dados.

![image](https://github.com/user-attachments/assets/461c93f4-42e6-41c3-990b-840ca3b87a6f)


- `Criação da tabela de projeção`:
Trata-se de uma tabela calculada que projeta os valores do montante do investimento ao final de uma quantidade de anos pré-determinada.

![image](https://github.com/user-attachments/assets/67d842f3-4f7e-40ae-a553-5948d949b2af)

- `Criação de tabelas consultivas`:
Nessa etapa foram criadas duas tabelas consultivas: uma para a consulta do tipo do fundo imobiliário e outra para o perfil de investidor.

![image](https://github.com/user-attachments/assets/15dd4860-5784-43af-ab62-74e437eedbea)

## 🖩 Fórmulas/Funções utilizadas 
- `Valor Futuro`: 
Para o cálculo do montante/patrimônio acumulado, foi utilizada a fórmula do **"Valor Futuro"(=VF)**. A fórmula é utilizada para investimento a juros compostos com aportes mensais. As entrada exigidas, nesta ordem, são: taxa, período* e aporte mensal.

**A tabela de inserção de dados pede o valor do período em anos e a função de valor futuro reconhece o dado como mês, por isso foi preciso aplicar o fator de multiplicação vezes 12(doze) para que o cálculo fosse correto.*
  
 


- `Proteção contra erros`: Caso nenhum nome seja inserido e o botão "Adicionar" seja apertado, a aplicação exibirá o erro "Por favor, digite um nome válido", impedindo que o programa rode sem os dados corretos.


- `Transparência`: Todos os nomes inseridos serão exibidos em uma lista visível na página da aplicação.
  

- `Sorteio`: Ao clicar no botão "Sortear amigo", um nome aleatório será sorteado e apresentado.
  

## Ferramentas e Aplicativos Utilizados

- ``Java``
- ``VS code``
- ``Trello``


## Desenvolvedores
[<img loading="lazy" src="https://avatars.githubusercontent.com/u/201495780?s=96&v=4" width=115><br><sub>Pedro Rocha</sub>](https://github.com/Pedro-Rocha89)

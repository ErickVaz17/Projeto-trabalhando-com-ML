# Modelo de Previsão 🖥️

Este README será utilizado para entrega do Projeto **TRABALHANDO COM MACHINE LEARNING** no **Azure ML**. Aqui foi solicitado para fazer um passo a passo de como criar um modelo de previsão com seus devidos pontos de extremidades configurados. Fui fazendo o modelo de previsão sobre vendas de bicicletas conforme o guia e as aulas e vou tentando fazer o passo a passo pelo meu entendimento de forma abragente. 

## Primeiro contato no espaço do Azure Machine Learning 😎

Caso você não tenha uma conta no [Azure](https://portal.azure.com), é necessário fazer o cadastro com as suas seguintes informações:

- E-mail
- Número do celular
- Cartão de crédito (Será debitado um valor irrisório e logo depois vai ter o reembolso desse valor, isso é so uma confirmação da Azure)

Após ter criado sua conta, você precisara criar um espaço de trabalho no portal do Azure, para o trabalho em específico você vai em **+Criar um recurso** e pesquise `machine learning` e crie um novo recurso do **Azure Machine Learning** com as configurações de sua preferência ou pode utilizar a documentação do próprio Azure como base. Você deverá ir na aba Launch Studio, após entrar na sua conta da microsoft poderá ir no Studio Machine Learning e encontrara seu espaço de trabalho recém-criado.

## Usando o Aprendizado de Máquina Automatizado 💾

Para criar o ML Automatizado será necessário configurar as seguintes opções conforme sua escolha, podendo também utilizar a documentação:

- Configurações básicas
- Tipo de tarefa e dados
- Configurações de tarefa
- Calcular 
Após finalizar essas configurações você pode enviar o trabalho normalmente. 

## Avaliar, Implantar e Testa o melhor modelo 👨‍💻

Conforme o trabalho for concluído, na aba Visão Geral poderá visualizar melhor o resumo do modelo criado, como o nome do modelo, que você vai reconhecer como Nome do Algoritmo e nele conseguira ver as métricas e selecionar gráficos. No modelo criado, você vai selecionar a opção de implantar web e eu aconselho a ler e utilizar como referência a documentação, pois eu achei uma parte complicada. Mas, depois que implantar, você espera de 5 - 10 minutos para a finalização da implantação e parte para os Endpoints (Pontos de extremidades) teste de sua preferência.

Foi indicado excluir o serviço criado, pois está em uma instância do Azure, afim de evitar descontos desnecessarios e acumulação no espaço do Azure.

## 📚Referências
Esse foi o material que eu usei como referência para fazer meu modelo de previsão e utilizei também para criar esse passo a passo. Gostaria de salientar a sempre olhar a documentação, pois, tem tudo sobre desde a criação até os testes de modelos.

- [Documentação Azure ML Automatizado](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html)
- [Explore os Serviços de IA do Azure](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/02-content-safety.html)
- [Aulas sobre Machine Learning da DIO](https://web.dio.me/lab/trabalhando-com-machine-learning-na-pratica-no-azure-ml/learning/eac95e19-bd90-4df9-a9aa-bfe6945eae89)

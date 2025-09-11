# Desafio AWS Step Functions - Hello World

## Objetivo do Desafio
Consolidar o aprendizado sobre **AWS Step Functions** criando e executando um workflow simples, integrando com funções Lambda e registrando o fluxo completo.

## O que foi feito
- Criação de uma **State Machine** simples ("Hello World").  
- Configuração de permissões no **IAM** para execução.  
- Execução do workflow e verificação do resultado de saída.  
- Registro de **prints e gráficos** de cada passo da execução.

## Resultados
- A execução retornou `"Hello World"`.  
- Todos os passos do fluxo foram documentados com prints.  
- Material pronto para estudo e referência futura.

## Tecnologias Utilizadas
- AWS Step Functions  
- AWS Lambda  
- AWS IAM  
- Java (teste local, se aplicável)  
- GitHub (versionamento e documentação)

## Como Executar
1. Acesse o **AWS Console → Step Functions**  
2. Selecione a máquina de estado `"Hello World"`  
3. Clique em **Iniciar Execução**  
4. Observe os detalhes de entrada e saída no console

5. ## Funcionalidades
- Recebe e valida pedidos
- Define caminhos diferentes para pedidos válidos e inválidos (Choice)
- Envia notificações para pedidos válidos
- Registra erros ou termina fluxo para pedidos inválidos
- Monitoramento via CloudWatch

- ## Aprendizado Pessoal
Durante este desafio, percebi como **automatizar processos pode economizar tempo** e evitar erros.  
Aprendi a organizar **states e transições** no Step Functions e a integrar com **Lambda** para executar a lógica real.  
Entendi o significado de termos técnicos como **Task, Choice, Parallel** e como aplicá-los na prática.  
Também identifiquei minhas dificuldades, como implementar **Choice com múltiplos critérios** e integrar Step Functions com **SQS**, e sei onde preciso focar para evoluir.  
Sentir essa prática me deu mais **confiança para criar pequenos projetos automatizados** usando Java e AWS.

## Imagens do 
- Todas as fotos coforme o pedido do desfio.
## Observações
Este projeto serve como material de estudo e documentação do workflow automatizado. Todos os prints estão na pasta `/images`.

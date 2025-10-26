#  Desafio AWS Step Functions - DIO

##  Descrição
Este repositório foi criado como parte do desafio da DIO sobre **AWS Step Functions**.  
O objetivo é aplicar e documentar o uso de workflows automatizados na AWS, integrando diferentes serviços e consolidando o aprendizado em ambientes práticos.

---

##  O que são AWS Step Functions?
As **Step Functions** permitem criar fluxos de trabalho (workflows) que coordenam vários serviços AWS, como Lambda, ECS, DynamoDB e SNS, por meio de **máquinas de estado visuais**.  
Elas facilitam a **orquestração de processos automatizados**, sem precisar escrever lógica de controle complexa no código.

---

##  Arquitetura do Projeto
- **Serviços utilizados:**
  - AWS Step Functions
  - AWS Lambda
  - Amazon S3
  - Amazon CloudWatch (para logs)

- **Fluxo resumido:**
  1. Um evento dispara a execução do workflow.
  2. O Step Functions coordena a execução das funções Lambda.
  3. Os resultados são armazenados no S3.
  4. Logs e status da execução são registrados no CloudWatch.


---

##  Demonstração
---
- Diagrama do workflow:  
  ![Workflow Step Functions](https://docs.aws.amazon.com/images/step-functions/latest/dg/images/step-functions-example.png)


---

##  Aprendizados e Insights
- Entendi a importância das Step Functions para **automatizar e coordenar processos** entre diferentes serviços AWS.
- Percebi que é possível **reduzir erros e simplificar integrações** ao usar máquinas de estado.
- Aprendi a usar o **AWS Console** e o **AWS CLI** para criar e monitorar execuções.
- A documentação oficial é essencial para explorar **padrões de workflow mais complexos**, como *Parallel* e *Map States*.

---

##  Recursos e Referências
- [Documentação oficial da AWS Step Functions](https://docs.aws.amazon.com/step-functions)
- [Curso da DIO - AWS Step Functions](https://web.dio.me/)
- [Exemplos oficiais da AWS](https://github.com/aws-samples)

---

##  Como Executar
1. Configure sua conta AWS e acesse o **AWS Step Functions Console**.
2. Crie uma nova **State Machine**.
3. Cole a definição do fluxo (`workflow-definition.json`).
4. Execute e monitore o resultado pelo painel.

---

##  Autor
**Alice Torres**  
Estudante de Ciência da Computação | Entusiasta em Cloud e Automação  
[LinkedIn](#) | [GitHub](#)

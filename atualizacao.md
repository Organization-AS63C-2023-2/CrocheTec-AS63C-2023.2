# Requisitos Funcionais

| ID   | Requisito NF                                                                                                 | Categoria/Tipo     |  Prioridade |  Requisitos Relacionados |
| ---- | ------------------------------------------------------------------------------------------------------------ | ------------------ | -------------- | ----------------------- |
| RNF01 | Os usuários devem ser capazes de utilizar todas as funcionalidades do sistema após 5 minutos de treinamento. |    Alta     |Usabilidade        |          RNF02          |
| RNF02 | Os usuários devem ser capazes de acessar a ajuda online de qualquer página do sistema.                       |    Alta     |Usabilidade        |          RNF01          |
| RNF03 | O sistema deverá processar 1000 requisições a cada segundo.                                                  |    Alta     |Eficiência         |          RNF04          |
| RNF04 | O sistema deve estar disponível 80% das vezes.                                                               |    Alta     |Confiabilidade     |          RNF03          |
| RNF05 | Se o sistema falhar, os dados dos trabalhos do usuário devem ser recuperados pelo sistema.                   |    Alta     |Confiabilidade     |          RNF04          |
| RNF06 | O sistema deve ser suportado no Windows, Linux e IOS.                                                        |    Média    |Portabilidade      |          RNF07          |
| RNF07 | O sistema deve abrir em todos os browsers possíveis.                                                         |    Média    |Portabilidade      |          RNF06          |
| RNF08 | Todos os trabalhos tem o mesmo layout de contagem de pontos.                                                 |    Alta     |Entrega            |          RNF09          |
| RNF09 | O sistema deve ser implementado tanto em flutter quanto em javascript.                                       |    Alta     |Entrega            |          RNF10          |
| RNF10 | O sistema deve ser desenvolvido usando conceitos de orientação a objeto.                                     |    Média    |Entrega            |          RNF09          |
| RNF11 | O sistema deve ser desenvolvido usando framework React.                                                      |    Média    |Entrega            |          RNF09          |
| RNF12 | O sistema deve possuir compatibilidade com outras ferramentas de crochê.                                     |    Baixa    |Interoperabilidade |          RNF02          |
| RNF13 | O sistema não deve revelar aos operadores nenhuma informação pessoal dos clientes.                           |    Alta     |Éticos             |          RNF14          |
| RNF14 | O sistema deverá armazenar as informações de acordo com a Lei nº 13.709.                                    |    Alta     |Legais             |          RNF13          |
| RNF15 | O sistema deve criptografar todas as comunicações externas, de acordo com a Lei nº 8.078/1990.                    |    Alta     |Legais             |          RNF14          |
| RNF16 | O acesso aos dados deve ser protegido.                                                                       |    Alta     |Legais             |          RNF14          |
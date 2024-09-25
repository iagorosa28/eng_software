# Conect Educa

> Status do projeto: Em andamento

> Esse projeto nos foi proposto no 5ºSemestre na disciplina de Engenharia de Software

> Escrevemos esse projeto juntos durante as aulas 

> Área de Domínio: Educação

> Projeto: Aplicativo de freelancer para professores particulares

### Tópicos
🔹[Informações](#page_facing_up-informações)

🔹[Funcionalidade](#mag_right-funcionalidade)

🔹[Tecnologias Utilizadas](#computer-tecnologias-utilizadas)

🔹[Desenvolvedores](#busts_in_silhouette-desenvolvedores)

## :page_facing_up: Informações
### Público Alvo
  Nesse aplicativo buscamos como público alvo todos os estudantes que querem aprender algo novo ou estejam com dificuldade em alguma matéria interagir com professores que buscam ter uma renda extra.
  
### Propósito
  Facilitar o contato entre professores que queiram dar aulas particulares com alunos que necessitam dessas aulas.
  
### Lucro
  Pensamos em uma taxa de ____ em cima da aula do professor. Por exemplo, o professor cobra 200 reais pela aula tirando a sua locomoção que será tratada direto com o aluno, o valor mostrado para contratar o serviço será de ____. 
  Intermediação entre aluno e professor.

## Processos de Négocios
1. Processo de cadastro/login de alunos e professores
2. Processo de busca de professores por alunos 
3. Processo de comunicação entre alunos e professores
4. Processo de monitoramento de aula 
5. Processo de pagamento de serviço
6. Processo de avaliação

## Modelagem de Processos
![Imagem do WhatsApp de 2024-09-05 à(s) 11 50 09_69074da9](https://github.com/user-attachments/assets/3475a52f-870c-42c6-b7cb-b441e54f124b)

Para melhor definição acesse o link: https://drive.google.com/file/d/1-HmNsTpe2Uj7nPGJ2esX0hL_f1fhycfJ/view?usp=sharing

## Detalhe as tarefas dos processos de negócio - Em Formato De Texto

### Processo de Cadastro/Login de Alunos e Professores:
•	Os indivíduos se cadastram na plataforma como alunos ou professores.

•	A plataforma valida os dados fornecidos e, em seguida, envia uma ativação de login para os usuários.

•	Com a ativação concluída, os indivíduos obtêm permissão para acessar a plataforma utilizando suas credenciais.

### Processo de Busca de Professores pelos Alunos:
•	Professores cadastrados ativam suas contas, tornando-se visíveis na lista de professores disponíveis.

•	A plataforma exibe para os alunos uma lista atualizada de professores ativos.

•	Utilizando um sistema de filtragem, os alunos podem buscar o professor ideal com base em critérios como matéria, disponibilidade de horários, tipo de aula, entre outros.

### Processo de Comunicação entre Alunos e Professores:
•	Após a seleção de um professor, a plataforma disponibiliza um sistema de comunicação entre ambos para o planejamento das aulas.

•	Com o planejamento concluído, a plataforma agenda a aula.

### Processo de Monitoramento de Aula:
•	A plataforma oferece um sistema de acompanhamento que monitora o andamento das aulas, seja presencial ou online.

•	O professor ministra a aula no horário combinado com o aluno.

•	Ao término da aula, tanto o aluno quanto o professor confirmam a conclusão da mesma. No caso de aulas online, o encerramento pode ser registrado automaticamente.

### Processo de Pagamento pelo Serviço:
•	Após a conclusão da aula, a plataforma fornece um sistema para gerenciamento e realização do pagamento.

•	O aluno escolhe o método de pagamento preferido e, uma vez confirmado, a plataforma registra a transação. Caso o pagamento seja feito em espécie, tanto o aluno quanto o professor devem confirmar o recebimento na plataforma.

### Processo de Avaliação:
•	Ao final de todo o processo, a plataforma libera um sistema de avaliação para que alunos e professores possam avaliar mutuamente a experiência.

## Detalhe as tarefas dos processos de negócio - Em Formato De Tabela

### Tarefas realizadas pelo Aluno 

| Nome da tarefa:         | Cadastro de Aluno                                                             |
| :-----------------------| :-----------------------------------------------------------------------------|
| Dados de entrada:       | Dados do aluno                                                                |
| Detalhamento da tarefa: | - O aluno cadastra-se na plataforma<br>- Espera a plataforma validar os dados |
| **Dados de saída:**     | **Mensagem de espera**                                                        |

| Nome da tarefa:         | Login de Aluno                                                                                |
| :-----------------------| :---------------------------------------------------------------------------------------------|
| Dados de entrada:       | Dados do aluno                                                                                |
| Detalhamento da tarefa: | - O aluno espera a liberação do login pela plataforma<br>- O aluno faz o login na plataforma  |
| **Dados de saída:**     | **Acesso a plataforma**                                                                       |

| Nome da tarefa:         | Procura de Professor                                                                                  |
| :-----------------------| :-----------------------------------------------------------------------------------------------------|
| Dados de entrada:       | Palavras-chaves de procura                                                                            |
| Detalhamento da tarefa: | - O aluno digita palavras-chaves para encontrar um professor ideal através dos serviços da plataforma |
| **Dados de saída:**     | **Professor para a aula**                                                                             |

| Nome da tarefa:         | Professor Escolhido                                              |
| :-----------------------| :----------------------------------------------------------------|
| Dados de entrada:       | Mensagens pela plataforma                                        |
| Detalhamento da tarefa: | - Acontece a comunicação entre aluno e professor pela plataforma |
| **Dados de saída:**     | **Agendamento da aula**                                          |

| Nome da tarefa:         | Recebendo a aula                                                                                  |
| :-----------------------| :-------------------------------------------------------------------------------------------------|
| Dados de entrada:       | Conexão da aula                                                                                   |
| Detalhamento da tarefa: | - O aluno recebe a aula do professor ou pela plataforma ou presencial com o monitoramento da aula |
| **Dados de saída:**     | **Finalização da aula**                                                                           |

| Nome da tarefa:         | Pagamento                                                                                  |
| :-----------------------| :------------------------------------------------------------------------------------------|
| Dados de entrada:       | Dados de pagamento                                                                         |
| Detalhamento da tarefa: | - O aluno paga o professor pelo método que preferir, ou pela plataforma ou presencialmente |
| **Dados de saída:**     | **Baixa de pagamento pela  plataforma**                                                    |

| Nome da tarefa:         | Avaliação do professor                             |
| :-----------------------| :--------------------------------------------------|
| Dados de entrada:       | Resposta do aluno                                  |
| Detalhamento da tarefa: | - O aluno faz uma avaliação do professor e da aula |
| **Dados de saída:**     | **Avaliação enviada para a plataforma**            |

### Tarefas realizadas pelo Professor

| Nome da tarefa:         | Cadastro do Professor                                                             |
| :-----------------------| :---------------------------------------------------------------------------------|
| Dados de entrada:       | Dados do professor                                                                |
| Detalhamento da tarefa: | - O professor cadastra-se na plataforma<br>- Espera a plataforma validar os dados |
| **Dados de saída:**     | **Mensagem de espera**                                                            |

| Nome da tarefa:         | Login do Professor                                                                                   |
| :-----------------------| :----------------------------------------------------------------------------------------------------|
| Dados de entrada:       | Dados do professor                                                                                   |
| Detalhamento da tarefa: | - O professor espera a liberação do login pela plataforma<br>- O professor faz o login na plataforma |
| **Dados de saída:**     | **Acesso a plataforma**                                                                              |

| Nome da tarefa:         | Ativação de atividade                            |
| :-----------------------| :------------------------------------------------|
| Dados de entrada:       | Dados da aula                                    |
| Detalhamento da tarefa: | - Professor entra na lista de professores ativos |
| **Dados de saída:**     | **Espera por aluno**                             |

| Nome da tarefa:         | Comunicação da aula                                              |
| :-----------------------| :----------------------------------------------------------------|
| Dados de entrada:       | Mensagens do aluno pela plataforma                               |
| Detalhamento da tarefa: | - Acontece a comunicação entre aluno e professor pela plataforma |
| **Dados de saída:**     | **Agendamento da aula**                                          |

| Nome da tarefa:         | Dando a aula                                                                                    |
| :-----------------------| :-----------------------------------------------------------------------------------------------|
| Dados de entrada:       | Conexão da aula                                                                                 |
| Detalhamento da tarefa: | - O professor da aula para o aluno ou pela plataforma ou presencial com o monitoramento da aula |
| **Dados de saída:**     | **Finalização da aula**                                                                         |

| Nome da tarefa:         | Pagamento                                                                                                        |
| :-----------------------| :----------------------------------------------------------------------------------------------------------------|
| Dados de entrada:       | Dados de pagamento                                                                                               |
| Detalhamento da tarefa: | - O professor recebe o pagamento do aluno pelo método que o aluno peferir, ou pela plataforma ou presencialmente |
| **Dados de saída:**     | **Baixa de pagamento pela plataforma**                                                                           |

| Nome da tarefa:         | Avaliação do aluno                                 |
| :-----------------------| :--------------------------------------------------|
| Dados de entrada:       | Resposta do professor                              |
| Detalhamento da tarefa: | - O professor faz uma avaliação do aluno e da aula |
| **Dados de saída:**     | **Avaliação enviada para a plataforma**            |

### Tarefas realizadas pelo Sistema

| Nome da tarefa:         | Validação dos dados                                                                     |
| :-----------------------| :---------------------------------------------------------------------------------------|
| Dados de entrada:       | Dados do professor ou do aluno                                                          |
| Detalhamento da tarefa: | - Validar os dados de entrada dos cadastros, verificando a autenticidade e coisas afins |
| **Dados de saída:**     | **Notificação de espera para os cadastrados**                                           |

| Nome da tarefa:         | Liberação do login                                                     |
| :-----------------------| :----------------------------------------------------------------------|
| Dados de entrada:       | Conclusão da validação                                                 |
| Detalhamento da tarefa: | - Após a validação ser concluída e aceita, a plataforma libera o login |
| **Dados de saída:**     | **Notificação de liberação de login para os cadastrados**              |

| Nome da tarefa:         | Serviços de filtragem e listagem                                                                                                |
| :-----------------------| :-------------------------------------------------------------------------------------------------------------------------------|
| Dados de entrada:       | Dados de ativação do professor                                                                                                  |
| Detalhamento da tarefa: | - Cadastrando o professor na lista de ativos<br>- Liberando a lista de ativos para os alunos, oferencendo serviços de filtragem |
| **Dados de saída:**     | **Retornando o professor com a escolha do aluno e notificando-o**                                                               |

| Nome da tarefa:         | Comunicação e agendamento                                                  |
| :-----------------------| :--------------------------------------------------------------------------|
| Dados de entrada:       | Informações do aluno e do professor                                        |
| Detalhamento da tarefa: | - Oferecendo suporte para o planejamento das aulas entre aluno e professor |
| **Dados de saída:**     | **Agendamento da aula**                                                    |

| Nome da tarefa:         | Monitoramento da aula                                                                            |
| :-----------------------| :------------------------------------------------------------------------------------------------|
| Dados de entrada:       | Início da aula                                                                                   |
| Detalhamento da tarefa: | - Suporte de monitoramento de aula via presencial, ou, suporte de transmissão de aula via online |
| **Dados de saída:**     | **Fim da aula**                                                                                  |

| Nome da tarefa:         | Suporte de pagamento                                                                                                                |
| :-----------------------| :-----------------------------------------------------------------------------------------------------------------------------------|
| Dados de entrada:       | Dados de pagamento do aluno e de recebedor do professor                                                                             |
| Detalhamento da tarefa: | - A plataforma oferece suporte de pagamentos online (via app)<br>- A plataforma oferece monitoramento e baixas de pagamento via app |
| **Dados de saída:**     | **Conclusão da verificação de pagamento**                                                                                           |

| Nome da tarefa:         | Suporte de avaliações                                                                             |
| :-----------------------| :-------------------------------------------------------------------------------------------------|
| Dados de entrada:       | Avaliações do professor e do aluno                                                                |
| Detalhamento da tarefa: | - A plataforma oferece suporte de avaliações para que tanto o aluno quanto o professor se avaliem |
| **Dados de saída:**     | **Atualizações na área de avaliações dos cadastrados**                                            |

## Modelo de software escolhido

## Quem são os stakeholders?

## Desenvolvedores
| [<img loading="lazy" src="https://github.com/Mariah-Gomes/ProjetoCompMovel1/assets/141663285/e6827fd1-d8fe-4740-b6fc-fbbfccd05752" width=115><br><sub>Mariah Santos Gomes</sub>](https://github.com/Mariah-Gomes) | [<img loading="lazy" src="https://github.com/Mariah-Gomes/ProjetoCompMovel1/assets/141663285/66d7e656-b9e4-43b7-94fa-931b736df881" width=115><br><sub>Iago Rosa de Oliveira</sub>](https://github.com/iagorosa28) |
| :---: | :---: |


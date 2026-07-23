Esta pasta contém as evidências coletadas durante a execução dos casos de teste realizados no sistema BugBank (EBAC).

Evidência 1 – Cadastro realizado com sucesso


Aquivo: <img width="271" height="212" alt="image" src="https://github.com/user-attachments/assets/5fe6cd33-26bb-48fc-88eb-05b8874fc365" />

Descrição:

Evidência da execução do Caso de Teste CT-01, demonstrando que o cadastro foi realizado com sucesso e que o sistema exibiu corretamente o número da conta criada.

                                                                   //
Evidência 2 – Criação de conta com saldo


Aquivo: <img width="331" height="95" alt="image" src="https://github.com/user-attachments/assets/4893224d-5a22-4863-843e-1201d7de145e" />

Descrição:

Evidência da criação da conta com a opção "Criar conta com saldo" habilitada, resultando em um saldo inicial de R$ 1.000,00, conforme especificado nos requisitos.

                                                                   //

Evidência 3 – Campo Nome obrigatório

Arquivo: <img width="319" height="230" alt="image" src="https://github.com/user-attachments/assets/47cf68d8-3995-489e-a471-9684ee259918" />


Descrição:

Evidência da validação do campo Nome. O requisito espera a mensagem "Nome não pode ser vazio", e o resultado foi conforme especificado nos requisitos.

                                                                  //

Evidência 4 – Campo Email obrigatório

Arquivo: <img width="223" height="335" alt="image" src="https://github.com/user-attachments/assets/c56ace4a-571e-4983-bc0e-311e3194a17d" />


Descrição:

Evidência da validação do campo Email. Foi identificado que o sistema exibe a mensagem "É campo obrigatório" em vez da mensagem especificada no requisito.

                                                                   //

Evidência 5 – Campo Senha obrigatório

Arquivo: <img width="225" height="341" alt="image" src="https://github.com/user-attachments/assets/4fed9c97-2023-4666-86c6-60075cd935ed" />


Descrição:

Evidência da validação do campo Senha. O comportamento observado diverge do requisito, pois o sistema apresenta apenas a mensagem "É campo obrigatório".

                                                                  //
Evidência 6 – Campo Confirmar Senha obrigatório

Arquivo: <img width="231" height="356" alt="image" src="https://github.com/user-attachments/assets/613d0e4e-8b36-4368-ad55-d0d6c0be53c3" />


Descrição:

Evidência da validação do campo Confirmação de senha. O sistema exibe a mensagem "É campo obrigatório", diferente da mensagem esperada no requisito.
                                                                  
                                                                   //
Evidência 7 – Saldo disponível

Arquivo: <img width="273" height="99" alt="image" src="https://github.com/user-attachments/assets/197b6962-ff2b-442e-bbc5-a123f16ea251" />


Descrição:

Evidência da execução do Caso de Teste CT-03, demonstrando que o saldo disponível é exibido corretamente na tela de extrato.

                                                                   //
Evidência 8 – Histórico de transações

Arquivo: <img width="482" height="167" alt="image" src="https://github.com/user-attachments/assets/83a99f41-a2a6-472d-919f-e0f446dfc1a7" />


Descrição:

Evidência da tela de extrato apresentando as transações registradas na conta, incluindo data, tipo da movimentação e valores.   

                                                                   //
Evidência 9 – Limitação encontrada

Arquivo: <img width="61" height="44" alt="image" src="https://github.com/user-attachments/assets/c5570b7f-aaa8-429e-820c-75bf8e9f3efb" />


Descrição:

Durante a execução dos testes foi observado que o botão de alternância da opção "Criar conta com saldo" não responde ao clique no círculo branco. A funcionalidade só é acionada quando o clique é realizado diretamente sobre a barra do componente.



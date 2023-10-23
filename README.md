# Projeto-Final-M2
Esse é o projeto individual do segundo modulo do curso de analise de dados SENAC/RESILIA 2023

Este programa é uma ferramenta útil para empresas que desejam gerenciar candidatos em seu processo de seleção, permitindo o armazenamento e recuperação de informações com base em critérios específicos.


# Instruções de Instalação:
Certifique-se de ter o Python instalado no seu sistema. Baixe o Python aqui, se necessário.

Abra o terminal ou prompt de comando.

Instale as bibliotecas necessárias: numpy; selenium e pandas.




# Aqui está um resumo dos principais componentes do programa:

Classe Candidato: Primeiro, criamos uma classe chamada Candidato que tem atributos para armazenar informações sobre o candidato, como número do candidato, nota na entrevista, nota no teste teórico, nota no teste prático e nota na avaliação de soft skills.

Função armazenar_candidato: Essa função permite ao usuário armazenar informações sobre um novo candidato. O usuário insere o número do candidato e as notas nas diferentes etapas. Os dados são então organizados em um objeto Candidato e adicionados a uma lista chamada candidatos_list.

Função buscar_candidato: Esta função permite ao usuário buscar candidatos com base em critérios específicos. O usuário insere as notas mínimas que um candidato deve atender em cada etapa do processo seletivo. O programa então percorre a lista de candidatos e compara as notas. Os candidatos que atendem aos critérios são armazenados em uma lista chamada candidatos_compativeis. Se houver candidatos compatíveis, seus números são exibidos.

Menu Principal: O programa começa exibindo um menu principal com três opções: buscar candidato, armazenar candidato e sair. O usuário pode escolher uma das opções digitando o número correspondente. O programa entra em um loop que continua até o usuário escolher a opção "sair".

Feedback do Usuário: O programa fornece feedback para o usuário, incluindo mensagens de agradecimento ao armazenar um candidato com sucesso ou ao exibir a lista de candidatos compatíveis.

Validação de Entrada: O programa valida as entradas do usuário para garantir que sejam do tipo correto (por exemplo, números em vez de letras).

# Exemplo de Uso:

O usuário pode armazenar informações de candidatos digitando seus números e notas nas etapas.

O usuário pode buscar candidatos que atendam a critérios específicos, fornecendo as notas mínimas.

Os candidatos compatíveis são listados.

A atividade permite armazenar informações de candidatos e filtrar candidatos que atendem a critérios específicos, facilitando a seleção de candidatos compatíveis com as vagas. Certifique-se de testar o código com diferentes candidatos e critérios para avaliar seu funcionamento.

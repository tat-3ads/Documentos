# Documentos do Projeto TAT
## Disciplina de Tópicos Avançados em Tecnologias

## Autores
### Professor da Disciplina e coordenador do projeto
#### Douglas Cunha - douglas!fema.edu.br

## Alunos
| Nome                | Contato                              |
| ------------------- | ------------------------------------ |
| YANN                | a@a.com                              |
| Carla               | b@b.com                              |

# Descrição
O objetivo principal desta APP é facilitar o trabalho de um tutor ou professor, para criar grupos com pessoas / alunos para alguma atividade em grupo. 
A APP deve disponibilizar uma interface simplificada e ágil de calcular a quantidade de pessoas pela quantidade de grupos, auxiliando na montagem dos grupos. 

1. A APP deve ser estar disponível na WEB e controlada por um tutor ou professor, via celular, tablet ou computador.
2. Ela irá oferecer duas interfaces distintas (tutor ou professor) para criar os grupos e (usuários) que integram-se aos grupos. 
3. A interface do tutor / professor deve criar a quantidade de grupos com seus respectivos nomes e gerar o QRCode.
4. A interface das pessoas / alunos deve permitir que o mesmo selecione um grupo para participar.
5. Ao final o tutor / professor deve exportar os grupos com as pessoas / alunos num PDF.

# Proposta do Projeto Grupos X Pessoas
![Proposta do Projeto de Grupos X Pessoas](Imagens/figura1.jpg){ width="700" heigh="500" align=left }

## Diagrama de Entidade e Relacionamento
![Diagrama de Entidade e Relacionamento](Imagens/Grupos_X_Usuarios.png){ width="700" heigh="500" align=left }

## Frontend
Informações sobre o desenvolvimento...

## Regras para Backend
No momento de Criar o Grupo:
1. Gerar os grupos  usuarios cuja descrição se entre (A - Z), máximo de 30 grupos.
2. De acordo com a quantidade de usuários por grupo o mentor pode alterar a quantidade de grupos
3. Criar os registro no grupos_usuarios de acordo com a quantidade por grupo.

Cálculo da quantidade de pessoas por grupo 
Hipótese 1
43 alunos / 6 grupos
     43 / 6 = 7,16666  isto é 6 grupos com 7 usuáros e o ultimo grupo com 8 usuáros
26 alunos / 4 grupos
     26 / 4 = 6,5   isto é 4 grupos com 6 usuários e 2 grupos com 7 usuários

## Instalação
Informações sobre a abertura e instalação de ferramentas.

## Execução
Informações sobre a execução da APP.

## Automação
Informações sobre RPA 

## License
A GNU GPL v2 (Licença Pública Geral GNU versão 2) é uma das licenças de software livre mais usadas, um tipo de licença "copyleft forte" criada pela Free Software Foundation, que permite usar, modificar e distribuir software livremente, mas exige que qualquer trabalho derivado ou modificado também seja distribuído sob os mesmos termos da GPL v2, garantindo que o código permaneça aberto e livre, com regras sobre código-fonte e distribuição binária, protegendo as liberdades do usuário. 
Principais Características:
1. Copyleft Forte: Se você usa código GPL v2 em seu projeto, todo o seu projeto deve ser licenciado sob a GPL v2.
2. Liberdade: Garante aos usuários a liberdade de executar, estudar, modificar e redistribuir o software.
3. Código-Fonte: Exige que o código-fonte seja disponibilizado junto com o software (ou uma oferta para fornecê-lo).
4. Sem Garantia: O software é fornecido "como está", sem garantias de mercadoria ou adequação a um propósito específico.
5. Compatibilidade: A versão 2 da GPL (GPLv2) é a base, mas pode ser combinada com outras licenças, como a LGPL (Lesser General Public License), para bibliotecas. 

Para que Serve: É usada para proteger o software de se tornar proprietário, promovendo o compartilhamento de conhecimento e colaboração, sendo a licença de muitos projetos importantes de código aberto. 

Em Resumo: A GPLv2 garante que a essência do software livre (liberdade e código aberto) seja mantida em todas as versões e trabalhos derivados. 

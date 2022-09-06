# Simulador-MIPS (Pipeline)

Projeto em grupo desenvolvido para a disciplina Arquitetura de Computadores

A interface mostra, a cada estágio do pipeline, qual instrução está rodando em cada um dos 5 estágios do MIPS, o valor de todos os registradores e o conteúdo da memória principal. Existe também a opção de gerar automaticamente os stalls quando necessário, caso essa opção seja negada o usuário deverá implementar os stalls diretamente no código inserido no simulador.

O simulador possui suporte para as seguintes instruções: add, addi, and, beq, bne, j, jal, jr, lw, or, sll, srl, sw e sub

Código para teste rápido:

addi $a0, $zero, 10\n
addi $a1, $a0, 10\n
sw $a0, 20($a1)\n
sub $a2, $a1, $a0\n
lw $a3, 20($a1)\n

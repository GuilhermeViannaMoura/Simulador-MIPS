# Simulador-MIPS (Pipeline)

Projeto em grupo desenvolvido para a disciplina Arquitetura de Computadores

A interface mostra, a cada estágio do pipeline, qual instrução está rodando em cada um dos 5 estágios do MIPS, o valor de todos os registradores e o conteúdo da memória principal. Existe também a opção de gerar automaticamente os stalls quando necessário, caso essa opção seja negada o usuário deverá implementar os stalls diretamente no código inserido no simulador.

O simulador possui suporte para as seguintes instruções: add, addi, and, beq, bne, j, jal, jr, lw, or, sll, srl, sw e sub

No repositório tem um arquivo .asm que pode ser usado para testar o simulador

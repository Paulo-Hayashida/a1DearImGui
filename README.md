# a1DearImGui
- Atividade 1 da disciplica de Computação Gráfica, ministrada pelo professor Harlen pela Universidade Federal do ABC.

Nome : Paulo Henrique Eiji Hayashida RA: 11104714

## Atividade 1 - Calculadora

## Descrição

- Uma calculadora simples que suporta as operações se adição(+), subtração(-), multiplicação(**), divisão(/) e exponenciação(^) entre dois números de ponto flutuante. Além de resposta das raízes de equações de 1º grau(eq linear) e de 2º grau(eq quadratica).

- Na opção de equação linear também contém uma função adicional, que mostra a inclinação da reta a partir do valor do parametro a, selecionado através de um slider.

## Implementação

- As operações são selecionadas através de um combo box, que possui uma variável associada ao combo box, dependendo do valor dessa variavél, opções de input de valores são mostradas.

- Para as operações de adição, subtração, multiplicação, divisão e exponenciação, são mostradas dois campos, onde são colocadas os dois valores para se calcular a operação selecionada, e um botão calcular para mostrar o valor resultante da operação.

- Para a opção de equação linear, tem-se dois campos um para o valor de a e outro para o valor de b, dois valores da função linear no formato ax + b, além disso tem-se um check box para ativar uma função adicional, ao clicar função adicional, um slider aparece no UI bem como um texto que indica a inclicação da reta dado o valor do slider.

- Por fim, a opção de equação quadratica, apresenta três campos para inserção dos valores a, b e c, correspondente aos valores da função na forma ax^2 + bx + c, sendo que para valores de x reais tem-se os respesctivos valores de raizes, x1 e x2, do contrario o valor nan é apresentado se o valor é complexo.

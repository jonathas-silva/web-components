O Objetivo desse componente é criar um menu suspenso, inicialmente escondido, que aparece ao passar o mouse sobre o botão.

### Modo de uso

1. Inserir uma div container com id `#dropdown-container`, que envolverá o botão e o menu escondido.
2. No botão que estará sempre visível, no qual teremos o efeito hoover, inserir uma classe `.dropdown-btn`.
3. Inserir uma div container, que conterá os botões escondidos, com id `#dropdown-menu`.
4. Depois é só inserir os botões dentro da div container.

Obs: cada conjunto botão + menu escondido deverá ter estar num container `#dropdown-container` separado. O posicionamento dos botões, alinhamento, espaçamento etc ficará a cargo da aplicação cliente (dentro de uma tag nav, por exemplo).
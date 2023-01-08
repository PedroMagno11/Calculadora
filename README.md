# Calculadora

Calculadora feita apenas com HTML, CSS e Javascript.


![Caculadora](https://user-images.githubusercontent.com/105832975/211202054-ed5feaed-7dd3-4ea6-9317-600064e0b5ed.png)

OBS:
No arquivo 'script.js' , utilizei a função 'eval'. Essa função exige um certo cuidado para fazer a sua utilização , pois sem o devido tratamento ela pode corromper a segurança da sua aplicação, logo, não é recomendado o uso da função 'eval' em aplicações mais sensíveis.

MAAAAAASSS....

"Nunca use eval!

eval() é uma função perigosa, que executa o código passado com os privilégios do caller. Se você executar o eval() com uma sequência de caracteres que podem ser afetados por uma parte maliciosa, você pode acabar executando código malicioso na máquina do usuário com as permissões da sua página/extensão. Mais importante ainda, o código de terceiros pode ver o escopo em que eval() foi chamado, o que pode levar a possíveis ataques como Function não é suscetível.

eval() é geralmente mais lento do que as alternativas, uma vez que tem de invocar o interpretador JS, enquanto muitos outros construtores são otimizados por engines de JS modernos.

Os interpretadores modernos convertem javascript em código de máquina. Resumindo, o nome das variáveis será desmanchado. Portanto, o uso de eval forçará o navegador a fazer buscas caras para descobrir o endereço e seu valor no código de máquina. Além disso, novos valores podem ser introduzidos em eval como mudanças no tipo da variável, fazendo o navegador recalcular todo o código de máquina gerado anteriormente. Felizmente, existem alternativas mais seguras (e rápidas) ao eval() para usos comuns."
Fonte : https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/eval

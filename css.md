# CSS

{% embed url="https://drive.google.com/drive/folders/0Bwq1uYZkxJQeYm54X080WHQwZGc?resourcekey=0-nBQt-U_QAFBRz1EyxurTGg" %}

## todos elementos tem borda, basta definir espessura, tipo da borda e cor
## para definir o css para todos elementos, basta colocar o nome da tag, exemplo:
### img{...}
## quanto mais específico maior a prioridade - ex: id -> classe -> elemento
## id foi feito para destacar 1 elemento
## classe é para selecionar um conjunto de elementos
## sobrepor a prioridade - ex: 
### color: red !important;
#### o "!important" não é uma boa prática e só afeta a linha em que ele foi adicionado, no caso do exemplo, somente a cor, exemplo, se abaixo dessa linha eu adicionar "border", o "!important" de color não afetara o border da linha ou das linhas das classes ou IDs
##### Exemplo:
´´´
h1 {
    color: red !important;
    border: 3px solid mediumseagreen;
}

.texto {
    color: magenta;
    border: 5px solid red;
}

#um {
    color: blueviolet;
}
´´´
* dada matriz </br>
[ </br>6 2 1 = 7
</br> 2 4 1 = 7
</br>3 2 8 = 13
</br>]

    [ </br> a11     a12 a   13  = b1
</br> a21   a22   a23 = b2
</br>a31     a32    a33 = b3
</br>]

    O intuíto do método de Gauss é zerar os valores até chegar em uma possível solução para a matriz 
</br>
    Como primeiro passo é necessário encontrar o multiplicador de cada linha </br><b>EX: a21/a11 (multiplicador da segunda linha será chamado de m2)</b></br>
    <b>EX: a31/a11 (multiplicador da terceira linha será m3)</b></br>
    <b>CASO FOSSE UMA MATRIZ 4x4 EX: a41/a11 (multiplicador da quarta linha será m4)</b>
    <b>OBS o multiplicador vai prioritariamente o valor da diagonal principal </b></br>
    
    Após obter os multiplicadores, é necessário zerar o valor abaixo da diagonal principal

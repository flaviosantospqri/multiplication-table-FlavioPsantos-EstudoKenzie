<!DOCTYPE html>
<html>
    <head>
        <title>Multiplication Table</title>
    </head>

    <body>
        <h1>Multiplication Table</h1>
        <script>

           function tabuada(n) { // Substitua "nomeDaSuaFuncao" por um nome mais apropriado x[i] = [i]
                // escreve a coluna inicial
                let x = [];
                for (let i = 0; i <= n; i++) {
                    x[i] = [];
                    for(let j = 0; j <= n; j++){
                    x[i][j] = j*i;
                    }
                    
                }
                return x;
                
                // TODO: escrever dois loops aninhados para desenhar o array bidimencional e monstar o restante da tabela no console.
            }
            console.table(tabuada(10));
        </script>
    </body>
</html>


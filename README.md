# calcular-a-dor 

<!DOCTYPEhtml>
<html lang="pt">
    <cabeça>
        <meta charset="utf-8">
        <meta name="viewport" content="width-device-width, inicial-scale=1.0">
        <título>
            Projeto Calculadora
        </title>
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css" integridade="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2" crossorigin=" anônimo">
        <!-- formatação bootstrap para grade/visor da calculadora -->
        <!- ​​- copiado site https://getbootstrap.com/docs/4.5/getting-started/introduction/ -->
        <link rel="stylesheet" href="style.css">
        <!-- formatação css para bordas e espaçamento entre botões, arquivo interno relacionado-->
    </head>
    <corpo>
        <div class="container">
            <div class="linha">
                <div class="col-md-12">
                    <form action="#" name="Calculadora" class="main">
                        <input type="text" class="display form form-control" name="display"><br>
                        <!-- criando display principal para exibição de números e resultados -->
                        <input type="button" class="btn btn-primary" value="C" id="clear">
                        <!-- criando o botão C, atribuindo ação de limpeza display através de chamada por rotina pelo ID->
                        <input type="button" class="btn btn-primary ml-3" value="->" onclick="backSpace()">
                        <!-- criando botão operador ->, atribuindo ação de apagar o número através da rotina -->
                        <input type="button" class="btn btn-primary ml-3" value="%" onclick="document.calculator.display.value+='%'">
                        <!-- criando botão operador %, atribuindo valor de operação -->
                        
                        <input type="button" class="btn btn-primary ml-3" value="/" onclick="document.calculator.display.value+='/'"><br><br>
                        <!-- criando botão operador /, atribuindo valor de operação -->
                        
                        <input type="button" class="btn btn-primary" value="7" onclick="seven()">
                        <!-- criando botão número 7, atribuindo valor numérico -->
                        <input type="button" class="btn btn-primary ml-3" value="8" onclick="eight()">
                        <!-- criando botão número 8, atribuindo valor numérico -->
                        <input type="button" class="btn btn-primary ml-3" value="9" onclick="nine()">
                        <!-- criando botão número 9, atribuindo valor numérico -->
                        <input type="button" class="btn btn-primary ml-3" value="*" onclick="document.calculator.display.value+='*'"><br><br>
                        <!-- criando botão *, atribuindo valor de operação -->
                        <input type="button" class="btn btn-primary" value="4" onclick="four()">
                        <!-- criando botão número 4, atribuindo valor numérico -->
                        <input type="button" class="btn btn-primary ml-3" value="5" onclick="five()">
                        <!-- criando botão número 5, atribuindo valor numérico -->
                        <input type="button" class="btn btn-primary ml-3" value="6" onclick="six()">
                        <!-- criando botão número 6, atribuindo valor numérico -->
                        <input type="button" class="btn btn-primary ml-3" value="-" onclick="document.calculator.display.value+='-'"><br><br>
                        <!-- criando botão operador -, atribuindo valor de operação -->
                        <input type="button" class="btn btn-primary" value="1" onclick="one()">
                        <!-- criando botão número 1, atribuindo valor numérico -->
                        <input type="button" class="btn btn-primary ml-3" value="2" onclick="two()">
                        <!-- criando botão número 2, atribuindo valor numérico -->
                        <input type="button" class="btn btn-primary ml-3" value="3" onclick="three()">
                        <!-- criando botão número 3, atribuindo valor numérico -->
                        <input type="button" class="btn btn-primary ml-3" value="+" onclick="document.calculator.display.value+='+'"><br><br>
                        <!-- criação botão operador +, atribuindo valor de operação -->
                        <input type="button" class="btn btn-primary" value="0" onclick="zero()">
                        <!-- criando botão número 0 -->
                        <input type="button" class="btn btn-primary ml-3" value="00" onclick="document.calculator.display.value+='00'">
                        
                        <!-- criando botão dezena -->
                        <input type="button" class="btn btn-primary ml-3" value="." onclick="ponto()">
                        <!-- criando botão separador milhar . -->
                        <input type="button" class="btn btn-primary ml-3" value="=" onclick="document.calculator.display.value = eval(calculator.display.value)">
                        <!-- criando botão operador = -->
                    </form>
                </div>
            </div>
                            
     </div>
        <script>
            src="custom.js"
        </script>
        <script
            src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integridade="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous">
        </script>
        <script
            src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" integridade="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" crossorigin="anônimo">
        </script>
    </body>
</html>

<!-- origem do repositório git https://github.com/profluizangelo/VsCodeIntro.git -->

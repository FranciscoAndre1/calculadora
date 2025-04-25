# calculadora
let operacao = prompt('informe a operacao:( + , - , * , /) ');
let valo1 = parseFloat(prompt('informe o primeiro valor: '));
let valo2 = parseFloat(prompt('informe o segundo valor: '));


if (operacao ==='+') {
    let soma = valo1 + valo2;
    console.log(soma);
}else if(operacao === '-'){
    let subtracao = valo1 - valo2;
    console.log(subtracao);
}else if(operacao === '*'){
    let multiplicacao = valo1 * valo2;
    console.log(multiplicacao);
}else if(operacao === '/'){
    let divisao = valo1 / valo2;
    console.log(divisao);
}

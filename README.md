<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
    
<script>
    // let numero = prompt("Digite um número:");

    // if (numero > 0) {
    //     alert("O número é positivo!");
    // } else {
    //     alert("O número é negativo ou zero!");
    // }

    // let idade = prompt("Digite sua idade:");

    // if (idade >= 18) {
    //     alert("Você é maior de idade!");
    // } else {
    //     alert("Você é menor de idade!");
    // }


    // let numero = prompt("Digite um número:");

    // if (numero % 2 === 0) {
    //     alert("O número é par!");
    // } else {
    //     alert("O número é ímpar!");
    // }

    // let numeroSecreto = 5;
    // let chute = prompt("Adivinhe o número (entre 1 e 10):");

    // if (chute == numeroSecreto) {
    //     alert("Você acertou!");
    // } else {
    //     alert("Você errou! O número era " + numeroSecreto);
    // }

//     let nota = Number(prompt("Digite sua nota (0 a 10):"));

// if (nota >= 9) {
//     alert("Excelente! Você tirou uma nota A.");
// } else if (nota >= 7) {
//     alert("Bom trabalho! Você tirou uma nota B.");
// } else if (nota >= 5) {
//     alert("Você tirou uma nota C. Pode melhorar.");
// } else {
//     alert("Nota insuficiente. Você tirou uma nota D.");
// }

// Exercicios

// 1.
// let numero1 = prompt("Digite um número:");
// let numero2 = prompt("Digite um número:");
// let numero3 = prompt("Digite um número:");

// if (numero1 > 0) {
// alert("O número 1 é positivo!");}
// if (numero2 > 0) {
// alert("O número 2 é positivo!");}
// if (numero3 > 0) {
// alert("O número 3 é positivo!");}
// else {
// alert("O número é negativo ou zero!");}

// 2.
// let numero1 = Number(prompt("Digite o primeiro número:"));
// let numero2 = Number(prompt("Digite o segundo número:"));
// let operacao = prompt("Digite a operação matemática (+,-,*,/):").toLowerCase();

// if (operacao === "+") {
//     alert("O resultado é: " + (numero1 + numero2));
// } else if (operacao === "-" || operacao === "subtracao") {
//     alert("O resultado é: " + (numero1 - numero2));
// } else if (operacao === "*" || operacao === "multiplicacao") {
//     alert("O resultado é: " + (numero1 * numero2));
// } else if (operacao === "/" || operacao === "divisao") {
//     if (numero2 !== 0) {
//         alert("O resultado é: " + (numero1 / numero2));
//     } else {
//         alert("Erro: Não é possível dividir por zero.");
//     }
// } else {
//     alert("Operação inválida. Tente novamente.");
// }

// // 3.
// let numero = Number(prompt("Digite um número"));

// if (numero >= 50 && numero <= 100){
//     alert("Este número está entre 50 e 100")
// } else {
//     alert("Este número não está entre 50 e 100")
// }
// 4.
// let valorCompra = Number(prompt("Qual é o valor total da compra?"));
// if (valorCompra > 100) {
// let desconto = valorCompra * 0.9;
//     let valorFinal = valorCompra - desconto;
//     alert("Você recebeu um desconto de 10%! O valor final da compra é: R$ " + valorFinal.toFixed(2));
// } else {
//     // Caso contrário, exibir o valor sem desconto
//     alert("O valor da compra é: R$ " + valorCompra.toFixed(2));
// }
// 5.
// let altura = Number(prompt("Digite a altura da pessoa em cm:"));

// if (altura < 150) {
//     alert("A pessoa é considerada Baixa.");
// } else if (altura >= 150 && altura <= 180) {
//     alert("A pessoa é considerada Média.");
// } else if (altura > 180) {
//     alert("A pessoa é considerada Alta.");
// } else {
//     alert("Entrada inválida. Por favor, insira um número válido.");
// }
// 6.
// let senhaCorreta = "qwerty";

// let senha = prompt("Digite a senha:");

// if (senha === senhaCorreta) {
//     alert("Acesso permitido");
// } else {
//     alert("Acesso negado");
// }
// 7.
// let numero = Number(prompt("Digite um número:"));

// if (numero % 2 === 0) {
//     alert("O número é Par.");
// } else {
//     if (numero > 50) {
//         alert("O número é Ímpar e é um Número especial.");
//     } else {
//         alert("O número é Ímpar.");
//     }
// }
// // 8.
// let idade = Number(prompt("Digite sua idade:"));

// if (idade <= 12) {
//     alert("Você é uma criança.");
// } else if (idade >= 13 && idade <= 17) {
//     alert("Você é um adolescente.");
// } else if (idade >= 18 && idade <= 64) {
//     alert("Você é um adulto.");
// } else if (idade >= 65) {
//     alert("Você é um idoso.");
// } else {
//     alert("Idade inválida. Tente novamente.");
// }
// 9.
// let numeroCorreto = 7;

// let numeroUsuario = Number(prompt("Adivinhe o número entre 1 e 10:"));

// if (numeroUsuario === numeroCorreto) {
//     alert("Parabéns, você acertou!");
// } else {
//     alert("Tente novamente!");
// }
// 10.
// let nota = Number(prompt("Digite sua nota entre 0 e 10:"));

// if (nota >= 0 && nota <= 4) {
//     alert("Desempenho: Ruim");
// } else if (nota >= 5 && nota <= 7) {
//     alert("Desempenho: Bom");
// } else if (nota >= 8 && nota <= 10) {
//     alert("Desempenho: Excelente");
// } else {
//     alert("Nota inválida. Por favor, insira uma nota entre 0 e 10.");
// }

// Desafio final
// Entrada de Dados
// let nome = prompt("Digite seu nome:");
// let idade = Number(prompt("Digite sua idade:"));
// let pontuacaoProvaTecnica = Number(prompt("Digite sua pontuação na Prova Técnica (0 a 10):"));
// let pontuacaoEntrevista = Number(prompt("Digite sua pontuação na Entrevista (0 a 10):"));

// // Critérios de Seleção
// let idadeMinima = 18;
// let pontuacaoMinimaProvaTecnica = 7;
// let pontuacaoMinimaEntrevista = 6;

// // Verificar se o candidato atende aos critérios
// if (idade < idadeMinima) {
//     alert(`Desculpe, ${nome}, você não atende aos critérios de idade.`);
// } else if (pontuacaoProvaTecnica < pontuacaoMinimaProvaTecnica) {
//     alert(`Infelizmente, ${nome}, sua pontuação na Prova Técnica foi insuficiente.`);
// } else if (pontuacaoEntrevista < pontuacaoMinimaEntrevista) {
//     alert(`Infelizmente, ${nome}, sua pontuação na Entrevista foi insuficiente.`);
// } else {
//     let mediaGeral = (pontuacaoProvaTecnica + pontuacaoEntrevista) / 2;

//     // Se o candidato passou em todos os critérios
//     alert(`Parabéns, ${nome}! Você foi aprovado para a vaga.`);
    
//     // Verificar se é "Altamente Qualificado"
//     if (mediaGeral >= 8) {
//         alert("Você é Altamente Qualificado!");
//     }
// }







</script>




</body>
</html>

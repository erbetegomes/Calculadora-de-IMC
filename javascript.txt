
console.log("Calculadora IMC:")

Peso = 54
Altura = 1.72

IMC = (Peso/(Altura**2))

console.log("")
console.log(IMC)

if (IMC <= 18.5){
 console.log("Abaixo do Peso")
}
else if (IMC <= 24.9)
 console.log("Peso Normal")
else if (IMC <= 34.9)
 console.log("Obesidade Grau I")
else if (IMC <= 39.9)
 console.log("Obesidade Grau II")
else if (IMC >= 40)
 console.log("Obesidade Grau III")

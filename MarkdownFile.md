**EXERCÍCIO PRÁTICO RÁPIDO**

Complete o código abaixo:

typescript

// 1. Crie um tipo literal para cor com: "vermelho", "azul", "verde"

type Cor = “vermelho”\_\_”azul” “ verde”;

// 2. Crie um tipo Carro com:

// - marca (string, readonly)

// - modelo (string)

// - cor (do tipo Cor acima)

// - ano? (opcional, number)

type Carro = {

readonly marca : (string)

readonly modelo: (string)

cor: string;

ano? number

};

// 3. Crie uma função Generic que retorne o primeiro elemento de um array

function primeiro<T>(array: T \[ \] ): T {

return array \[0\];

}
let nomeHeroi = "Batman";
let nivelHeroi = 9000;
let patente = "";

if (nivelHeroi > 10000) {
    patente = "imortal";
} else if (nivelHeroi > 9000) {
    patente = "ascendente";
} else if (nivelHeroi > 8000) {
    patente = "diamante";
} else if (nivelHeroi > 7000) {
    patente = "ouro";
} else if (nivelHeroi > 5000) {
    patente = "prata";
} else if (nivelHeroi > 2000) {
    patente = "ferro";
} else if (nivelHeroi > 1000) {
    patente = "bronze";
} else {
    patente = "iniciante"; // Se o nível for menor ou igual a 1000
}

console.log("O herói " + nomeHeroi + " está no nível " + nivelHeroi + " e é patente " + patente);

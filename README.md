<div align="center">
  <h1>🛡️ Hero Level Classifier</h1>
  
  <p>
    Algoritmo de classificação de ranking baseado em experiência (XP).
    Desenvolvido como desafio de lógica no Bootcamp <b>Ri Happy - Front-end do Zero / DIO</b>.
  </p>

  <img src="https://img.shields.io/github/languages/top/EderJuniorS/Classificador-de-Nivel-de-Heroi?style=flat-square&color=yellow">
  <img src="https://img.shields.io/badge/Node.js-Run_Local-green?style=flat-square&logo=node.js">
  <img src="https://img.shields.io/github/last-commit/EderJuniorS/Classificador-de-Nivel-de-Heroi?style=flat-square&color=blue">
</div>

<br>

## 📋 Sobre o Desafio

O objetivo deste script é implementar uma estrutura de decisão robusta para categorizar o nível de um herói em um RPG, baseando-se em faixas de valores numéricos (Experience Points - XP).

O projeto foca em:
- Declaração de variáveis (`let`, `const`).
- Estruturas condicionais encadeadas (`if`, `else if`, `else`).
- Operadores de comparação (`<=`, `>=`).
- Saída de dados formatada (Template String).

## 📊 Tabela de Classificação

O algoritmo segue a seguinte regra de negócio para determinar o rank:

| Faixa de XP (Experience) | Nível do Herói |
| :--- | :--- |
| **Abaixo de 1.000** | 🔩 Ferro |
| **1.001 a 2.000** | 🥉 Bronze |
| **2.001 a 5.000** | 🥈 Prata |
| **5.001 a 7.000** | 🥇 Ouro |
| **7.001 a 8.000** | 💎 Platina |
| **8.001 a 9.000** | 🔮 Ascendente |
| **9.001 a 10.000** | 👹 Imortal |
| **Acima de 10.001** | 🔥 Radiante |

## 🛠️ Tecnologias

- ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) **ES6+ Syntax**
- ![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white) **Runtime Environment**

## 💻 Exemplo de Código

A lógica central utiliza condicionais para verificar o intervalo do XP:

```javascript
// Exemplo de estrutura utilizada
if (xp <= 1000) {
    nivel = "Ferro";
} else if (xp >= 1001 && xp <= 2000) {
    nivel = "Bronze";
}
// ...
console.log(`O Herói de nome ${nome} está no nível de ${nivel}`);
```

## 🚀 Como Executar
Este projeto requer o Node.js instalado.

Clone o repositório:
```bash
git clone https://github.com/EderJuniorS/Classificador-de-Nivel-de-Heroi.git
```

Navegue até a pasta:
```bash
cd Classificador-de-Nivel-de-Heroi
```

Execute o script:
```bash
node index.js
```

<div align="center"> Desenvolvido por <a href="https://www.linkedin.com/in/ederjuniormatossilva">Éder Junior</a> durante o Bootcamp DIO. </div>

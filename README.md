# Desafio Codeforces — Mentoria Codificadas | Além do Código
 
## Sobre este repositório
 
Este repositório contém minha resolução para o desafio de programação proposto na mentoria, utilizando problemas da plataforma [Codeforces](https://codeforces.com/) com auxílio de Inteligência Artificial.
 
---
 
## Problemas escolhidos
 
| # | Nome do problema | Link | Dificuldade |
|---|-----------------|------|-------------|
| 1 | Pizza Time | [Ver no Codeforces](https://codeforces.com/contest/2156/problem/A) | 800 |
 
---
 
## Problema — [Pizza Time]
 
### O que o problema pede?
<!-- Explique com suas próprias palavras o que o problema pede. Não copie o enunciado. -->
 
 
### Como eu resolvi?
<!-- Descreva a estratégia que você usou. Por exemplo: ordenei a lista, filtrei os negativos, etc. -->
 
 
### Código
#include <stdio.h>

int main() {
    int t;
    scanf("%d", &t);

    while (t--) {
        long long n;
        scanf("%lld", &n);

        printf("%lld\n", (n - 1) / 2);
    }

    return 0;
}

---
 
## IA utilizada
 
**Qual IA você usou?**
ChatGPT
 
**Como a IA te ajudou?**
Me ajudou na parte de lógica, e matemática. 

---
 
## Reflexão
 
### Dificuldades encontradas
A maior dificuldade foi entender completamente a lógica dos problemas e encontrar a solução correta dentro do tempo limite. Também tive que corrigir alguns erros de compilação e respostas erradas até chegar na solução final.


### O que aprendi
Aprendi mais sobre lógica de programação, manipulação de problemas matemáticos e análise de casos especiais. Também pratiquei bastante depuração de código e interpretação de enunciados competitivos.


### Como foi a experiência?
Foi uma experiência desafiadora, mas muito divertida. Gostei principalmente de tentar diferentes abordagens até encontrar uma solução que funcionasse corretamente. Acho que isso ajudou bastante a desenvolver raciocínio lógico e persistência.

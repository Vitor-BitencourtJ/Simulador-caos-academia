# Academia Caótica – Simulação em Python

### Projeto feito no curso da ASIMOV, de python intermediário

Este projeto simula o comportamento de usuários em uma academia ao utilizarem halteres.  
A ideia é observar como o **nível de desorganização** aumenta com 1 usuário desorganizado.

---

## 🎯 Objetivo

Simular o caos gerado na organização dos halteres quando existem diferentes perfis de usuários:

| Tipo de Usuário | Comportamento ao devolver o halter |
|-----------------|-----------------------------------|
| 1 – Organizado  | Tenta devolver no lugar correto, caso esteja livre |
| 2 – Bagunceiro  | Devolve sempre em um espaço aleatório |

O resultado é uma medida de **caos** baseada no número de halteres fora do lugar certo.

---

## 🧠 Como funciona

- A academia começa com halteres organizados, de 10 a 34 kg (apenas números pares).
- Usuários pegam pesos aleatórios para treinar.
- No final do treino, devolvem os halteres com base no seu tipo.
- Após vários ciclos, o programa calcula o nível de bagunça usando:


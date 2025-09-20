# 🃏 Super Trunfo em C

Este projeto é uma implementação simples do jogo **Super Trunfo** em linguagem **C**, com comparação de cartas baseadas em atributos como população, área, PIB, entre outros.

---

## 📦 Compilação e Execução

### ✅ Requisitos

- GCC ou outro compilador C
- Terminal Linux, macOS ou Windows (com MinGW)

### 🔧 Compilando

```bash
gcc super_trunfo.c -o super_trunfo
````

### ▶️ Executando

```bash
./super_trunfo
```

---

## 📝 Exemplo de Saída

```
📄 Detalhes das Cartas:

🃏 Carta 1:
São Paulo (A01 - Estado A)
População: 12325000 habitantes
Área: 1521.11 km²
PIB: 699.28 bilhões de reais
Pontos Turísticos: 50
Densidade Populacional: 8102.47 hab/km²
PIB per Capita: 56724.32 reais
Super Poder: 12325000 + 1521.11 + 699280000000 + 50 + 56724.32 + (1 / 8102.47) ≈ ...

🃏 Carta 2:
Rio de Janeiro (B02 - Estado B)
População: 6748000 habitantes
Área: 1200.25 km²
PIB: 300.50 bilhões de reais
Pontos Turísticos: 30
Densidade Populacional: 5622.24 hab/km²
PIB per Capita: 44532.91 reais
Super Poder: 6748000 + 1200.25 + 300500000000 + 30 + 44532.91 + (1 / 5622.24) ≈ ...

Escolha um atributo para comparar:
1 - População
2 - Área
3 - PIB
4 - Pontos Turísticos
5 - Densidade Populacional (MENOR vence)
6 - PIB per Capita
7 - Super Poder
Escolha: 1

Escolha um atributo para comparar:
1 - População
2 - Área
3 - PIB
4 - Pontos Turísticos
5 - Densidade Populacional (MENOR vence)
6 - PIB per Capita
7 - Super Poder
Escolha: 5

🔍 Comparando atributos selecionados...

Atributo: População  
- Carta 1 (São Paulo): 12.325.000  
- Carta 2 (Rio de Janeiro): 6.748.000  
**Vencedor: Carta 1**

Atributo: Densidade Populacional (MENOR vence)  
- Carta 1 (São Paulo): 8102.47 hab/km²  
- Carta 2 (Rio de Janeiro): 5622.24 hab/km²  
**Vencedor: Carta 2**

🏁 Resultado Final: Empate!  
Cada carta venceu um atributo.
```

---

## 🧠 Atributos disponíveis para comparação

| Atributo               | Quem vence?              |
| ---------------------- | ------------------------ |
| População              | Maior                    |
| Área                   | Maior                    |
| PIB                    | Maior                    |
| Pontos Turísticos      | Maior                    |
| Densidade Populacional | **Menor**                |
| PIB per Capita         | Maior                    |
| Super Poder            | Maior (cálculo especial) |

---

## 🧮 Cálculos

* **Densidade Populacional** = população / área
* **PIB per Capita** = PIB / população
* **Super Poder** = soma de todos os atributos + (1 / densidade)

---

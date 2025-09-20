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

Carta 1
  População: 5000000
  Área: 1500.00
  PIB: 100000000000.00
  Pontos Turísticos: 100
  Densidade Populacional: 3333.33
  PIB per Capita: 20000.00
  Super Poder: 100005168133.03

Carta 2
  População: 8000000
  Área: 1200.00
  PIB: 120000000000.00
  Pontos Turísticos: 150
  Densidade Populacional: 6666.67
  PIB per Capita: 15000.00
  Super Poder: 120009383316.25

📊 Comparando cartas...
- População: Carta 2 venceu
- Área: Carta 1 venceu
- PIB: Carta 2 venceu
- Pontos Turísticos: Carta 2 venceu
- Densidade Populacional: Carta 1 venceu
- PIB per Capita: Carta 1 venceu
- Super Poder: Carta 2 venceu

Resultado final:
Carta 1 venceu 3 atributos
Carta 2 venceu 4 atributos
🏆 Carta 2 é a vencedora!
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

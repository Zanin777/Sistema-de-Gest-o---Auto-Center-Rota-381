# 🔧 Auto Center Rota 381 — Sistema de Gestão

Trabalho Prático Avaliativo da disciplina **Desenvolvimento de Programas Estruturados e Modularização**  
Professor: Raffael Carvalho | UNIVÀS

---

## 📋 Sobre o Projeto

Sistema de terminal desenvolvido em Java para gerenciar as operações diárias de uma oficina mecânica. O sistema substitui planilhas manuais, controlando o cadastro de mecânicos, veículos, estoque de peças e ordens de serviço, com geração de relatórios financeiros.

---

## 🗂️ Estrutura do Projeto

```
AutoCenter/
├── src/
│   ├── Main.java           # Menu principal e loop do sistema
│   ├── Mecanico.java       # Vetores de mecânicos
│   ├── Veiculo.java        # Vetores de veículos
│   ├── Peca.java           # Vetores de peças/estoque
│   ├── OrdemServico.java   # Vetores de ordens de serviço
│   └── Sistema.java        # Toda a lógica do sistema
└── dados/
    ├── mecanicos.csv
    ├── veiculos.csv
    ├── pecas.csv
    └── ordens.csv
```

---

## ⚙️ Funcionalidades

### ✅ Encontro 1 — Cadastros Base (concluído)
- Estruturas de dados criadas com vetores fixos para Mecânico, Veículo, Peça e OS
- Menu interativo no terminal
- Cadastro e listagem de Mecânicos, Veículos e Estoque de Peças em memória
- Validação de duplicidade em todos os cadastros

### 🔄 Encontro 2 — Ordem de Serviço (em desenvolvimento)
- Abertura de OS vinculando placa, mecânico e peça
- Validação se a placa e o mecânico estão cadastrados
- Bloqueio de lançamento se a quantidade em estoque for insuficiente
- Desconto automático da quantidade no estoque ao abrir a OS

### 🔄 Encontro 3 — Persistência de Dados (pendente)
- Gravação de todos os vetores em arquivos `.csv`
- Leitura dos arquivos ao iniciar o sistema
- Dados sobrevivem ao fechar o programa

### 🔄 Encontro 4 — Relatórios e Diferencial (pendente)
- **Comissão da Equipe:** total de mão de obra gerado por cada mecânico
- **Inventário Crítico:** peças com quantidade zero em estoque
- **Faturamento de Peças:** valor total de peças utilizadas nas OSs
- Funcionalidade extra (diferencial)

---

## 🚀 Como Executar

Dentro da pasta `src/`, execute:

```bash
javac *.java
java Main
```

---

## 🚫 Restrições Técnicas

O projeto segue as exigências da disciplina:

- ✅ Lógica estruturada (Java procedural com métodos `static`)
- ✅ Vetores de tamanho fixo
- ✅ Manipulação de arquivos de texto (`.csv`)
- ❌ Sem Orientação a Objetos (sem construtores, sem encapsulamento)
- ❌ Sem coleções dinâmicas (`ArrayList`, `List`, `HashMap`)
- ❌ Sem banco de dados relacional (SQL)

---

## 🗓️ Sprints e Checkpoints

| Encontro | Foco | Status |
|----------|------|--------|
| 1 | Structs, menus e inserção em memória | ✅ Concluído |
| 2 — Checkpoint 1 | Abertura de OS com validação cruzada e controle de estoque | 🔄 Pendente |
| 3 — Checkpoint 2 | Persistência de dados em arquivos `.csv` | 🔄 Pendente |
| 4 — Checkpoint 3 | Relatórios, funcionalidade diferencial e README da IA | 🔄 Pendente |

---

## 🤖 Diário da IA

*Documentação obrigatória do uso de IA como ferramenta de apoio ao desenvolvimento.*

1. **Ferramentas proibidas que a IA sugeriu:** *(a preencher ao longo dos encontros)*
2. **Prompt usado para forçar o padrão estruturado:** *(a preencher ao longo dos encontros)*
3. **Regra de negócio que precisou de correção manual:** *(a preencher ao longo dos encontros)*

---

## 👥 Equipe

Luiz Gustavo Silva Nogueira
Gabriel Silva Machado
Matheus Zanin

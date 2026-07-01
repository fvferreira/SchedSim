# SchedSim – Simulador Didático de Escalonamento de Processos

## Sobre o Projeto

O **SchedSim** é um simulador didático desenvolvido em **Flutter** e **Dart** com o objetivo de demonstrar o funcionamento do algoritmo de escalonamento **Round Robin**, amplamente utilizado em Sistemas Operacionais.

A aplicação permite a criação e configuração de processos, executando a simulação do escalonamento e apresentando, de forma visual, o comportamento da CPU ao longo da execução.

O software foi desenvolvido como projeto da disciplina de **Sistemas Operacionais** da Universidade Federal Rural do Semi-Árido (UFERSA), visando apoiar o ensino e a aprendizagem dos conceitos de escalonamento de processos.

---

# Principais Funcionalidades

- Simulação do algoritmo **Round Robin**
- Criação e gerenciamento de processos
- Configuração do Quantum
- Definição do tempo total da simulação
- Visualização da linha do tempo de execução dos processos
- Cálculo automático da utilização da CPU
- Cálculo do tempo médio de espera

---

# Tecnologias Utilizadas

- Flutter
- Dart

---

# Plataformas Suportadas

- Windows
- Linux

---

# Estrutura do Projeto

```text
SchedSim/
│
├── lib/
├── assets/
├── build/
├── docs/
├── windows/
├── linux/
├── README.md
└── pubspec.yaml
```

---

# Como Executar

## Linux

```bash
cd Simulador_SchedSim_Linux
chmod +x schedsim
./schedsim
```

## Windows

Acesse a pasta:

```text
Simulador_SchedSim_Windows
```

Execute:

```text
schedsim.exe
```

> **Importante:** mantenha todos os arquivos da pasta do executável. O programa depende das bibliotecas distribuídas juntamente com ele.

---

# Objetivo

O SchedSim foi desenvolvido com finalidade educacional para auxiliar estudantes na compreensão do funcionamento do algoritmo de escalonamento Round Robin, permitindo observar, de maneira prática, o comportamento da CPU durante a execução de processos.

---

# Informações do Projeto

| Item            | Informação                                                  |
| --------------- | ----------------------------------------------------------- |
| Nome            | SchedSim – Simulador Didático de Escalonamento de Processos |
| Versão          | 1.0.0                                                       |
| Data de criação | 20/04/2026                                                  |
| Linguagem       | Dart                                                        |
| Framework       | Flutter                                                     |
| Plataforma      | Windows e Linux                                             |
| Algoritmo       | Round Robin                                                 |

---

# Autor

**João Victor Ferreira da Silva**

Projeto desenvolvido para a disciplina de Sistemas Operacionais da Universidade Federal Rural do Semi-Árido (UFERSA).

---

# Licença

Este projeto possui finalidade exclusivamente acadêmica e educacional.

Todos os direitos autorais pertencem ao autor.

© 2026 João Victor Ferreira da Silva.

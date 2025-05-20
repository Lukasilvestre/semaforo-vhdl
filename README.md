# Projeto Semáforo em VHDL 🚦

Este projeto implementa um sistema com **três semáforos** utilizando a linguagem VHDL. Cada semáforo alterna entre os estados **verde**, **amarelo** e **vermelho** com base em um contador de tempo.

## 💻 Funcionalidades

- Controle de três semáforos independentes.
- Troca automática entre os estados com temporizador.
- Saídas codificadas em 3 bits representando o estado dos LEDs (verde, amarelo, vermelho).

## 🧠 Lógica de Funcionamento

- Cada semáforo tem seu próprio contador e estado.
- A transição segue o ciclo: `vermelho → verde → amarelo → vermelho`.
- Os valores de saída seguem o seguinte padrão:
  - `100` = Verde
  - `010` = Amarelo
  - `001` = Vermelho

## 🧪 Simulação

Este código pode ser testado em simuladores como:
- **ModelSim**
- **Vivado**
- **GHDL + GTKWave**

## 📁 Arquivos

- `VHDL`: Código-fonte VHDL do projeto.

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar, modificar e distribuir.


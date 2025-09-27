# 🏨 Sistema de Hospedagem - Desafio Classe Reserva

## 📖 Descrição

Este projeto é um **sistema de hospedagem em C#**, desenvolvido como desafio para **resolver e completar a classe `Reserva`**.  
O foco foi garantir que hóspedes e suítes fossem cadastrados corretamente, validar capacidade da suíte e calcular o valor da diária com regras de desconto.

Mesmo sendo um desafio sobre uma classe específica, o projeto permitiu aprendizado real em **POO, listas, condicionais e exceções**.

---

## ✨ Funcionalidades

- 🧑‍🤝‍🧑 Cadastro de hóspedes com validação da capacidade da suíte.  
- 🛏 Cadastro de suíte na reserva.  
- 📊 Obtenção da quantidade de hóspedes (`ObterQuantidadeHospedes()`).  
- 💰 Cálculo do valor total da diária (`CalcularValorDiaria()`) com **10% de desconto para reservas ≥ 10 dias**.  
- ⚠️ Lançamento de **exceções** se a capacidade da suíte for excedida.  

---

## 🏗 Estrutura do Projeto

- **Models**
  - `Pessoa.cs` — representação dos hóspedes.  
  - `Suite.cs` — tipos de suíte, capacidade e valor da diária.  
  - `Reserva.cs` — cadastro de hóspedes, cadastro de suíte, validação e cálculo de valor.

- **Program.cs** — cria hóspedes, suítes e reservas, mostrando informações no console.

---

## 🔧 Como Executar

1. Instale o **.NET SDK** (6 ou superior).  
2. Clone o repositório:  
   ```bash
   git clone https://github.com/italofvm/desafio_sistema_de_hospedagem
3. Navegue até a pasta do projeto e execute:
    ```bash
    dotnet run
4. Veja no console a quantidade de hóspedes e o valor da diária.

## 💡 Dificuldades e Aprendizado

- Evitar NullReferenceException ao inicializar a lista de hóspedes.

- Comparar corretamente a lista recebida com a capacidade da suíte.

- Implementar cálculo do valor da diária com desconto.

- Compreender e completar métodos com placeholders (TODO).

**Aprendi a importância de validar dados, organizar classes e implementar lógica de negócio de forma segura e eficiente.**

## 👤 Autor

Desenvolvido por Italo

Aprendizado em C# com foco em lógica, POO e tratamento de exceções.


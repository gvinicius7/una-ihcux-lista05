
# 💱 ConversorExpert - Global Exchange

Este projeto foi desenvolvido com o objetivo de aplicar, na prática, conceitos fundamentais de **Interação Humano-Computador (IHC)** e **Experiência do Usuário (UX)** utilizando uma aplicação de console em C#.

---

## 📌 Sobre o projeto

A proposta consiste na criação de um conversor de moedas (de Real para Dólar) que vá além da funcionalidade básica, buscando também oferecer uma interação clara, intuitiva e eficiente para o usuário.

---

## 🧩 Princípios de Usabilidade Utilizados

Durante o desenvolvimento, foram consideradas algumas das principais heurísticas de Nielsen para melhorar a interação com o sistema.

---

### 🔎 Feedback do sistema ao usuário

O programa mantém o usuário informado em todas as etapas da execução.

**Como isso foi aplicado:**

* Exibição de mensagens como: `"Conectando ao Banco Central..."`
* Simulação de processamento com animações (`Calculando taxas...`)
* Pequenas pausas com `Thread.Sleep` para tornar a execução mais realista

✔️ Isso ajuda o usuário a entender que o sistema está ativo e evita confusão durante o uso.

---

### ⚠️ Tratamento e prevenção de erros

O sistema foi projetado para lidar com entradas incorretas de forma segura.

**Implementações realizadas:**

* Uso de blocos `try-catch` para evitar falhas inesperadas
* Mensagens explicativas para orientar o usuário:
  `"Entrada inválida! Utilize apenas números..."`

✔️ Dessa forma, o programa continua funcionando normalmente mesmo diante de erros.

---

### 🎨 Interface simples e eficiente

A interface foi pensada para ser direta, sem elementos desnecessários.

**Características do design:**

* Destaque visual com cores:

  * Amarelo para títulos
  * Verde para resultados
  * Vermelho para erros
* Organização do conteúdo com separadores
* Exibição clara e objetiva das informações

✔️ Isso melhora a legibilidade e torna a experiência mais agradável.

---

## 🚀 Execução do projeto

Para rodar a aplicação, utilize o comando abaixo no terminal:

```bash
dotnet run
```

---

## 🖼️ Demonstração

O arquivo `evidencia-final.png` apresenta o sistema em funcionamento, incluindo:

* Etapa de carregamento simulado
* Conversão realizada corretamente

---

## ⚙️ Tecnologias e conceitos

O projeto foi desenvolvido utilizando:

* C#
* Aplicação Console (.NET)
* Conceitos de UX e IHC aplicados na prática

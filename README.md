# LOO10_Anhanguera

ROTEIRO DE AULA PRÁTICA

Disciplina: Linguagem Orientada a Objetos
Tema: Interfaces, Classes Abstratas e Tratamento de Exceções
Título da Atividade: Sistema de Pagamentos — Implementando Interface e Exceções

🎯 Objetivos

Compreender o uso de interfaces e classes abstratas.

Implementar tratamento de exceções em operações de negócio.

Reforçar boas práticas de encapsulamento e polimorfismo.

Realizar upload do código no GitHub.

🧩 Contexto da Atividade

A empresa fictícia PaySimone precisa de um pequeno sistema para processar pagamentos de cartão de crédito e PIX.
Cada forma de pagamento deve calcular o valor final de uma compra com desconto ou taxa, e lançar uma exceção caso o valor seja inválido (menor ou igual a zero).

Você vai modelar esse sistema em Java, aplicando interface, classes abstratas, herança e exceções personalizadas.

💻 Infraestrutura

IDE sugerida: Eclipse, NetBeans ou IntelliJ IDEA

Java 17+

GitHub (repositório público para submissão)

⚙️ PROCEDIMENTOS PRÁTICOS
🧱 Etapa 1 – Criar o Projeto

Abra o IDE de sua preferência.

Crie um projeto chamado AtividadePagamento.

Dentro do src, crie o pacote:

br.com.aluno.pagamento

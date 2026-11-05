# 🍽️ Sistema de Gestão e Controlo da Merenda Escolar (CETI Ozias Correia)

> Protótipo desenvolvido no âmbito da disciplina de **Atividades Práticas Interdisciplinares de Extensão II (APIEXT II)** do curso de **Análise e Desenvolvimento de Sistemas (ADS)** do Centro Universitário Uninassau Parnaíba.

---

## 📌 Sobre o Projeto
Este repositório contém o código-fonte de uma solução tecnológica desenvolvida para otimizar o fluxo de distribuição de refeições no **Centro Educacional de Tempo Integral (CETI) Ozias Correia**, localizado em Parnaíba - PI. 

O objetivo principal é substituir o controlo manual em filas por um registo digital individualizado em tempo real, garantindo maior eficiência operacional, respeito ao cardápio planejado por nutricionistas e prevenção do desperdício de alimentos.

---

## 🚀 Funcionalidades da Aplicação
A aplicação é dividida em duas interfaces principais baseadas em arquitetura estática conectada a uma base de dados em nuvem:

1. **Rota do Aluno (`index.html`):**
   * Interface acessível via telemóvel por QR Code ou link direto.
   * Permite que o estudante selecione a sua turma e confirme o pedido do almoço de forma rápida e intuitiva.

2. **Painel da Merendeira (`merendeira.html`):**
   * Tela em tempo real destinada à equipa da cozinha/gestão.
   * Mostra um contador dinâmico com o total de refeições solicitadas.
   * Atualiza instantaneamente a lista com o nome dos alunos, turmas e horários dos pedidos à medida que são submetidos.

---

## 🛠️ Tecnologias Utilizadas
* **Front-end:** HTML5, CSS3 e JavaScript (Vanilla).
* **Base de Dados & Tempo Real:** Supabase (PostgreSQL + Realtime Channels).
* **Hospedagem:** Vercel / GitHub Pages.

---

## Rota dos alunos
* https://monteirocode1.github.io/projeto-merenda/

## Rota do Painel da Cozinha
* https://monteirocode1.github.io/projeto-merenda/merendeira

## 👥 Equipa de Desenvolvimento (ADS - Uninassau Parnaíba)
* Danilo Silva Brito
* Guilherme Monteiro Duarte
* João Gabriel de Menesses e Silva
* Kueren Hazlen dos Santos Oliveira
* Paulo Vinicius de Sousa Araújo
* Willian Cavalcante Santos
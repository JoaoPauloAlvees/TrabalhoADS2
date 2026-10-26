# 🐾 GreenShare - Plataforma de Doação e Apoio Animal

Projeto desenvolvido como **Atividade de Extensão** do curso Superior de Tecnologia em **Análise e Desenvolvimento de Sistemas (ADS)** da **Universidade Nova Iguaçu (UNIG)**.

## 📌 Sobre o Projeto
O **GreenShare** é uma aplicação web fullstack desenvolvida para apoiar protetores independentes e abrigos de animais em situação de vulnerabilidade (com foco em um abrigo localizado no bairro Caonze, em Nova Iguaçu - RJ, que abriga cerca de 40 animais). O sistema otimiza a gestão de doações de ração, medicamentos de alto custo e materiais de limpeza, conectando doadores à causa animal de forma transparente e digital.

O projeto está diretamente alinhado ao **ODS 12 da ONU (Consumo e Produção Responsáveis)** e aos conceitos de **TI Verde**, promovendo o uso consciente de recursos digitais e o combate ao desperdício.

---

## 🚀 Tecnologias Utilizadas
* **Front-end:** HTML5, CSS3, JavaScript (Vanilla) com design responsivo e componentes dinâmicos (Acordeons/Sanfonas e Carrossel de imagens).
* **Back-end & Banco de Dados:** [Supabase](https://supabase.com/) (PostgreSQL na nuvem) para persistência de dados em tempo real.
* **Versionamento & Deploy:** Git, GitHub e hospedagem web na nuvem.

---

## 📊 Modelagem de Dados (Supabase)
O banco de dados relacional foi estruturado com as seguintes tabelas principais:
1. **`doadores`**: Armazena as informações dos cidadãos ou empresas que realizam contribuições (Nome, E-mail, Telefone, Tipo de Doador).
2. **`pontos_coleta`**: Mapeia os locais físicos de arrecadação e entrega de insumos.
3. **`doacoes`**: Tabela central que gerencia os itens doados, o vínculo com o doador, o ponto de coleta correspondente e o status dinâmico (*Pendente* ou *Concluída*).

---

## ⚙️ Funcionalidades (CRUD)
* **Create (Inserir):** Cadastro dinâmico de novos doadores e novas doações integradas ao banco.
* **Read (Consultar):** Listagem em tempo real das doações ativas e pontos de coleta disponíveis.
* **Update (Atualizar):** Alteração lógica do status da doação para "Concluída" diretamente pela interface.
* **Delete (Excluir):** Remoção ou cancelamento de registros de doações incorretas.

---

## 👥 Equipe de Desenvolvimento
* **João Paulo Alves de Souza** — Aluno de ADS / Desenvolvedor Front-end & Banco de Dados
* **Fernando Cruz** — Aluno de ADS / Desenvolvedor & Apoio de Campo

---

## 🏫 Instituição
* **Faculdade:** Universidade Nova Iguaçu (UNIG)
* **Curso:** Tecnologia em Análise e Desenvolvimento de Sistemas (ADS - EAD)
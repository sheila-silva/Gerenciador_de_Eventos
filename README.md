# 🎫 Sistema de Gerenciamento de Eventos

Este projeto é um **sistema de gerenciamento de eventos** desenvolvido com **Spring Boot**, **JPA** e **banco de dados H2 em memória**.  
Ele permite o cadastro e relacionamento entre **atividades**, **participantes**, **categorias** e **blocos de horário**.

---

## ⚙️ Tecnologias
- Java 17+
- Spring Boot
- Spring Data JPA
- H2 Database
- Maven

---

## 🧩 Estrutura do Sistema
Entidades principais:
- **Category** → tipo de atividade (curso, oficina)  
- **Activity** → atividades do evento  
- **Block** → blocos de horário  
- **Participant** → participantes das atividades  

---

O banco é criado automaticamente e populado pelo arquivo `data.sql`.

---



# 🛡️ Simulação de Ataques de Força Bruta com Kali Linux e Medusa

Projeto prático desenvolvido para o desafio da **DIO (Digital Innovation One)** com o objetivo de explorar, compreender e documentar técnicas de força bruta e *password spraying* em ambiente controlado, além de propor medidas efetivas de mitigação.

> ⚠️ **Aviso Legal:** Todos os testes descritos neste repositório foram realizados exclusivamente em ambiente virtualizado isolado (*Host-Only*) para fins educacionais.

---

## 🏗️ Arquitetura do Ambiente

O laboratório foi estruturado no **Oracle VirtualBox** utilizando rede interna (`Host-Only`), garantindo isolamento total da internet:

* **Atacante:** Kali Linux (`192.168.56.100`) — Ferramentas: `Medusa`, `Enum4linux`, `Nmap`.
* **Alvo:** Metasploitable 2 (`192.168.56.101`) — Serviços: `vsftpd` (FTP), `DVWA` (HTTP), `Samba` (SMB).

---

## 📂 Estrutura do Repositório

```text
├── images/               # Capturas de tela dos ataques e validações
├── wordlists/
│   ├── users.txt         # Lista de usuários utilizada nos testes
│   └── passwords.txt     # Lista de senhas utilizada nos testes
└── README.md             # Documentação completa do projeto

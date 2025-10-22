# 🚀 n8n_public

Repositório público com os **arquivos Docker Compose** e **templates de workflows** usados nos projetos da StrixFy e da Echo Academy.

---

## 🧩 Estrutura do Repositório

📦 n8n_public/
┣ 📜 n8n-main.yml # Compose principal do n8n (main instance)
┣ 📜 n8n-worker.yml # Compose dos workers (modo queue)
┣ 📜 evolution-api.yml # Compose da API Evolution
┣ 📜 README.md # Este arquivo
┗ 📂 templates/ # (em breve) Workflows prontos para importação no n8n

yaml
Copiar código

---

## ⚙️ Sobre

Esses arquivos compõem a **infraestrutura base** usada no **Coolify** para hospedar:
- n8n (main + workers)
- Redis
- PostgreSQL
- Evolution API (para WhatsApp)
  
O objetivo é fornecer um ambiente **modular**, **reutilizável** e **aberto** para quem deseja entender como montar um stack de automação completo.

---

## 🎥 Tutorial no YouTube

📺 *Em breve*: [Assista ao tutorial completo no canal do Rodrigo Martins](#)  
*(Substitua o link acima quando o vídeo estiver publicado.)*

---

## 🧠 Templates de Workflows

Na pasta `/templates` serão adicionados:
- Fluxos de **backup automático** para GitHub  
- Fluxos de **sincronização com Google Calendar**  
- Fluxos de **cadastro e atualização de clientes (PostgreSQL)**  
- E muito mais...

---

## 🧰 Tecnologias Utilizadas

- [n8n](https://n8n.io) — plataforma de automação open-source  
- [Coolify](https://coolify.io) — PaaS autohospedável  
- [Redis](https://redis.io) — cache e filas de execução  
- [PostgreSQL](https://www.postgresql.org) — banco de dados relacional  
- [Evolution API](https://github.com/EvolutionAPI/evolution-api) — integração WhatsApp  

---

## 🤝 Contribuição

Quer contribuir?  
1. Faça um fork deste repositório  
2. Crie uma branch (`git checkout -b minha-feature`)  
3. Faça o commit (`git commit -m 'Adiciona novo template'`)  
4. Dê push (`git push origin minha-feature`)  
5. Abra um Pull Request 🚀

---

## 📜 Licença

Este projeto está sob a licença MIT — veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

**By [Rodrigo Martins](https://github.com/RodLeite) • StrixFy & Echo Academy**

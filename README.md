# IRHub (Incident Response Hub)

**Um sistema open source para registro, acompanhamento e aprendizado com incidentes de segurança.**

---

## Missão

Aumentar o número de controles de incidentes nas empresas, tornando esse processo **mais simples, acessível e padronizado**.

Nosso objetivo é **democratizar o acesso a ferramentas de gestão de incidentes**, permitindo que organizações — de qualquer porte — possam documentar, aprender e evoluir com base em seus próprios erros e experiências.

---

## Sobre o projeto

O `incident-tracker` é um projeto criado por um grupo de mentorados(as) da área de tecnologia e segurança da informação com apoio da comunidade Kensei.  
É uma iniciativa **100% aberta**, com o objetivo de gerar impacto social e profissional.

Com ele, empresas e times técnicos podem:

- Registrar e acompanhar incidentes de segurança ou falhas operacionais
- Rastrear ações executadas durante o incidente
- Anexar evidências, logs e arquivos
- Aprender com o processo através de lições aprendidas e análise de causa raiz
- Consultar histórico e gerar relatórios

---

## Funcionalidades (MVP)

- [ ] Registro de incidentes com campos estruturados
- [ ] Linha do tempo de ações
- [ ] Upload de evidências
- [ ] Campos de lições aprendidas e causa raiz
- [ ] Filtros por status e tipo
- [ ] Exportação de relatórios (CSV, PDF)
- [ ] Dashboard com estatísticas

---

## Tecnologias utilizadas

- **Frontend:** React + TailwindCSS
- **Backend:** Node.js + Express
- **Banco de dados:** SQLite (ou PostgreSQL)
- **Deploy:** Docker + Docker Compose

---

## Como rodar localmente

```bash
git clone https://github.com/kensei-cybersec-lab/incident-tracker.git
cd irhub
docker-compose up --build
```

Acesse: http://localhost:3000

## Público-alvo
Pequenas e médias empresas

Times de TI e Segurança

Cooperativas, ONGs e setores públicos que precisam gerenciar seus próprios incidentes

Estudantes e iniciantes que queiram aprender sobre gestão de incidentes

## Como contribuir
Este projeto é um convite à colaboração ativa:

Dê uma estrela ⭐ no repositório

Crie issues com sugestões ou problemas

Envie Pull Requests com melhorias

Ajude com testes e validações

Traduza a interface para outros idiomas

Compartilhe com sua rede!

## Licença
MIT License

## Créditos
Idealizado por José Menezes e mentorados da comunidade Kensei CyberSec Lab
Com o apoio do Instituto Vai na Web e Plataform Impact

## Impacto social
Este projeto busca reduzir a barreira de entrada para práticas de segurança, promovendo o uso de ferramentas acessíveis em contextos que historicamente não contam com estruturas caras ou sofisticadas.

Queremos ver mais empresas protegidas, mais profissionais preparados e mais histórias de sucesso documentadas.

---

Se quiser, posso:
- Criar o `CONTRIBUTING.md` com regras de contribuição
- Gerar o `Dockerfile` e `docker-compose.yml`
- Subir um repositório inicial com essa estrutura

Quer que eu prepare esse repositório todo já com base nesse README?

<div align="center">

# 🧭 Atlas Predições

**Estoque sob controle. Preço do diesel S-10 antes de ele acontecer.**

SaaS B2B que une gestão de estoque de combustível a um modelo próprio de
predição do preço do diesel S-10 — para quem compra litro não decidir no achismo.

<br/>

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-orange?style=for-the-badge)
![Modelo](https://img.shields.io/badge/modelo-proprietário-6C4AB6?style=for-the-badge)
![Licença](https://img.shields.io/badge/licença-proprietária-lightgrey?style=for-the-badge)

<br/>

`Python` · `Vue.js` · `Flutter` · `PostgreSQL` · `Docker` · `Cloudflare`

</div>

---

## 🎯 O problema

O diesel S-10 é uma das maiores linhas de custo de transportadoras, frotas,
cooperativas e postos — e o preço oscila semana a semana, puxado por câmbio,
petróleo, política de preços da refinaria e logística regional.

Na prática, quem compra combustível decide **duas coisas** toda semana:

- **Quanto** manter em estoque.
- **Quando** comprar.

Hoje essas duas decisões costumam ser tomadas na planilha, no feeling e no
preço de ontem. O resultado é estoque parado, compra no pico e margem
derretendo sem ninguém conseguir apontar onde.

## 💡 A solução

A **Atlas Predições** junta as duas pontas num só produto:

| | |
|---|---|
| 📦 **Controle de estoque** | Entradas, saídas, consumo e nível dos tanques em tempo real, com histórico e alertas de ruptura. |
| 📈 **Predição de preço** | Modelo proprietário que projeta o valor do diesel S-10 para as próximas janelas, a partir de séries históricas e indicadores de mercado. |
| 🧮 **Decisão de compra** | Estoque + previsão viram uma recomendação prática: comprar agora, segurar, ou quanto abastecer. |
| 📊 **Painéis e relatórios** | Custo médio por litro, economia acumulada e acerto do modelo, medidos ao longo do tempo. |

> O modelo é **proprietário e em evolução contínua** — cada previsão é
> registrada e comparada com o preço realizado, para que a acurácia seja
> auditável e não uma promessa de marketing.

---

## 🧱 Arquitetura & Stack

| Camada | Tecnologia |
|---|---|
| **Backend / APIs** | Python — microsserviços |
| **Frontend web** | Vue.js |
| **Mobile** | Flutter |
| **Banco de dados** | PostgreSQL (Neon) |
| **Storage** | Cloudflare R2 |
| **Containers** | Docker / Docker Compose |
| **Produção** | Cloudflare |
| **Homologação** | Oracle Cloud — Oracle Linux |

**Como trabalhamos:** Conventional Commits, revisão por Pull Request,
decisões de arquitetura registradas como ADRs e infraestrutura documentada
fase a fase.

---

## 👥 Time

| Pessoa | Responsabilidade |
|---|---|
| **Pablo De Oliveira** | Tech Lead · Frontend e Mobile |
| **Wendel** | Frontend |
| **Gabriela Lenz** | Frontend |
| **Wesley Barbaro** | Backend e DevOps |
| **João Mascarello** | Backend e DevOps |

---

## 📚 Repositórios

| Repositório | O que é |
|---|---|
| [**Documentacao**](https://github.com/Atitus-Startup-TCC/Documentacao) | Documentação técnica: plano de DevOps, infraestrutura, segurança, LGPD, ADRs e runbooks. |

---

<div align="center">

🚧 **Projeto em desenvolvimento ativo** — parte do TCC na Atitus Educação.

</div>

# Vai pra rua 🛡️

**Calendário Colaborativo de Eventos de Segurança da Informação**

Este é um projeto simples e comunitário com o objetivo de centralizar e listar os principais eventos presenciais de InfoSec que acontecerão no Brasil e no mundo em 2026.

A ideia é incentivar a sair de casa ("Ir pra rua"), fazer networking e compartilhar conhecimento presencialmente.

🔗 **Acesse o site:** [vaiprarua.github.io]

---

## 🤝 Como contribuir

Este portal depende da comunidade para se manter atualizado. Você pode ajudar de duas formas principais:

1.  **Adicionando novos eventos:** Viu um evento confirmado que não está na lista?
2.  **Removendo eventos passados:** O evento já aconteceu? Ajude a limpar a lista.

### Passo a passo

Todo o conteúdo do site é carregado a partir de um único arquivo: `events.json`. Você não precisa saber programar HTML ou CSS, apenas editar o texto.

1.  Faça um **Fork** deste repositório.
2.  Edite o arquivo `events.json`.
3.  Adicione o novo evento seguindo o padrão abaixo ou remova o bloco de um evento que já passou.
4.  Envie um **Pull Request (PR)**.

### Padrão do JSON

Ao adicionar um evento, mantenha estritamente este formato:

```json
{
  "title": "Nome do Evento",
  "location": "Cidade, Estado - Local Específico",
  "date": "Dia de Mês de 2026",
  "link": "[https://link-oficial-do-evento.com.br](https://link-oficial-do-evento.com.br)"
}

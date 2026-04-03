```markdown
# BypassMidd

**Universal Link Bypass Service**

![logo](https://github.com/KhaiDreams/WhoMessage/assets/70505025/49929a31-83f4-4025-b6e3-fffb274e08ed)


[Website](https://api-bypassers.onrender.com) | [Status](https://api-bypassers.onrender.com/status) | [API Docs](https://api-bypassers.onrender.com/docs)

---

## About

BypassMidd is a free and fast universal link bypass service. It supports over 50 link shortening platforms including Linkvertise, AdFly, Boost.ink, and Lootlabs.

## Features

- Bypass links from 50+ platforms
- Fast response time
- No personal data stored
- Public API available
- Real-time statistics
- Bot protection with Cloudflare Turnstile

## Supported Platforms

- Linkvertise
- AdFly
- Shorte.st
- Exe.io
- Earn.ink
- Ply.gg
- Boost.ink
- Lootlabs
- Platoboost
- Rekonise
- Workink
- Pastebin
- Rentry
- And 50+ more

## Quick Start

**Use the website:** https://api-bypassers.onrender.com

Just paste your link, complete the verification, and click Execute Bypass.

## API

### Authentication

Use the default API key: `freeApikey`

Header: `X-API-Key: freeApikey`

### Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| /api/bypass | POST | Bypass a link |
| /api/stats | GET | Global statistics |
| /health | GET | Health check |
| /supported | GET | List of supported services |

### Bypass Request

**URL:** `POST https://api-bypassers.onrender.com/api/bypass`

**Headers:**

```

Content-Type: application/json
X-API-Key: freeApikey

```

**Body:**

```json
{
  "url": "https://linkvertise.com/access/202348/example"
}
```

Response:

```json
{
  "success": true,
  "result": "https://bypassed-link.com/...",
  "time": 2.34
}
```

cURL Example

```bash
curl -X POST https://api-bypassers.onrender.com/api/bypass \
  -H "Content-Type: application/json" \
  -H "X-API-Key: freeApikey" \
  -d '{"url":"https://linkvertise.com/access/202348/example"}'
```

JavaScript Example

```javascript
fetch('https://api-bypassers.onrender.com/api/bypass', {
  method: 'POST',
  headers: {
    'Content-Type': 'application/json',
    'X-API-Key': 'freeApikey'
  },
  body: JSON.stringify({
    url: 'https://linkvertise.com/access/202348/example'
  })
})
.then(res => res.json())
.then(data => console.log(data));
```

Python Example

```python
import requests

response = requests.post(
    'https://api-bypassers.onrender.com/api/bypass',
    headers={'X-API-Key': 'freeApikey'},
    json={'url': 'https://linkvertise.com/access/202348/example'}
)
print(response.json())
```

Rate Limits

Tier Requests Period
Free 1,000 per day
Premium 10,000 per day
Developer 100,000 per day

Status

Current server status: Online

License

Private - All Rights Reserved

---

BypassMidd - Free Universal Link Bypass Service

```

---

# Português

```markdown
# BypassMidd

**Serviço Universal de Bypass de Links**

[Site](https://api-bypassers.onrender.com) | [Status](https://api-bypassers.onrender.com/status) | [Documentação da API](https://api-bypassers.onrender.com/docs)

---

## Sobre

BypassMidd é um serviço universal de bypass de links gratuito e rápido. Suporta mais de 50 plataformas de encurtamento de links, incluindo Linkvertise, AdFly, Boost.ink e Lootlabs.

## Funcionalidades

- Bypass de links de mais de 50 plataformas
- Resposta rápida em segundos
- Nenhum dado pessoal armazenado
- API pública disponível
- Estatísticas em tempo real
- Proteção contra bots com Cloudflare Turnstile

## Plataformas Suportadas

- Linkvertise
- AdFly
- Shorte.st
- Exe.io
- Earn.ink
- Ply.gg
- Boost.ink
- Lootlabs
- Platoboost
- Rekonise
- Workink
- Pastebin
- Rentry
- E mais de 50 outras

## Início Rápido

**Use o site:** https://api-bypassers.onrender.com

Basta colar seu link, completar a verificação e clicar em Executar Bypass.

## API

### Autenticação

Use a chave de API padrão: `freeApikey`

Cabeçalho: `X-API-Key: freeApikey`

### Endpoints

| Endpoint | Método | Descrição |
|----------|--------|-------------|
| /api/bypass | POST | Executar bypass de link |
| /api/stats | GET | Estatísticas globais |
| /health | GET | Verificar saúde do servidor |
| /supported | GET | Lista de serviços suportados |

### Requisição de Bypass

**URL:** `POST https://api-bypassers.onrender.com/api/bypass`

**Cabeçalhos:**

```

Content-Type: application/json
X-API-Key: freeApikey

```

**Corpo:**

```json
{
  "url": "https://linkvertise.com/access/202348/exemplo"
}
```

Resposta:

```json
{
  "success": true,
  "result": "https://link-bypassado.com/...",
  "time": 2.34
}
```

Exemplo com cURL

```bash
curl -X POST https://api-bypassers.onrender.com/api/bypass \
  -H "Content-Type: application/json" \
  -H "X-API-Key: freeApikey" \
  -d '{"url":"https://linkvertise.com/access/202348/exemplo"}'
```

Exemplo com JavaScript

```javascript
fetch('https://api-bypassers.onrender.com/api/bypass', {
  method: 'POST',
  headers: {
    'Content-Type': 'application/json',
    'X-API-Key': 'freeApikey'
  },
  body: JSON.stringify({
    url: 'https://linkvertise.com/access/202348/exemplo'
  })
})
.then(res => res.json())
.then(data => console.log(data));
```

Exemplo com Python

```python
**import requests

response = requests.post(
    'https://api-bypassers.onrender.com/api/bypass',
    headers={'X-API-Key': 'freeApikey'},
    json={'url': 'https://linkvertise.com/access/202348/exemplo'}
)
print(response.json())**
```

Limites de Requisição

Nível Requisições Período
Gratuito 1,000 por dia
Premium 10,000 por dia
Desenvolvedor 100,000 por dia

Status

Status atual do servidor: Online

Licença

Privado - Todos os direitos reservados

---

BypassMidd - Serviço Universal de Bypass de Links Gratuito

```

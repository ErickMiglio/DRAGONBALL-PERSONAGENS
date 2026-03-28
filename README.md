# Personagens Dragon Ball

Catálogo de personagens de Dragon Ball Z, GT e Super com suas transformações.

## Preview 

[dragonball-personagens-erickmiglio.vercel.app](https://dragonball-personagens-erickmiglio.vercel.app/)

Uma aplicação web que exibe todos os personagens das três séries principais de Dragon Ball com suas transformações específicas.

## Tecnologias

- **PHP** (Backend)
- **HTML5/CSS3** (Frontend)
- **Docker** (Containerização)
- **Vercel** (Hospedagem)

## Como Executar Localmente

### Pré-requisitos

- PHP 8.0 ou superior instalado
- Servidor local (PHP built-in server)

### Passo a Passo

1. Clone o repositório:
```bash
git clone <seu-repositorio>
cd Personagens_Dragon_Ball
```

2. Inicie o servidor PHP:
```bash
php -S localhost:8000 -t api
```

3. Abra o navegador:
```
http://localhost:8000
```

## Como Executar na Vercel

### Deploy Automático

1. Faça push do código para o GitHub
2. Acesse [vercel.com](https://vercel.com)
3. Clique em "Add New..." → "Project"
4. Importe seu repositório
5. Clique em "Deploy"

### Deploy Manual (Vercel CLI)

1. Instale a Vercel CLI:
```bash
npm i -g vercel
```

2. Faça login:
```bash
vercel login
```

3. Execute o deploy:
```bash
vercel
```
## Como Executar com Docker

### Pré-requisitos

- Docker instalado
- Docker Compose instalado

### Passo a Passo

1. Clone o repositório:
```bash
git clone <seu-repositorio>
cd Personagens_Dragon_Ball
```

2. Inicie o container:
```bash
docker-compose up -d
```

3. Acesse a aplicação:
```
http://localhost:8080
```

## Personalização

Os personagens estão definidos no array `$personagens` no arquivo `api/index.php`. Você pode adicionar novos personagens seguindo o formato:

```php
'Nome da Série' => [
    ['nome' => 'Nome do Personagem', 'transformacoes' => ['Transformação 1', 'Transformação 2']]
]
```

## Licença

MIT License

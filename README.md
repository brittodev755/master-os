# Master OS

## 💼 Descrição
Sistema operacional web completo desenvolvido em Laravel com funcionalidades avançadas de gestão, pagamentos e geração de documentos.

## 🚀 Tecnologias Utilizadas
- **Backend**: Laravel 11.9 (PHP 8.2+)
- **Frontend**: Livewire 3.5, AdminLTE
- **Pagamentos**: Gerencianet, Stripe
- **PDF**: DomPDF, TCPDF
- **Imagens**: Intervention Image
- **Build**: Vite, Webpack Mix
- **Containerização**: Docker

## 📦 Instalação

### Pré-requisitos
- PHP 8.2+
- Composer
- Node.js & NPM
- MySQL/PostgreSQL
- Docker (opcional)

### Instalação Local
```bash
# Clone o repositório
git clone <repository-url>
cd master-os

# Instale dependências PHP
composer install

# Instale dependências Node.js
npm install

# Configure o ambiente
cp .env.example .env
php artisan key:generate

# Configure o banco de dados
php artisan migrate

# Compile assets
npm run build

# Inicie o servidor
php artisan serve
```

### Instalação com Docker
```bash
# Build da imagem
docker build -t master-os .

# Execute o container
docker run -p 8000:8000 master-os
```

## 🎯 Funcionalidades
- **Sistema Operacional Web**: Interface completa tipo desktop
- **Gestão de Pagamentos**: Integração Stripe e Gerencianet
- **Geração de PDFs**: Relatórios e documentos automatizados
- **Processamento de Imagens**: Upload e manipulação avançada
- **Painel Administrativo**: Interface AdminLTE
- **API REST**: Endpoints para integração
- **Autenticação**: Sistema completo de usuários
- **Livewire**: Componentes reativos

## 🔧 Configuração
1. **Banco de Dados**: Configure no `.env`
2. **Pagamentos**: Configure chaves Stripe e Gerencianet
3. **Storage**: Configure permissões de storage
4. **SSL**: Configure certificados se necessário

## 📱 Interface
- **AdminLTE**: Interface administrativa moderna
- **Responsiva**: Adaptável a todos os dispositivos
- **Componentes**: Livewire para interatividade
- **Temas**: Customização visual avançada

## 🛡️ Segurança
- **Sanctum**: Autenticação API
- **CSRF Protection**: Proteção contra ataques
- **Validation**: Validação robusta de dados
- **Middleware**: Controle de acesso

## 🤝 Contribuição
Contribuições são bem-vindas! Abra uma issue ou envie um pull request.

## 📄 Licença
MIT License
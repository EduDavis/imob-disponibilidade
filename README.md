# Imob Disponibilidade - Sistema de Gestão de Unidades

Site responsivo para gerenciar disponibilidade de unidades imobiliárias com painel administrativo.

## 🎯 Funcionalidades

- **Visualização em Caixa (Grid)**: Visualização por empreendimento e bloco
- **Visualização em Linha (Tabela)**: Lista completa com todos os detalhes
- **Filtros Avançados**: Por empreendimento, bloco, status e busca por unidade
- **Masterplans**: Visualização de plantas dos condomínios
- **Painel Admin**: Edição de status, preços e informações de corretores
- **Responsivo**: Funciona perfeitamente em desktop e mobile
- **Dados Locais**: Salvos automaticamente no navegador

## 📊 Dados

- **4 Empreendimentos**: Grumari, Praia do Pontal, Prainha, Reserva
- **65 Unidades**: Com preços, status e informações técnicas
- **4 Masterplans**: Plantas dos condomínios

## 🔐 Acesso Admin

- **Email**: admin@imobdisponibilidade.com
- **Senha**: admin123

## 🚀 Deploy no Netlify

### Opção 1: Drag & Drop (Mais Fácil)

1. Acesse https://netlify.com
2. Faça login ou crie uma conta
3. Arraste a pasta `/home/ubuntu/imob-site` para a área de drop
4. Pronto! Seu site estará online

### Opção 2: Git + Netlify

1. Faça push dos arquivos para um repositório GitHub
2. Conecte o repositório ao Netlify
3. Netlify fará o deploy automaticamente

### Opção 3: CLI do Netlify

```bash
npm install -g netlify-cli
cd /home/ubuntu/imob-site
netlify deploy --prod
```

## 📁 Estrutura de Arquivos

```
imob-site/
├── index.html          # Site completo (HTML + CSS + JS)
├── data.json           # Dados das unidades
├── masterplans/        # Imagens dos masterplans
│   ├── reserva.jpg
│   ├── prainha.jpg
│   ├── grumari.jpg
│   └── praia-do-pontal.png
├── netlify.toml        # Configuração do Netlify
└── README.md           # Este arquivo
```

## 💾 Dados

Os dados são salvos no **LocalStorage** do navegador. Isso significa:
- As alterações feitas no admin são salvas automaticamente
- Os dados persistem mesmo após fechar o navegador
- Cada navegador/dispositivo tem seus próprios dados

Para sincronizar dados entre dispositivos, será necessário integrar um backend/banco de dados.

## 🛠️ Tecnologias

- HTML5
- CSS3
- JavaScript Vanilla
- LocalStorage API

## 📱 Responsividade

O site é totalmente responsivo e funciona em:
- Desktop (1920px+)
- Tablet (768px - 1024px)
- Mobile (até 768px)

## 🎨 Cores

- **Verde (#22c55e)**: Disponível
- **Amarelo (#fbbf24)**: Negociação
- **Vermelho (#ef4444)**: Vendido

---

**Desenvolvido com ❤️ para gestão imobiliária**

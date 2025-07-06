# SGBov Landing Page

Esta é a landing page oficial do SGBov - Sistema de Gestão de Bovinos, hospedada no Cloudflare Pages.

## 🚀 Como Publicar

### 1. Configuração do GitHub
- Faça push do código para o repositório
- A pasta `web/` deve estar na raiz do projeto

### 2. Configuração do Cloudflare Pages
1. Acesse [Cloudflare Pages](https://pages.cloudflare.com/)
2. Conecte seu repositório GitHub
3. Configure:
   - **Source**: GitHub
   - **Repository**: seu-repositorio/sgbov
   - **Branch**: main
   - **Build settings**:
     - **Framework preset**: None
     - **Build command**: (deixe vazio)
     - **Build output directory**: web
     - **Root directory**: (deixe vazio)

### 3. Domínio Personalizado (Opcional)
- Configure um domínio personalizado em Settings > Custom domains
- Exemplo: `sgbov.com` ou `www.sgbov.com`

## 📁 Estrutura de Arquivos

```
web/
├── index.html          # Página principal
├── _headers           # Configurações de segurança
├── assets/            # Imagens e recursos
│   ├── favicon.png
│   ├── og-image.jpg
│   └── twitter-image.jpg
└── README.md          # Esta documentação
```

## 🎨 Personalização

### Cores do Tema
- **Primária**: #129f0c (Verde)
- **Secundária**: #054706 (Verde escuro)
- **Fundo**: #F8F8F8 (Cinza claro)
- **Texto**: #1F2036 (Azul escuro)

### Links para Atualizar
- **Download do App**: Substitua `#download` pelos links reais
- **Demo**: Substitua `#demo` pelo link do vídeo demo
- **Contato**: Adicione links reais no footer

## 📱 SEO e Performance

### Meta Tags Configuradas
- ✅ Title otimizado
- ✅ Description para SEO
- ✅ Open Graph para redes sociais
- ✅ Twitter Cards
- ✅ Favicon

### Performance
- ✅ CSS otimizado
- ✅ JavaScript eficiente
- ✅ Imagens otimizadas
- ✅ Cache configurado

## 🔧 Manutenção

### Atualizações Frequentes
1. **Preços dos planos**: Edite em `index.html`
2. **Estatísticas**: Atualize números reais
3. **Depoimentos**: Adicione feedback de usuários reais
4. **Links**: Mantenha links atualizados

### Monitoramento
- Use Google Analytics (adicionar código)
- Monitore Core Web Vitals
- Acompanhe conversões

## 🚨 Troubleshooting

### Problemas Comuns
1. **Página não carrega**: Verifique configuração do Cloudflare Pages
2. **Imagens não aparecem**: Confirme se estão na pasta `assets/`
3. **Links quebrados**: Teste todos os links após deploy

### Logs
- Cloudflare Pages mostra logs de build
- Console do navegador para erros JavaScript
- Network tab para problemas de carregamento

## 📞 Suporte

Para dúvidas sobre a landing page:
- **Documentação**: Este README
- **Código**: Repositório GitHub
- **Deploy**: Cloudflare Pages Dashboard

---

**Última atualização**: Dezembro 2024  
**Versão**: 1.0  
**Autor**: Equipe SGBov 
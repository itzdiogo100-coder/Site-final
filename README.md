# Transformación GLP-1 - GitHub Pages

Landing page de vendas para o curso "Activación Natural de GLP-1" hospedada no GitHub Pages.

---

## 📋 Instruções de Instalação no GitHub Pages

### Passo 1: Criar um Repositório no GitHub

1. Acesse [github.com](https://github.com) e faça login
2. Clique em **"New"** para criar um novo repositório
3. **Nome do repositório:** `transformacion-glp1` (ou qualquer nome que desejar)
4. **Descrição:** "Landing page - Transformación GLP-1"
5. Escolha **Public** (para que GitHub Pages funcione)
6. Clique em **"Create repository"**

### Passo 2: Fazer Upload dos Arquivos

**Opção A: Via GitHub Web Interface (Mais Fácil)**

1. No seu novo repositório, clique em **"Add file"** → **"Upload files"**
2. Selecione **TODOS os arquivos** desta pasta:
   - `index.html`
   - Pasta `assets/`
   - Pasta `images/`
   - Arquivo `.nojekyll`
3. Clique em **"Commit changes"**

**Opção B: Via Git Command Line (Mais Rápido)**

```bash
# Clone o repositório
git clone https://github.com/SEU_USUARIO/transformacion-glp1.git
cd transformacion-glp1

# Copie todos os arquivos para esta pasta
# (substitua os arquivos existentes)

# Faça o commit
git add .
git commit -m "Upload landing page Transformación GLP-1"
git push origin main
```

### Passo 3: Ativar GitHub Pages

1. Vá para **Settings** do seu repositório
2. No menu esquerdo, clique em **"Pages"**
3. Em **"Source"**, selecione **"Deploy from a branch"**
4. Em **"Branch"**, escolha **"main"** (ou a branch que você usou)
5. Clique em **"Save"**
6. Aguarde 1-2 minutos

### Passo 4: Seu Site Estará Online! 🎉

Seu site estará disponível em:
```
https://SEU_USUARIO.github.io/transformacion-glp1
```

Exemplo:
```
https://joao-silva.github.io/transformacion-glp1
```

---

## 📁 Estrutura de Arquivos

```
transformacion-glp1/
├── index.html              ← Página principal (ESSENCIAL)
├── .nojekyll              ← Arquivo especial para GitHub Pages (ESSENCIAL)
├── assets/
│   ├── index-CEfinuLD.js  ← JavaScript compilado
│   └── index-DFvYkCuM.css ← CSS compilado
└── images/
    ├── hero-transformation.jpg
    ├── woman-fitness.jpg
    ├── healthy-meal.jpg
    ├── exercise-woman.jpg
    ├── inflammation.jpg
    ├── meal-prep.jpg
    ├── transformation-before-after.jpg
    └── course-mockup.jpg
```

---

## ✅ Arquivos Essenciais

| Arquivo | Descrição | Obrigatório |
|---------|-----------|-------------|
| `index.html` | Página HTML principal | ✅ SIM |
| `.nojekyll` | Arquivo vazio que desativa Jekyll | ✅ SIM |
| `assets/` | Pasta com CSS e JS compilados | ✅ SIM |
| `images/` | Pasta com todas as imagens | ✅ SIM |

---

## ⚙️ Configurações Adicionais

### 1. Configurar Domínio Personalizado (Opcional)

Se você comprou um domínio (ex: transformacion-glp1.com):

1. Vá para **Settings** → **Pages**
2. Em **"Custom domain"**, digite seu domínio
3. Clique em **"Save"**
4. Configure os nameservers do seu domínio para apontar para GitHub Pages

**Instruções para GoDaddy:**
- Vá para GoDaddy > DNS Settings
- Procure por "Nameservers"
- Aponte para:
  - `ns-1234.awsdns-12.com` (ou similar do GitHub)

### 2. Ativar HTTPS (Automático)

GitHub Pages ativa HTTPS automaticamente. Se não aparecer:

1. Vá para **Settings** → **Pages**
2. Marque a opção **"Enforce HTTPS"**
3. Aguarde alguns minutos

### 3. Adicionar Pixel de Rastreamento (Já Incluído)

O site já possui:
- ✅ **Facebook Pixel** (ID: 1932432744375812)
- ✅ **Google Tag Manager** (ID: GTM-TKQMMDGQ)

Nenhuma configuração adicional é necessária!

---

## 🔍 Verificação de Compatibilidade

Este site foi preparado com:

✅ **Paths Relativos** - Funciona em qualquer URL
✅ **Sem Dependências de Servidor** - Apenas HTML/CSS/JS
✅ **Arquivo .nojekyll** - Desativa processamento Jekyll
✅ **Imagens Otimizadas** - Carregam rapidamente
✅ **Responsive Design** - Funciona em mobile/tablet/desktop
✅ **Facebook Pixel** - Rastreamento de visitantes
✅ **Google Tag Manager** - Análise de eventos

---

## 🐛 Troubleshooting

### Problema: Site não carrega

**Solução:**
1. Verifique se o arquivo `.nojekyll` está presente
2. Verifique se `index.html` está na raiz
3. Aguarde 5 minutos para GitHub Pages processar

### Problema: Imagens não carregam

**Solução:**
1. Verifique se a pasta `images/` está presente
2. Verifique se os paths em `index.html` são relativos (`./images/`)
3. Limpe o cache do navegador (Ctrl+Shift+Delete)

### Problema: CSS/JS não carregam

**Solução:**
1. Verifique se a pasta `assets/` está presente
2. Verifique se os paths em `index.html` são relativos (`./assets/`)
3. Abra DevTools (F12) e procure por erros 404

### Problema: Site carrega mas está quebrado

**Solução:**
1. Abra DevTools (F12)
2. Vá para "Console"
3. Procure por erros em vermelho
4. Verifique os paths dos arquivos

---

## 📞 Suporte

Se encontrar problemas:

1. Verifique se todos os arquivos foram enviados
2. Confirme que o repositório é **Public**
3. Aguarde 5 minutos para GitHub Pages processar
4. Limpe o cache do navegador
5. Tente em outro navegador

---

## 📊 Próximos Passos

1. **Atualizar links de compra:**
   - Abra `index.html` em um editor
   - Procure por `https://pay.hotmart.com/M103046692E`
   - Substitua pelo seu link real do Hotmart

2. **Monitorar conversões:**
   - Acesse Facebook Ads Manager
   - Vá para "Eventos"
   - Configure rastreamento de compras

3. **Otimizar campanhas:**
   - Use Google Analytics para ver dados
   - Teste diferentes anúncios
   - Melhore o copy baseado em resultados

---

## 📝 Notas Importantes

- ⚠️ **NÃO mude** a estrutura de pastas
- ⚠️ **NÃO delete** o arquivo `.nojekyll`
- ⚠️ **NÃO renomeie** os arquivos em `assets/`
- ✅ **PODE** editar o conteúdo do `index.html`
- ✅ **PODE** adicionar novas imagens na pasta `images/`

---

**Versão:** 1.0
**Data:** 29 de Novembro de 2025
**Status:** ✅ Pronto para GitHub Pages

# Publicar o Rotina no GitHub Pages — passo a passo

Os arquivos prontos estão em: **`Downloads\LifeStyle\rotina-site\`**
São 6: `index.html`, `manifest.webmanifest`, `sw.js`, `icon.svg`, `README.md`, `.nojekyll`

---

## 1. Criar conta no GitHub

1. Abra **github.com/signup**
2. E-mail → senha → **nome de usuário** (⚠️ isso vira parte do endereço do app: `SEUUSUARIO.github.io/rotina`)
3. Confirme o e-mail. Não precisa cartão nem nada.

## 2. Instalar o GitHub Desktop

1. Abra **desktop.github.com** → baixe → instale
2. Abra o programa → **Sign in to GitHub.com** → entre com a conta que você criou

## 3. Criar o repositório

1. GitHub Desktop → menu **File → New repository**
2. **Name:** `rotina`
3. **Local path:** escolha uma pasta qualquer (ex.: Documentos)
4. Pode deixar o resto como está → **Create repository**

## 4. Copiar os arquivos do app

1. GitHub Desktop → menu **Repository → Show in Explorer** (abre a pasta `rotina` que ele criou)
2. Abra também `Downloads\LifeStyle\rotina-site\`
3. **Copie os 6 arquivos** de `rotina-site` para dentro da pasta `rotina`
   - Substitua o `README.md` se ele perguntar
   - O `.nojekyll` é um arquivo "sem nome". Se ele não aparecer: no Explorer, aba **Exibir → Mostrar → Itens ocultos**. Se mesmo assim não rolar copiar, tudo bem, ele é opcional.

## 5. Publicar

1. Volte no **GitHub Desktop** — vai aparecer a lista de arquivos novos à esquerda
2. Embaixo, no campo **Summary**, escreva: `primeira versão`
3. Botão **Commit to main**
4. Botão azul no topo: **Publish repository**
   - ⚠️ **DESMARQUE** "Keep this code private" (o Pages grátis exige repositório público)
   - **Publish repository**

## 6. Ligar o GitHub Pages

1. GitHub Desktop → menu **Repository → View on GitHub** (abre o navegador)
2. Na página do repositório: aba **Settings** (engrenagem, no topo)
3. Menu lateral esquerdo: **Pages**
4. Em **Source**: escolha **Deploy from a branch**
5. Em **Branch**: escolha `main` e a pasta `/ (root)` → **Save**
6. Espere 1–2 minutos e atualize a página. Vai aparecer:
   **"Your site is live at https://SEUUSUARIO.github.io/rotina/"**

## 7. Instalar no celular

1. Abra `https://SEUUSUARIO.github.io/rotina/` no celular
   - **Android/Chrome:** menu ⋮ → **Instalar app** (ou "Adicionar à tela inicial")
   - **iPhone/Safari:** botão compartilhar → **Adicionar à Tela de Início**
2. Abra pelo ícone → **sem barra de URL** 🎉

## 8. Trazer seus dados do app antigo

1. **Antes de parar de usar**, abra o app antigo (link da claude.ai) → **Mais → Backup dos dados → Copiar**
2. No app novo (instalado) → **Mais → Backup dos dados** → cole no campo → **Restaurar**

Feito isso, pode aposentar o link da claude.ai.

## 9. Atualizações futuras

Eu te mando os arquivos novos → você substitui na pasta `rotina` → GitHub Desktop → **Commit to main** → **Push origin**. No ar em ~1 min. O app se atualiza sozinho quando você abre com internet.

---

**Nesta fase os dados ficam separados por aparelho.** Sincronizar celular ↔ PC é a próxima etapa (Firebase). Enquanto isso, o Backup/Restaurar é a ponte.

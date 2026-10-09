# Clinical Torres — React + Vite

## Adicionar ao GitHub
1. Extraia este ZIP.
2. No repositório clinical-torres, escolha Add file > Upload files.
3. Envie o conteúdo da pasta extraída: src, public, index.html, package.json, README.md e render.yaml.
4. O package.json deve ficar na raiz do repositório. Não envie apenas o ZIP.
5. Clique em Commit changes.

## Rodar no computador
Instale Node.js 22.13 ou superior. Abra a pasta no VS Code e execute:

```sh
npm install
npm run dev
```

## Publicar no Render
Crie um Static Site conectado ao repositório clinical-torres.
- Branch: main
- Build Command: npm install && npm run build
- Publish Directory: dist

Em Redirects/Rewrites, adicione:
- Source: /*
- Destination: /index.html
- Action: Rewrite

Essa regra permite abrir e atualizar as páginas internas.
O arquivo render.yaml também permite publicar como Blueprint.

## Dados da clínica
Em src/clinic.tsx, preencha a variável phone com o WhatsApp oficial, somente números, incluindo 55 e DDD. Exemplo de formato: 5581999999999.
Os profissionais e os depoimentos estão identificados como exemplos. Substitua pelos dados reais autorizados antes de divulgar.

# Apps Landing Pages

Repositório central de landing pages estáticas dos aplicativos, sem dependência de build ou rastreamento por padrão.

## Estrutura

```text
apps-landing-pages/
├── .nojekyll
├── index.html                 # Portal dos aplicativos
├── casa-em-dia/
│   ├── index.html             # Landing page Casa em Dia
│   ├── icone.png              # Identidade visual
│   └── tela-inicio.webp       # Screenshot real
└── README.md
```

## Publicação no GitHub Pages

1. Crie um repositório **público** chamado `apps-landing-pages` no usuário `FeeSantana`, com `README` inicial para criar a branch `main`.
2. Envie os arquivos e diretórios desse pacote à **raiz** do repositório, preservando a estrutura.
3. Em **Settings → Pages → Build and deployment**, selecione **Deploy from a branch**.
4. Selecione **main** e **/(root)** e salve.
5. Após o deploy, acesse:
   - Portal: `https://feesantana.github.io/apps-landing-pages/`
   - Casa em Dia: `https://feesantana.github.io/apps-landing-pages/casa-em-dia/`
6. No Instagram Android, teste a landing page pelo navegador interno e toque em `Baixar grátis na Google Play`.
7. Se a Play Store não abrir, use o botão **Copiar link de instalação** e abra no Chrome. **Não troque o link da bio antes dos testes.**

## Próximos aplicativos

Crie uma pasta por aplicativo, por exemplo `outro-app/index.html`. Para usar no portal, inclua um card no `index.html` da raiz. Use caminhos relativos (`icone.png` etc.) para manter a hospedagem independente do domínio.

## Observações

- O site é público e inteiramente estático. Não adicione segredos, tokens, nem dados privados.
- Sem analytics por padrão; planejar medição e política de privacidade antes de incluir scripts terceiros.
- O link principal da Google Play é `https://play.google.com/store/apps/details?id=com.ofeeh.casaemdia`.
- Os repositórios `feesantana.github.io` (app-ads.txt) e `apps-public-docs` (políticas) **não precisam ser modificados**.
- GitHub Pages não é garantia de contorno de bloqueios do navegador interno do Instagram; teste com o celular.

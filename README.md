# 💕 Para o Amor da Minha Vida

Um site romântico dedicado à pessoa mais especial da sua vida!

## ✨ Funcionalidades

- 📅 **Contador de Dias** - Acompanha quantos dias vocês estão juntos desde 14/06/2026
- 🎵 **Música Romântica** - Toque música com animação de corações voadores
- 💬 **Pensamentos Aleatórios** - Diferentes frases românticas a cada clique
- 📷 **Galeria de Fotos** - Espaço para suas fotos mais lindas
- 💌 **Carta Romântica** - Uma declaração pessoal e emocionante
- 🎨 **Design Neon Rosa** - Tema escuro com efeitos luminosos

## 🚀 Como Usar

1. **Abra o arquivo `index.html` no seu navegador**
2. **Adicione suas fotos:** Substitua os placeholders (📷) pelas URLs de suas fotos
3. **Personalize o texto:** Edite a carta e as frases conforme desejar
4. **Compartilhe:** Envie o link para quem você ama

## 📸 Adicionando Fotos

Abra o `index.html` com um editor de texto e procure por:

```html
<div class="foto-box foto-larga placeholder">
    <span>📷</span>
</div>
```

Substituir para:

```html
<div class="foto-box foto-larga">
    <img src="URL_DA_SUA_FOTO" alt="Descrição">
</div>
```

## 🎵 Alterando a Música

Procure por:

```html
<audio id="musica" src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" loop></audio>
```

E substitua a URL pela sua música favorita!

## 💡 Dicas

- Use URLs de imagens do imgur, Google Photos ou qualquer host de imagens
- Personalize as frases românticas no array `frases` do JavaScript
- Ajuste as cores no CSS se preferir outro tema
- O site é totalmente responsivo (funciona bem no celular)

## 🌐 Publicar Online (GitHub Pages)

1. Este repositório já está pronto para publicar no GitHub Pages
2. Vá em **Settings > Pages**
3. Selecione **Branch: main**
4. Seu site estará em: `https://carlosecibeshow.github.io/love-letter-site`

---

**Feito com ❤️ para alguém muito especial**
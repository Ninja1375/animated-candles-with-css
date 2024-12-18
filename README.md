# Animated Candles with CSS

Este projeto apresenta uma animação criativa de velas utilizando HTML5 e CSS3 puro, com elementos interativos e visuais que incluem olhos piscando, chamas dançantes e efeitos de fundo dinâmicos.

## 🔥 Destaques da Animação

Velas com expressões faciais animadas
Os olhos piscam em intervalos realistas, criando uma expressão divertida e envolvente.

**Chama da vela animada**

O movimento sutil da chama simula o efeito natural do fogo utilizando keyframes CSS.

**Efeitos de fumaça**

A fumaça se dissipa com animações suaves, trazendo mais realismo ao projeto.

**Transições de fundo**

Um fundo dinâmico com cores em transição contínua, proporcionando uma experiência visual agradável.

## 🚀 Tecnologias Utilizadas

<a href="https://programartudo.blogspot.com/2024/11/html-tudo-o-que-precisa-para-comecar.html" target="_blank"><img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="40" height="40"/></a> 
<a href="https://programartudo.blogspot.com/2024/11/css-como-dar-estilo-ao-teu-website.html" target="_blank"><img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="40" height="40"/></a>

**HTML5:** Estrutura básica do projeto.

**CSS3:** Estilização, keyframes e animações puras.

## 📂 Estrutura do Projeto

A organização dos arquivos é simples e direta:

```plaintext
animated-candles-with-css/
│-- index.html # Estrutura HTML do projeto
│-- style.css # Estilização e animações CSS
└-- README.md # Documentação do projeto
```

## 🎥 Pré-visualização

Para visualizar a animação:

Faça o clone do projeto:

   ```bash
   git clone https://github.com/Ninja1375/animated-candles-with-css.git
   ```

Abra o arquivo `index.html` em qualquer navegador moderno.

## 🛠️ Como Funciona

Principais Animações

**Olhos Piscando**

Criado com `@keyframes` alternando a opacidade e altura dos olhos.

```css
@keyframes blink-eyes {
    0%, 100% { transform: scaleY(1); }
    50% { transform: scaleY(0.1); }
}
```

**Movimento da Chama**

Simula o balanço natural do fogo.

```css
@keyframes dance-fire {
    0%, 100% { transform: rotate(0deg); }
    50% { transform: rotate(2deg); }
}
```

**Fumaça Subindo**

Animação suave movendo elementos para cima e para os lados.

```css
@keyframes move-smoke {
    0% { opacity: 1; transform: translateY(0); }
    100% { opacity: 0; transform: translateY(-50px); }
}
```

**Fundo Dinâmico**

Alterna entre cores usando `@keyframes`.

```css
@keyframes change-background {
    0% { background-color: #fef3d3; }
    50% { background-color: #ffccbc; }
    100% { background-color: #fef3d3; }
}
```

## 🎨 Captura de Tela

![Velas Animadas com CSS ](https://github.com/user-attachments/assets/3d61d93f-0708-4f29-9bd8-1bcc59145dae)


## 💡 Inspiração

Este projeto foi desenvolvido para demonstrar o poder do **CSS puro** na criação de animações interativas e criativas.

Se gostou do projeto, deixe uma estrela ⭐ no repositório!

## Apoie-me:
<a href="https://buymeacoffee.com/antonio13" target="_blank"><img loading="lazy" src="https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20coffee&emoji=&slug=seu_nome_de_usuario&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff" width="120" height="120"></a>  <a href="https://www.paypal.com/donate/?hosted_button_id=DN574F28FYUNG" target="_blank"><img loading="lazy" src="https://upload.wikimedia.org/wikipedia/commons/b/b5/PayPal.svg" width="120" height="120"></a>

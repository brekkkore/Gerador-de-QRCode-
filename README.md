# 📱 Gerador de QR Code com API

Um gerador de QR Code simples, dinâmico e responsivo desenvolvido em JavaScript puro (Vanilla JS), HTML e CSS. O projeto consome uma API externa para converter qualquer texto ou URL inserido pelo usuário em um código QR instantaneamente.

---

## 🚀 Funcionalidades

- **Geração em Tempo Real:** Cria o QR Code instantaneamente ao inserir o texto/link e clicar no botão (ou pressionar *Enter*).
- **Limpeza Automática:** O QR Code gerado é ocultado automaticamente se o campo de texto for limpo.
- **Feedback Visual:** Estado de carregamento no botão durante o consumo da API.
- **Design Responsivo:** Adaptado para dispositivos móveis e desktops.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica da página.
- **CSS3:** Estilização, layout (Flexbox/Grid) e animações.
- **JavaScript (Vanilla):** Manipulação do DOM e consumo da API via `fetch`.
- **API Extensão:** [QR Code Generator API](https://goqr.me/api/) (ou a API utilizada no seu projeto).

---

## 📦 Como Funciona

1. O usuário digita um texto ou cola um link no campo de entrada.
2. O JavaScript captura o valor digitado e faz uma requisição para a API passando o conteúdo na URL:
   `https://api.qrserver.com/v1/create-qr-code/?size=150x150&data={CONTEUDO}`
3. A API retorna a imagem do QR Code gerado.
4. O JavaScript exibe a imagem no elemento container da página.

---

## 🔧 Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)

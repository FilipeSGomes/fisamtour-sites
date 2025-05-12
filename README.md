# Criar o README.md com instruções para subir no GitHub Pages
readme_content = """
# FISAM Tour - Landing Page

Landing page estática e responsiva para a agência de viagens **FISAM Tour**, com foco em luxo, elegância e experiências exclusivas.

## ✨ Funcionalidades

- Design clean com cores da marca (verde oliva e dourado)
- Missão institucional da FISAM
- Carrossel com destinos incríveis para 2025
- Depoimentos de clientes
- Formulário de orçamento com integração ao WhatsApp
- Botão fixo para contato via WhatsApp

## 📁 Estrutura de arquivos


## 🌐 Publicar no GitHub Pages

1. Crie um repositório no GitHub com o nome `fisam-tour-site`
2. Faça o upload de todos os arquivos da pasta (incluindo o `index.html`, imagens e este `README.md`)
3. No GitHub, vá em **Settings** > **Pages**
4. Em “Source”, selecione a branch `main` e a pasta `/root` (ou `/` se estiver disponível)
5. Clique em “Save”
6. Acesse o site em `https://seu-usuario.github.io/fisam-tour-site/`

## 📞 Integração com WhatsApp

O botão e o formulário estão configurados para o número fictício `+55 81 99999-9999`.
Altere o número nos seguintes locais do `index.html`:

- Linha do botão fixo:
```html
<a class="whatsapp-button" href="https://wa.me/5581999999999" target="_blank">



const url = `https://wa.me/5581999999999?text=...`;

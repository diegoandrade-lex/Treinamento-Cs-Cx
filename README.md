# Trilha de Formação em Experiência do Cliente — LEX

Programa interno de treinamento em **CS/CX para escritórios jurídicos**, no formato de aula web
(EAD autoinstrucional). Cada módulo tem conteúdo, resumo e uma prova com correção automática e
exportação de resultado.

## Conteúdo

- `index.html` — página inicial da trilha (lista dos módulos)
- `modulo-01.html` — Módulo 01: Fundamentos de CS/CX no Jurídico (conteúdo + prova)

O site é 100% estático (HTML + CSS + JavaScript no navegador). Não precisa de build nem servidor.

## Como colocar no ar (GitHub Pages) — ~2 minutos

1. Crie um repositório **público** (ex.: `treinamento-cs-cx`).
2. Envie estes arquivos para o repositório (`index.html`, `modulo-01.html`, `README.md`).
3. No repositório: **Settings → Pages**.
4. Em **Build and deployment → Source**, escolha **Deploy from a branch**.
5. Em **Branch**, selecione **main** e a pasta **/ (root)** e clique **Save**.
6. Aguarde ~1–10 min. O endereço aparece no topo da página:
   `https://SEU-USUARIO.github.io/treinamento-cs-cx/`

A página inicial abre a trilha; o botão "Começar" leva ao Módulo 01.

## Como adicionar os próximos módulos

1. Duplique `modulo-01.html` como `modulo-02.html` e substitua o conteúdo.
2. No `index.html`, no card do Módulo 02, troque a `<div class="mod off">` por
   `<a class="mod on" href="modulo-02.html">` e o texto "Disponível em breve" pelo botão
   `<span class="go">Começar →</span>`.
3. Faça commit. O site atualiza sozinho.

## Observação sobre dados (LGPD)

A prova coleta **nome e CPF** apenas para controle de conclusão e gera um arquivo local (CSV)
que o aluno baixa. Nenhum dado é enviado para servidor. Se quiser controle centralizado
automático, o recomendado é ligar a prova a um formulário (ex.: Google Forms) com acesso restrito.

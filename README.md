# CR Drive — Downloads

Use um canal privado do seu Telegram como drive de arquivos no Windows e no celular.

**[⬇ Baixar a versão mais recente](https://github.com/cleitonrios/cr-drive-releases/releases/latest)** — baixe o arquivo `CR Drive Setup x.y.z.exe` e execute.

- O Windows pode mostrar "O Windows protegeu o computador" (o instalador não é assinado). Clique em **Mais informações → Executar assim mesmo**.
- Depois de instalado, o CR Drive **se atualiza sozinho** quando sai uma versão nova.

## Primeiro uso
1. Acesse https://my.telegram.org, entre com seu número, abra **API development tools** e crie um app (qualquer nome).
2. Cole o **api_id** e o **api_hash** no CR Drive.
3. Entre com QR code ou telefone. O app cria um canal privado **"CR Drive"** na sua conta.

## No celular (Android e iPhone)
Abra **https://cr-drive.vercel.app** no celular e entre com o mesmo api_id/api_hash e telefone. Para instalar:
- **Android (Chrome):** menu ⋮ → **Instalar app**.
- **iPhone (Safari):** Compartilhar → **Adicionar à Tela de Início**. Faça o login dentro do app instalado (no iPhone ele não compartilha o login com o Safari).

O app do celular fala direto com o Telegram: funciona com o PC desligado. Mantenha-o aberto enquanto envia arquivos.

## Seus arquivos são só seus
O CR Drive foi feito para ser seguro:

- **Cada um usa a própria conta.** Você cria sua chave em my.telegram.org e entra com o seu Telegram. Os arquivos vão para um canal privado na sua conta: ninguém mais tem acesso a eles, nem quem criou o app.
- **Não há servidor no meio.** O app fala direto com o Telegram. Nenhum arquivo, senha ou login passa por outro lugar.
- **Seu login fica só nos seus aparelhos.** No PC, a sessão do Telegram é guardada criptografada pelo Windows e só o seu usuário do Windows consegue abri-la. No celular, ela fica só no app instalado.
- **O app do PC só atende o seu computador.** Ele não aceita conexões de fora do seu PC e exige uma chave secreta que muda a cada vez que ele abre. Outros sites abertos no navegador não conseguem usá-lo.

**Recomendação:** ative a **verificação em duas etapas** no seu Telegram (**Configurações → Privacidade e Segurança → Verificação em duas etapas**). Assim, sua conta fica protegida com uma senha extra mesmo que alguém consiga o código que chega por SMS.

## Arquivos grandes
O Telegram aceita até 2 GB por arquivo. O CR Drive divide arquivos maiores em partes automaticamente (até 100 GB). Para você, continua sendo um arquivo só.

Este repositório contém apenas os instaladores.

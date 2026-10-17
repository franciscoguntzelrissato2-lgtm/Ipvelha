# Meta Velha

Jogo da velha para iPhone, criado com HTML/CSS/JavaScript e Capacitor. O fluxo do Codemagic cria o projeto nativo iOS no Mac de compilação e gera o IPA assinado quando os ativos de assinatura Apple estiverem configurados.

## Compilar no Codemagic

1. Envie esta pasta para um repositório GitHub.
2. No Codemagic, conecte o repositório e selecione o workflow `Meta Velha iOS`.
3. Configure a assinatura iOS e os dispositivos/perfis correspondentes no Codemagic.
4. Inicie a compilação e baixe o IPA em Artifacts.

O identificador `com.metavelha.game` é o Bundle ID inicial. Ele deve ser igual ao Bundle ID registrado na conta Apple usada para assinar.

# Instalação

## Antes de Começar

Confira em **Sobre Este Mac** se o computador tem chip Apple e macOS 14 ou
mais recente. Este instalador não tem versão Intel.

A beta 0.1 usa uma assinatura local. Ela **não** tem certificado Developer ID
nem notarização da Apple. Uma assinatura local íntegra não significa que o
Gatekeeper de outro Mac aceitará o aplicativo. Hospedar o arquivo no GitHub
não altera essa condição.

Se o macOS impedir a abertura, não desligue as proteções do sistema nem
instale certificados recebidos por mensagem. Consulte as
[orientações oficiais da Apple](https://support.apple.com/pt-br/102445)
e relate o bloqueio. A versão com assinatura reconhecida ainda está pendente.

## Instalar o Aplicativo

1. Baixe o `.dmg` na [release da beta](https://github.com/Devliviax/LessonStudio/releases/tag/v0.1.0-beta.1).
2. Abra-o e arraste **LessonStudio** para **Aplicativos**.
3. Ejete o volume **LessonStudio Beta**.
4. Abra o aplicativo instalado, não a cópia dentro do instalador.

Se já houver uma instalação, feche o aplicativo antes de substituí-la e
mantenha uma única cópia de uso. Não abra versões de pastas diferentes
durante o teste das permissões.

## Autorizar os Recursos

O macOS controla as permissões; o aplicativo não pode concedê-las sozinho.

| Recurso | Permissão necessária |
| --- | --- |
| Capturar tela ou janela | Gravação de tela, nos ajustes de Privacidade e Segurança |
| Mostrar e gravar a câmera | Câmera |
| Gravar sua voz | Microfone |

Os nomes dos ajustes podem variar conforme a versão do macOS. Autorize
apenas os recursos que pretende usar. Se uma permissão estiver desativada,
use o controle correspondente no aplicativo para abrir os ajustes.

Se o sistema solicitar que o app seja encerrado depois de autorizar, faça
isso e reabra a mesma instalação. Em seguida, escolha a fonte e confira
a prévia. Não remova e conceda todas as permissões repetidamente como
procedimento normal de teste.

## Conferir o Download

A release também fornece um arquivo `.sha256`. Opcionalmente, com o DMG
e esse arquivo na mesma pasta, execute:

```sh
shasum -a 256 -c LessonStudio-0.1-beta1-apple-silicon.dmg.sha256
```

O resultado esperado é `OK`. Isso confirma a integridade em relação ao
checksum publicado, mas não substitui a assinatura Developer ID ou a
notarização da Apple.

## Atualizar

Feche o aplicativo, substitua-o na mesma pasta e reabra essa instalação.
Não é necessário apagar gravações para atualizar. As permissões continuam
sujeitas às regras e decisões do macOS; esta beta não promete que nunca
haverá uma nova solicitação do sistema.

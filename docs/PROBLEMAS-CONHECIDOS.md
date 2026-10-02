# Problemas Conhecidos

## Abertura Bloqueada

A beta não está assinada com Developer ID nem notarizada pela Apple.
Um bloqueio ao abrir o instalador ou o app é diferente de uma negativa de
permissão de câmera, microfone ou gravação de tela.

Não desative a segurança do macOS. Consulte as
[orientações da Apple](https://support.apple.com/pt-br/102445) e relate a
mensagem exibida. A distribuição com assinatura reconhecida está pendente.

## Permissão Concedida, mas Fonte Indisponível

Confira se a autorização é para a instalação que está aberta, se o macOS
solicitou encerramento e se a mesma cópia foi reaberta. Escolha a fonte e
use o ícone para atualizar as fontes. Não alterne entre a cópia do DMG,
uma build do Xcode e o aplicativo instalado durante esse teste.

Se continuar falhando, registre a versão do macOS, a mensagem do aplicativo
e se o problema reaparece depois de fechar e reabrir. Não apague todas as
permissões como primeira medida. Esta beta não consegue garantir que o
sistema jamais solicitará autorização novamente.

## Câmera ou Microfone Ausente

Verifique a permissão específica nos ajustes do macOS e o dispositivo
selecionado no painel da direita. Para voz, também confirme **Gravar microfone**.
Após conectar um microfone, atualize a lista pelo ícone correspondente.
Se o dispositivo não aparecer ou não fornecer imagem/áudio, registre o nome
do modelo e se funciona em outro aplicativo.

## Prévia Diferente do Vídeo

A prévia de preparação não mostra os efeitos de gravação e usa qualidade
reduzida. Durante a gravação, ela é ocultada intencionalmente. Confira zoom,
cursor, privacidade e foco em uma gravação curta antes de capturar material
real. Não use dados privados para validar o desfoque.

## Travamentos ou Quadros Perdidos

A meta é reduzir o trabalho de prévia e manter a captura fluida, mas efeitos,
resolução da fonte, dispositivos externos e outros apps podem influenciar
o resultado. Comece com efeitos reduzidos e uma gravação curta para comparar.

Relate modelo do Mac, fonte, formato, duração e efeitos ativos. Diga se a
lentidão afeta o computador, só a interface ou também o vídeo final. Um
teste curto bem-sucedido não comprova estabilidade em sessões longas.

## Limites da Beta

- Não há instalador Intel.
- Não há seleção nativa isolada de uma aba do navegador; selecione a janela.
- Os efeitos devem ser configurados antes da captura; não há editor completo
  de pós-produção nesta versão.
- Não há atualização automática documentada nem envio automático a redes sociais.
- Instalação, permissões e desempenho em outros Macs ainda precisam de teste.

# Testes da Beta

Use uma tela ou janela sem dados privados. Grave primeiro trechos de
20 a 30 segundos; depois faça um teste mais longo, se os curtos funcionarem.

## Roteiro Manual

- [ ] Instalar em um Mac compatível e registrar se o macOS aceitou a abertura.
- [ ] Conceder as permissões necessárias e reabrir a mesma instalação.
- [ ] Selecionar tela inteira e ver a tela real na prévia.
- [ ] Selecionar janela e conferir que é a janela correta.
- [ ] Selecionar imagem e conferir o conteúdo escolhido.
- [ ] Ativar a câmera e confirmar imagem, formato, posição e enquadramento.
- [ ] Escolher o microfone, falar durante a gravação e ouvir a voz no resultado.
- [ ] Quando desejado, testar som do sistema com áudio de teste sem direitos restritos.
- [ ] Gravar e confirmar que a captura continua com a prévia oculta.
- [ ] Mover e clicar o mouse e conferir os efeitos no resultado, não na prévia.
- [ ] Testar 16:9, 1:1 e 9:16 e verificar se não há recortes indesejados.
- [ ] Testar o acompanhamento do mouse no Reels.
- [ ] Testar uma região de privacidade com texto fictício e conferir início e fim.
- [ ] Parar, reproduzir e exportar o MP4; abrir o arquivo em outro reprodutor.
- [ ] Fechar e reabrir o app e registrar se as autorizações continuam disponíveis.
- [ ] Observar se o Mac permanece utilizável durante a captura.

## Verificações Locais Realizadas

Em 2 de outubro de 2026, os testes automáticos locais da beta passaram para:

- Geometria das composições em horizontal, quadrado e vertical.
- Composição com uma imagem de câmera de teste, não uma câmera física.
- Desfoque, pixelização, cobertura, foco, zoom e acompanhamento do cursor.
- Prévia Metal não vazia e com orientação correta.
- Entrega apenas da prévia mais recente, sem acumular quadros para a interface.
- Gravação por fonte de imagem nos três formatos, sem enviar quadros de
  prévia durante a captura e sem reiniciá-la automaticamente ao terminar.
- Vídeos gerados decodificáveis, com dimensões esperadas e cadência próxima
  de 30 fps nos testes curtos dessa máquina.
- Integridade do DMG, da assinatura local e do checksum publicado.

Esses testes não substituem a instalação em outro Mac, a captura de tela real,
o teste de câmera e microfone físicos, nem sessões longas. A instalação e
as permissões em outro computador **ainda não foram validadas**. Não há
garantia de desempenho igual em todos os modelos.

## Relatar Resultados

Abra uma Issue com modelo do Mac, versão do macOS, versão da beta,
fonte, formato, dispositivos de áudio, passos para repetir, resultado
esperado e resultado observado. Informe se o problema acontece na prévia,
durante a captura, na reprodução ou apenas no MP4 exportado.

Evite anexar gravações com senhas, documentos privados, rostos sem autorização
ou informações pessoais. Um pequeno vídeo de teste com dados fictícios é
mais útil e mais seguro para investigar.

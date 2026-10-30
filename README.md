# Câmera Web

App de câmera que roda no navegador do celular. Um único `index.html`, sem build e sem servidor: as fotos ficam salvas só no aparelho (IndexedDB).

**Acesse:** https://mariocb-duarte.github.io/camera-web/

## Recursos
- Câmera traseira e frontal
- Lanterna e zoom (botões e pinça), quando o aparelho suporta
- Temporizador 0/3/10s e grade de composição
- Detecção de rosto em tempo real (MediaPipe, processada no próprio aparelho)
- Modo Auto: fotografa cada pessoa nova uma única vez (5 fotos em sequência, com foco no rosto quando o aparelho suporta). Usa reconhecimento facial no aparelho para não repetir quem já foi fotografado
- Resolução máxima ou HD
- Galeria local com compartilhar, baixar e excluir

## Requisitos
A câmera só é liberada em HTTPS (ou localhost). No celular, use "Adicionar à tela inicial" para abrir como app.

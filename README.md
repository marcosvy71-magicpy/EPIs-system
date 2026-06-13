# Sistema de Verificação de EPIs com Visão Computacional

Sistema que utiliza visão computacional (YOLO + OpenCV) para verificar o uso correto de EPIs (capacete e óculos de proteção) em tempo real, gerando fichas automáticas de cada verificação.

## Estrutura do Projeto

```
epi-system/
├── src/        # Código-fonte Python (captura de vídeo, detecção, interface)
├── model/      # Modelo YOLO treinado (.pt, configs)
├── db/         # Banco de dados SQLite com fichas de verificação
└── docs/       # Manual de uso e relatório técnico
```

## Tecnologias

- Python 3.x
- OpenCV
- YOLO (detecção de objetos)
- SQLite

## Sprints

| Sprint | Período | Objetivo |
|--------|---------|----------|
| Sprint 0 | 13 jun | Kick-off — ambiente e repositório |
| Sprint 1 | 13–20 jun | Visão computacional (câmera + YOLO) |
| Sprint 2 | 21 jun–4 jul | Resultado APROVADO/REPROVADO + banco de dados |
| Sprint 3 | 5–11 jul | Testes, polimento e documentação |
| Sprint 4 | 12–18 jul | Entrega final |

## Como rodar

> Instruções serão adicionadas ao longo do desenvolvimento.

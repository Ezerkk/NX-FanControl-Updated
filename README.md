# NX-FanControl (Atualizado para Firmware 21.x)

Este é um fork do projeto original **NX-FanControl**, atualizado para garantir compatibilidade com as novas firmwares do Nintendo Switch (19.0.0, 20.0.0, 21.0.0 e superiores) e as versões mais recentes do Atmosphere (1.8.0+).

## 🚀 O que há de novo?
- **Compatibilidade com Firmware 21.x**: Recompilado/Preparado para as mudanças de ABI da `libnx` v5.0.0+.
- **Estabilidade**: Inclui as correções de modo de suspensão e performance implementadas anteriormente por @masagrator.

## 📜 Créditos e Reconhecimento
Este projeto é baseado no trabalho original de **Zathawo**. Este fork visa manter a ferramenta funcional para a comunidade.

- **Criador Original**: [Zathawo](https://github.com/Zathawo)
- **Contribuições Importantes**: [masagrator](https://github.com/masagrator) (Correções de estabilidade e performance).
- **Contribuições Importantes**: [dominatorul](https://github.com/dominatorul) (Correções de estabilidade e performance).

> **Nota**: Todos os direitos e créditos do código original pertencem aos seus respectivos autores. Este repositório segue a licença MIT original.

## 🛠️ Requisitos para Compilação
Para compilar este projeto, você precisará do ambiente [devkitPro](https://devkitpro.org/wiki/Getting_Started) configurado com:
- `switch-dev`
- `libnx` (v5.0.0 ou superior)
- `switch-mesa` (para o overlay)

## 📦 Como Compilar
```bash
git clone --recurse-submodules https://github.com/Ezerkk/NX-FanControl-Updated.git
cd NX-FanControl-Updated
make all
```

## 📥 Instalação
1. Baixe a última versão na aba de [Releases]().
2. Copie a pasta `atmosphere` para a raiz do seu cartão SD.
3. Reinicie o console.
4. Acesse o menu Tesla para configurar a curva da fan.

---
*Mantido com ❤️ pela comunidade de homebrew do Switch.*

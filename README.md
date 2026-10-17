# MoodMap

## Visão do projeto

MoodMap é a ideia de um aplicativo social para compartilhar e consultar percepções sobre o clima emocional de diferentes lugares. A proposta futura considera recursos de mapas e serviços Apple para armazenar e compartilhar essas observações.

## Estado atual do repositório

Na implementação rastreada atualmente, o aplicativo é um ponto de partida em SwiftUI:
- `MoodMapApp.swift` inicia a aplicação e apresenta `ContentView`.
- `ContentView.swift` exibe um ícone de globo e o texto “Hello, world!”.

A integração com **MapKit**, **CloudKit**, **Foundation Models**, sincronização em tempo real e notificações push ainda não aparece implementada nesses arquivos. Esses itens devem ser tratados como objetivos planejados, não como funcionalidades disponíveis.

## Executar o projeto

1. Abra `MoodMap/MoodMap.xcodeproj` no Xcode.
2. Selecione o esquema e um simulador ou dispositivo configurado no Xcode.
3. Compile e execute o aplicativo.

O repositório não documenta ainda requisitos de versão do sistema, contratos de dados, permissões ou configuração de serviços externos. Esses detalhes devem ser acrescentados quando forem definidos e validados.

## Próximos passos sugeridos

- Definir o modelo de uma observação de clima emocional (campos, localização, autoria e validade).
- Implementar e validar a tela principal do mapa antes de anunciar MapKit como funcional.
- Definir autenticação, política de privacidade, armazenamento e regras de moderação antes de ativar compartilhamento social.
- Documentar separadamente o estado implementado e o roadmap.

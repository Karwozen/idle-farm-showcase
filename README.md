# Idle Farm

Idle Farm é um RPG de fantasia baseado em tibia, jogável no navegador. A proposta é preparar um personagem, escolher uma expedição e acompanhar a caçada automática. A versão atual é uma demonstração em desenvolvimento.

## Como se joga

1. Crie uma conta de teste e escolha uma das cinco classes: Druid, Warrior, Mage, Paladin ou Monk.
2. Entre no mundo e siga o tutorial interativo para conhecer a interface.
3. Escolha um local de caça, ajuste a dificuldade e inicie uma expedição. Durante a sessão, acompanhe o progresso e os resultados da caçada.
4. Encerre a expedição para voltar à cidade e preparar a próxima.

## Tecnologias

| Componente | Papel no projeto |
| --- | --- |
| OTClient e WebAssembly | Cliente do jogo executado no navegador |
| C++ e Canary | Base do servidor, responsável pelo mundo e pelas sessões de jogo |
| Lua | Regras de jogo, interface e tutorial |
| HTML, CSS e JavaScript | Telas de acesso e integração com o cliente web |
| Python, Flask e MariaDB | API de contas de teste e persistência |
| WebSocket, Nginx e Docker Compose | Conexão com o jogo e execução dos serviços da demonstração |

O navegador apresenta o mundo e a interface. O servidor mantém o estado do personagem e executa as regras da caçada. A demonstração usa contas e dados separados do ambiente de desenvolvimento.

## Demonstração

O acesso de teste é distribuído por convite. Este repositório reúne a documentação pública do projeto. As tecnologias de terceiros mantêm suas respectivas licenças.

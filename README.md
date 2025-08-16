
# Cluster
O Cluster é uma plataforma web de carteiras compartilhadas construída no ecossistema Stellar, permitindo que grupos de amigos, equipes e comunidades administrem fundos coletivos de forma simples, segura e transparente. Diferente de uma wallet individual, o Cluster oferece multisig nativo, garantindo que as transações só ocorram com a autorização definida pelo grupo.

## Proposta
A proposta é criar círculos de confiança em cripto, onde cada carteira pode ter múltiplos participantes com papéis distintos: administradores, contribuidores ou apenas visualizadores. O painel coletivo mostra saldos, contribuições e retiradas, enquanto todo o histórico de transações permanece registrado de forma imutável no ledger Stellar.

## Arquitetura
A arquitetura combina Node.js no backend (API + Stellar SDK), Rust para smart contracts e PostgreSQL para gerenciamento off-chain de usuários e permissões. No frontend, a interface pode ser construída em HTML, CSS e JS, ou em React para maior fluidez.

## Diferencial
O Cluster prioriza segurança com login criptografado, autenticação em duas etapas (2FA) e auditoria completa de operações. Seu diferencial está em unir usabilidade moderna com o poder do Stellar, criando uma solução prática para grupos que querem gerir criptoativos de forma colaborativa e confiável.
--- Desafio DIO: Criando seu primeiro Copilot no Microsoft Copilot Studio
Este repositório documenta minha participação no desafio de projeto da DIO.
O objetivo foi explorar o Microsoft Copilot Studio criando três tipos de copilotos: um baseado em modelo, outro gerado por descrição com IA, e um criado do zero (em branco).

--- Etapas do Desafio
Antes de começar a criar os copilotos, segui algumas etapas fundamentais:

- Criação da Conta Microsoft 365
O Copilot Studio exige uma conta corporativa ou educacional. Como não tinha uma, entrei no Microsoft 365 Developer Program e criei uma sandbox gratuita com licença E5. Isso me deu acesso completo às ferramentas necessárias.

- Acesso ao Microsoft Copilot Studio
Com a conta pronta, acessei https://copilotstudio.microsoft.com. A interface é bem intuitiva, com opções para criar copilotos de diferentes formas: por modelo, por descrição com IA ou em branco.

--- Copilot baseado em modelo
-- Objetivo
Criar um agente conversacional a partir de um modelo pré-definido, entendendo como funciona a estrutura padrão e como personalizá-la.

-- Processo
- Escolhi o modelo de atendimento ao cliente.
- O modelo já vinha com tópicos como “Saudações”, “Ajuda com produto” e “Encerramento”.
- Personalizei os fluxos para simular um suporte técnico de uma empresa fictícia chamada TechHelp.

-- Personalizações
- Alterei as mensagens para torná-las mais acolhedoras e naturais.
- Adicionei um novo tópico chamado “Dúvidas sobre planos”, com opções de múltipla escolha.
- Configurei condições para redirecionar o usuário com base nas respostas.

-- Testes
- Usei o simulador interno para testar cada fluxo.
- Verifiquei se o copiloto reconhecia corretamente as intenções e respondia de forma lógica.

--- Copilot baseado em descrição com IA
-- Objetivo
Explorar a funcionalidade de IA generativa do Copilot Studio, que cria agentes com base em uma descrição textual.

-- Processo
- Escolhi a opção “Criar com base em descrição”.
- Digitei: “Quero um copiloto que ajude pessoas a encontrarem vagas de emprego com base em perfil e localização.”
- A IA gerou automaticamente tópicos como:
- “Buscar vagas”
- “Filtrar por localização”
- “Perfil profissional”

-- Personalizações
- Ajustei os textos para torná-los mais naturais.
- Adicionei um tópico chamado “Dicas para entrevista”.
- Configurei gatilhos para reconhecer frases como “quero trabalhar”, “procuro emprego”, etc.

-- Testes
- Testei os fluxos no simulador.
- Fiz ajustes nas condições de entrada e nas mensagens de erro.

--- Copilot em branco
-- Objetivo
- Criar um agente do zero, definindo manualmente todos os tópicos, fluxos e respostas.

-- Processo
- Escolhi a opção “Criar em branco”.
- Dei ao projeto o nome fictício: Suporte Curso DevPro.
- Criei os seguintes tópicos:
- “Informações sobre o curso”: responde perguntas como duração, certificado, etc.
- “Inscrição”: orienta sobre como se inscrever.
- “Contato”: fornece e-mail e telefone fictício.

-- Personalizações
- Usei lógica condicional para redirecionar o usuário com base nas respostas.
- Adicionei mensagens de erro personalizadas.
- Criei variáveis para armazenar nome e interesse do usuário.

-- Testes
- Testei cada fluxo no simulador.
- Ajustei os gatilhos e condições para garantir fluidez na conversa.

--- Aprendizados
- Entendi as diferenças entre criar copilotos por modelo, IA e manualmente.
- Aprendi a estruturar fluxos conversacionais com lógica condicional.
- Descobri como a IA generativa pode acelerar o desenvolvimento.
- Percebi a importância de testar cada fluxo e ajustar os detalhes para melhorar a experiência do usuário.

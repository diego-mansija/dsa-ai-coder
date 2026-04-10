# Estudo de Caso 1 - Assistente de Programação Especialista em Python (DSA AI Coder)

# Este projeto consiste no desenvolvimento de um Agente de Inteligência Artificial Generativa especializado em suporte técnico para desenvolvedores Python. A aplicação utiliza a infraestrutura de alta performance da API Groq para processar modelos de linguagem de larga escala (LLMs), fornecendo respostas estruturadas que incluem explicações conceituais, blocos de código otimizados e referências à documentação oficial.

# O foco principal foi construir uma ferramenta de interface rica (Streamlit) que gerencia o ciclo de vida de uma conversa (Session State) e aplica técnicas de System Prompting para garantir que a IA mantenha um comportamento estritamente técnico e didático. O sistema foi projetado para auxiliar desde a resolução de bugs até a explicação de estruturas de dados complexas, seguindo padrões de codificação profissional.

# Funcionalidades e Competências Demonstradas

    Integração de LLMs via API: Implementação de conexão robusta com a plataforma Groq, utilizando modelos de baixa latência para respostas em tempo real.

    Engenharia de Prompt (System Messaging): Criação de um CUSTOM_PROMPT estruturado que define regras de operação, formatação obrigatória de respostas e restrição de escopo para programação.

    Gestão de Estado e Histórico: Uso avançado de st.session_state para manter o contexto da conversa, permitindo que o usuário faça perguntas sequenciais de forma fluida.

    Segurança e UX: Implementação de entrada de credenciais via campo de senha (type="password") e tratamento de exceções para garantir a estabilidade da aplicação em caso de falhas na rede ou na API.

    Arquitetura Streamlit: Design de interface focado em experiência do usuário, utilizando barras laterais para configurações e janelas de chat nativas para interação.

# Instalação

# Este projeto foi desenvolvido usando Anaconda. Vá até [https://www.anaconda.com/download](https://www.anaconda.com/download) e baixe o executável próprio para o seu SO.

# Este projeto exige uma API key Groq. Vá até [https://console.groq.com/keys](https://console.groq.com/keys) para obter uma chave válida.

# Abra o terminal ou prompt de comando, navegue até a pasta com os arquivos e execute o comando abaixo para criar um ambiente virtual:

conda create -n dsa-ai-coder python=3.13

# Ative o ambiente:

conda activate dsaec1 (ou: source activate dsaec1)

# Instale o pip e as dependências:

conda install pip
pip install -r requirements.txt 

# Execute a app:

streamlit run dsa_assistente.py

# Exemplos de uso do assistente:

# Como crio um hello world em Python?
# Qual a sintaxe de um loop em Python?
# Como eu uso a função map em Python? Me dê um exemplo com lambda.

# Use os comandos abaixo para desativar o ambiente virtual e remover o ambiente (opcional):

conda deactivate
conda remove --name dsaec1 --all




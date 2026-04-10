# Projeto_Conversando_por_Voz
Um assistente de voz multilíngue que integra reconhecimento de fala, modelos de linguagem e síntese de voz em uma única interface web construída com Streamlit.

O usuário fala pelo navegador, o áudio é transcrito via Whisper (OpenAI), processado por um modelo de linguagem (Gemini ou ChatGPT, com seleção e fallback automáticos) e a resposta é devolvida em áudio usando gTTS, mantendo o idioma da conversa sempre que possível.

O projeto foi pensado para rodar tanto localmente quanto no Google Colab (com túnel via ngrok), servindo como prova de conceito de conversas por voz em múltiplos idiomas usando APIs de IA modernas.



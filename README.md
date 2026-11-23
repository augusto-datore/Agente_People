# Agente People

Aplicação Streamlit para apoiar o fluxo de recrutamento com Groq, Google Calendar e Google Sheets.

## Execução local

1. Crie e ative um ambiente virtual Python.
2. Instale as dependências com `pip install -r requirements.txt`.
3. Configure `GROQ_API_KEY` e `PLANILHA_ID` no ambiente. `.env.example` contém somente valores fictícios.
4. Configure a autenticação Google localmente. Os arquivos `credentials.json` e `token.json` não fazem parte desta cópia e estão bloqueados pelo `.gitignore`.
5. Execute `streamlit run main.py`.

Não publique chaves, tokens, dados de candidatos ou planilhas reais.

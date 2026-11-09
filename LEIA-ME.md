# fabrica-whisper

Modelo de transcrição usado pela versão celular da Fábrica de Conteúdo (Ninja Automações). Fica aqui porque o
ambiente do app do Claude não baixa do Hugging Face.

- Modelo: **Whisper small** (OpenAI), convertido para o formato do faster-whisper em int8 (conversão da Systran,
  `Systran/faster-whisper-small`).
- `model.bin` está em partes de 80 MB por causa do limite de arquivo do GitHub: `cat model.bin.parte* > model.bin`.
- Este repositório só redistribui o modelo, sem alteração nos pesos. Não tem código nem dado de ninguém.

## Licença

Os pesos do Whisper e a conversão para faster-whisper são distribuídos sob a licença MIT. O texto da licença
está em [LICENSE](LICENSE).

# Registro de uso de IA

Regra completa em `AGENTS.md`. O agente de IA **acrescenta uma entrada ao final** a cada interação que gerar ou
alterar algo. Nunca apagar nem reescrever entradas antigas. A justificativa é do aluno, com as palavras dele.

## Modelo de entrada

```
### AAAA-MM-DD — Nome do aluno — Ferramenta (ex.: Claude Code, Gemini no Colab)
- **Onde:** arquivo/célula/etapa
- **O que foi pedido:**
- **O que a IA sugeriu ou fez:**
- **Pergunta de "por quê" feita ao aluno:**
- **Decisão do aluno e justificativa (palavras dele):**
- **Alternativa descartada e motivo:**
``

## Entradas

### 2026-10-14 — Márcio Rogério Reis Freire Júnior — Claude (chat)
- **Onde:** Granorte_Modelo.ipynb, Etapa 0 (ambiente reproduzível e seed)
- **O que foi pedido:** Etapa 0 seguindo linha a linha, conforme o AGENTS.md.
- **O que a IA sugeriu ou fez:** célula de instalação sem versão, célula que lê as versões instaladas e gera o requirements.txt, e célula que fixa a seed em random, numpy e torch.
- **Pergunta de "por quê" feita ao aluno:** (1) como escolher as versões das bibliotecas e por quê as mais recentes; (2) qual valor de SEED e por quê.
- **Decisão do aluno e justificativa (palavras dele):** usar a versão mais recente: no meu ponto de vista é a versão mais atualizada, logo penso que posso trazer resultados melhores, óbvio que possa conter alguns bugs, se for o caso peço para voltar algumas versões. SEED = 28: pode ser 28 dia do meu aniversário.
- **Alternativa descartada e motivo:** usar as versões do treino que deu mAP50 0,995 ou as que o Colab já traz; o aluno preferiu a versão mais recente, anotando o número instalado.
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rounded&color=0:fbcfe8,100:f9a8d4&height=170&section=header&text=Consultor%20de%20Carreira&fontSize=42&fontColor=831843&fontAlignY=42&desc=Python%20%C2%B7%20Global%20Solution%20FIAP%202025&descSize=16&descAlignY=68" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=Quicksand&weight=600&size=19&pause=1400&color=DB2777&center=true&vCenter=true&width=620&lines=Digite+sua+profiss%C3%A3o;Receba+um+roadmap+de+requalifica%C3%A7%C3%A3o;Base+local+%2B+Google+Gemini" />

</div>

<br>

### Sobre o projeto

Consultor de carreira desenvolvido na **Global Solution 2025 da FIAP**, sobre o futuro do trabalho, como parte do projeto **SkillShift**. A pessoa informa a profissão atual e recebe as habilidades de hoje, as profissões do futuro e um roadmap de requalificação.

Faz parte da mesma solução do [Semáforo de Empregabilidade](https://github.com/sosofisouza/semaforo-empregabilidade), que mostra o risco de automação de cada área.

<br>

### Como funciona

```
Profissão digitada
        │
        ▼
Está na base local (dados.json)?
   ├── sim ──►  mostra habilidades, profissões do futuro e roadmap
   └── não ──►  pergunta ao Google Gemini e mostra a resposta em tempo real
```

A base local tem 14 áreas profissionais, cada uma com 5 profissões do futuro e o passo a passo para chegar nelas. Quando a área não está na base, a IA gera a análise com habilidades, roadmap e dicas de portfólio.

<br>

### Tecnologias

<div align="center">
  <img src="https://skillicons.dev/icons?i=py&theme=light" />
  <br>
  <sub>Python · Google Gemini · JSON</sub>
</div>

<br>

### Como executar

```bash
pip install -r requirements.txt
```

Gere uma chave no [Google AI Studio](https://aistudio.google.com/apikey) e defina a variável de ambiente:

```bash
set GOOGLE_API_KEY=sua_chave          # Windows
export GOOGLE_API_KEY=sua_chave       # Linux e macOS
python app.py
```

<br>

### Equipe

<div align="center">

Camile Silva &nbsp;·&nbsp; Gustavo Ferreira &nbsp;·&nbsp; Lucas Caetano &nbsp;·&nbsp; Marco Conte &nbsp;·&nbsp; Sofia Rodrigues

</div>

<img src="https://capsule-render.vercel.app/api?type=rounded&color=0:fbcfe8,100:f9a8d4&height=60&section=footer" width="100%" />

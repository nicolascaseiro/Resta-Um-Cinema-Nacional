# 🎬 Resta Um: Cinema Brasileiro

Uma aplicação web imersiva e interativa desenvolvida em **Python** com **Streamlit**, dedicada a celebrar e explorar a história do cinema brasileiro através de escolhas pessoais e torneios eliminatórios.

👉 **[Resta Um: Cinema Nacional](https://resta-um-cinema-nacional.streamlit.app)**

## ✨ Funcionalidades

- **Seleção por Anos (1995–2026):** Navegue pelos anos do cinema nacional, visualize pôsteres e escolha o seu filme favorito para salvar de cada ano.
- **Barra de Progresso:** Acompanhe em tempo real quantos filmes já foram salvos e a porcentagem de conclusão da sua seleção.
- **Modo Mata-Mata:** Um torneio eliminatório estilo *Resta Um* para coroar o grande campeão entre os seus filmes salvos, com duas opções de chaveamento (Ordenado por Seleção ou Chaveamento Aleatório).
- **Histórico de Confrontos:** Acompanhe o chaveamento e o resumo de cada duelo rodada a rodada durante o torneio.
- **Design Exclusivo:** Interface polida com estética dark/gold (inspirada em tipografias clássicas como *Cinzel* e *Oswald*).

---

## 🛠️ Tecnologias Utilizadas

- **Python**
- **Streamlit** (Interface e lógica de estados)
- **JSON** (Banco de dados de filmes desacoplado)
- **HTML5 / CSS3 Customizado** (Estilização avançada e responsiva)

---

## 📦 Estrutura de Arquivos

```text
├── data/
│   └── filmes.json   # Banco de dados estruturado com os filmes e pôsteres
├── app.py            # Código principal da aplicação Streamlit
├── requirements.txt  # Dependências do projeto para deploy
└── README.md         # Documentação do projeto

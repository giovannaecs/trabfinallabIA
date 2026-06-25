# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊# 🫀 IA para Monitoramento de Arritmias com Smartwatches

**Um estudo sobre Inteligência Artificial aplicada à saúde cardiovascular para apoiar o retorno seguro à atividade física em pessoas com cardiopatias.**

Este repositório contém o desenvolvimento completo do meu trabalho acadêmico (Fases 1, 2 e 3) realizado no **CEFET-MG**, sob orientação do Prof. Everthon de Souza Oliveira.

---

## 🌐 Sobre o Projeto

Imagine que seu smartwatch pudesse não apenas contar seus passos, mas também *“ouvir”* o seu coração e te avisar, com segurança, se está tudo bem para continuar se exercitando. Esse é o objetivo do nosso estudo!

Utilizamos **Inteligência Artificial** e **Aprendizado de Máquina** para analisar sinais cardíacos (ECG) de bases de dados públicas (MIT-BIH e PTB-XL) e classificar batimentos como **normais** ou **arrítmicos** (focando principalmente na Fibrilação Atrial, que é a arritmia mais comum e perigosa).

A ideia não é substituir o médico, mas sim criar uma **ferramenta de triagem e monitoramento remoto** que ajude pacientes cardíacos a voltarem a se exercitar com mais tranquilidade, especialmente em programas de reabilitação domiciliar.

---

## 🗂️ O que você encontra neste repositório?

*   **`index.html`**: O código-fonte do site institucional do projeto (hospedado no GitHub Pages), com design elegante e rosa, contendo todas as informações das fases.
*   **Fase 1**: Estudo preliminar e primeiros resultados com o modelo **Random Forest**.
*   **Fase 2**: Pipeline completo com comparação de **3 modelos** (Random Forest, Regressão Logística e MLP) e validação externa.
*   **Fase 3**: Roteiro de apresentação oral, conclusões críticas e questões éticas.
*   **Códigos**: Prévia dos scripts em Python com links para execução no **Google Colab**.

---

## 🔬 Principais Resultados (Em poucas palavras)

Testamos três modelos de IA e o grande vencedor foi o **Random Forest**. Ele conseguiu:

*   **Detectar 80% das arritmias** (Sensibilidade de 80,58%) – ou seja, 4 em cada 5 crises seriam capturadas.
*   **Acertar 95% dos ritmos normais** (Especificidade de 95,31%) – isso significa que o smartwatch não ficaria apitando à toa, evitando ansiedade no paciente.
*   **Separar muito bem os casos** com uma área sob a curva (AUC-ROC) de **0,96** – um desempenho excelente para uma ferramenta de triagem.

> ⚠️ *Mas atenção:* A precisão do modelo ainda é de 57%, o que significa que quase metade dos alertas seriam falsos positivos. Por isso, **ele nunca deve substituir uma avaliação médica formal!**

---

## 🚀 Como acessar e rodar

### 1. 🌐 Site do Projeto (GitHub Pages)
O projeto está disponível online em um site elegante e responsivo. Acesse para ver todas as informações, tabelas e gráficos de forma organizada:

🔗 **`https://seu-usuario.github.io/nome-do-repositorio/`**  
*(Substitua pelo link real do seu GitHub Pages)*

### 2. 💻 Rodar os Códigos no Google Colab
Você pode executar os algoritmos diretamente no seu navegador, sem precisar instalar nada no seu computador. Basta clicar nos links dentro do site ou usar os links abaixo:

*   **Código 1 – Classificador Base (Random Forest):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1gB9KIMGW9AXxJ3iCMXNlf-Bhi4kFmfMV/view?usp=sharing)
*   **Código 2 – Comparação Completa (RF x RL x MLP):**  
    [📂 Abrir no Colab](https://drive.google.com/file/d/1cV70nd0dJ_ijdPz_cqOZZBRmHoWA-YNz/view?usp=sharing)

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** `wfdb`, `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`
*   **Modelos:** Random Forest, Regressão Logística, MLP (Rede Neural)
*   **Front-end:** HTML5, CSS3, JavaScript, Font Awesome, highlight.js
*   **Plataformas:** Google Colab, GitHub Pages

---

## 📚 Referências Principais

Este trabalho foi baseado em importantes bases de dados e estudos científicos, incluindo:

*   **MIT-BIH Arrhythmia Database** (MOODY; MARK, 2001)
*   **PTB-XL** (WAGNER et al., 2020)
*   Estudos sobre wearables e fibrilação atrial (BULUT et al., 2025; WOUTERS et al., 2025)
*   Reabilitação cardíaca com smartwatches (ZHANG et al., 2025)

---

## 👩‍💻 Autoria

**Giovanna Emanuelle Carvalho Silva**  
Aluna de Engenharia Elétrica – CEFET-MG, Campus Nova Gameleira  
📧 giovannaecs@outlook.com

**Orientador:** Prof. Everthon de Souza Oliveira

---

## ⚖️ Licença

Este projeto é de uso acadêmico e educacional. Sinta-se à vontade para estudar, modificar e compartilhar, sempre dando os devidos créditos.

---

⭐ **Se você gostou do projeto ou achou útil, deixe uma estrela no repositório!** Isso ajuda a divulgar a pesquisa e incentiva novos estudos na área de IA e saúde cardiovascular. 😊

# projeto_streamlit<div style="color: white">

<h1 style="font-size: 3rem; display: flex; "><img src="./aula_04/img/image-3.png" width="50" height="53">
Aprendendo Streamlit</h1>

## Iniciando a instalação do Streamlit

### **No terminal digitar o seguinte comando:**

> python -m venv .venv

Após a executar o comando terá criado uma pasta com o nome **.venv** na raiz da pasta, no exemplo abaixo podemos ver que a pasta **.venv** foi criada com sucesso dentro da pasta raiz que é a pasta **aula_04**.

<img src="./aula_04/img/pasta_venv.png">

---

### **Proximo comando a ser executado no terminal**

> .venv\Scripts\activate

Após digitar o comando acima click enter, note que no terminal irá aparecer destacado em verde o nome da pasta venv antes do PS, observe a imagem abaixo como ficará:

<img src="./aula_04/img/venv_ambiente.png">

---

### Agora iremos instalar o framework Streamlit

Digite no terminal o comando abaixo e clique enter

> pip install streamlit

Aguarde o termino da instalação e podemos prosseguir com a criação do arquivo principal para iniciarmos com as funcionalidade que o Streamlit oferece.

Então vamos iniciar, na raiz do projeto que neste caso está sendo utilizado a pasta **aula_04** clique com o botão direito do mouse na pasta **aula_04** e clique em **New File** e de o nome para o novo arquivo de **app.py**.

Após criar o arquivo vamos digitar algumas linhas de código para sabermos de a instalação do Streamlit o ocorreu sem erros, na primeira linha do arquivo digite o código abaixo:

**OBS: Note que quando começar a digitar streamlit tem que aparece um janela com uma lista de itens e você verá que o streamlit está nesta lista, caso não aparece streamlit na lista a instalção do streamlit não foi bem sucedica, reinstale o streamlit com o comando de instalação o pip install streamlit.**

> import streamlit as st
>
> st.markdown("# Testando o Streamlit")

---

Agora iremos executar o seguinte comando no terminal para vermos no browser as configurações iniciais do streamlit que fizemos.

> streamlit run app.py

Se não ocorreu nenhum erro é para o navegador ter aberto e deverá mostrar o texto que digitamos no markdown.

</div>

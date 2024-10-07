<head>
<body>
<h1>
     <img align="center" alt="Logo CV2" width="80px" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSLyADHz04rchjJ4F_gUXX4I6-ohdHZVfnghQ&s">
</h1>
<h1><p>Reconhecimento Facial</p> </h1>
<h3>Detecção Facial com CV2  <strong>Modelo HaarCascade</strong> </h3>
 <img align="center" alt="Reconhecimento Facial PNG" width="500px" height ="300" src="https://media.licdn.com/dms/image/v2/C4E12AQFCwnFPNosg1g/article-cover_image-shrink_720_1280/article-cover_image-shrink_720_1280/0/1651790181943?e=1733961600&v=beta&t=_VmR4QCxijawDN2A5CNtIpHgrFd-Jh5vW4maeSXgj-M"> 
</head>
<h2>Breve descrição de como funciona o modelo HaarCascade</h2>
  <p>Características Haar-like são como "mini-padrões" simples que um computador usa para identificar objetos em uma imagem. Imagine dividir uma imagem em pequenos retângulos e comparar a luminosidade desses retângulos. Essas diferenças de luminosidade são as características Haar-like. Elas são como as peças de um quebra-cabeça que o computador usa para montar a imagem de um rosto, por exemplo.

Um classificador em cascada é como uma série de filtros que a imagem passa. Cada filtro verifica se a imagem tem uma determinada característica Haar-like. Se não tiver, a imagem é descartada rapidamente. Se tiver, ela passa para o próximo filtro. Essa organização em camadas (cascata) faz com que o processo seja muito rápido, pois as imagens que não são rostos são eliminadas logo no início.

O treinamento é o processo de ensinar o computador a reconhecer as características Haar-like de um objeto específico. Para isso, mostramos ao computador
muitas imagens, algumas com o objeto (por exemplo, rostos) e outras sem. O computador aprende a identificar quais combinações de características Haar-like são típicas do objeto que estamos procurando.</p>

**Importação de Bibliotecas:**
* **numpy:** Utilizado para operações numéricas.
* **cv2:** Biblioteca OpenCV para processamento de imagens.
* **cv2_imshow:** Função específica do Google Colab para exibir imagens.

**Carregamento da Imagem e Pré-processamento:**
* **Carrega a imagem:** Lê a imagem a partir do caminho especificado.
* **Converte para tons de cinza:** Simplifica a imagem para facilitar a detecção.

**Carregamento do Modelo Haar Cascade:**
* **Carrega o classificador:** Carrega um modelo pré-treinado para detectar pessoas.
* **Modelo Haar Cascade:** Utiliza características simples da imagem para identificar padrões de rostos humanos.

**Detecção de Pessoas:**
* **Aplica o classificador:** Utiliza o modelo carregado para detectar regiões na imagem que correspondem a pessoas.
* **Retorna retângulos:** Identifica as áreas onde as pessoas foram detectadas.

**Visualização dos Resultados:**
* **Desenha retângulos:** Desenha retângulos ao redor das áreas detectadas.
* **Adiciona rótulos:** Adiciona a palavra "pessoa" dentro dos retângulos.
* **Exibe a imagem:** Mostra a imagem final com as detecções.

**Em resumo:**

O código demonstra como utilizar o OpenCV e um modelo Haar Cascade pré-treinado para detectar pessoas em imagens. O processo envolve carregar a imagem, aplicar o modelo para encontrar as regiões de interesse e, finalmente, visualizar os resultados.

**Conceitos-chave:**

* **Haar Cascade:** Um tipo de classificador usado para detectar objetos em imagens.
* **OpenCV:** Biblioteca popular para visão computacional.
* **Detecção de objetos:** Processo de localizar objetos específicos em uma imagem.

**Possíveis Extensões:**

* **Outras classes:** Detectar outros objetos, como carros ou rostos.
* **Melhoria da precisão:** Experimentar diferentes modelos Haar Cascade ou ajustar os parâmetros de detecção.
* **Rastreamento de objetos:** Rastrear objetos ao longo de um vídeo.
* **Deep learning:** Utilizar técnicas de deep learning para obter resultados mais precisos.
<h2>Link para o Projeto: <h4><a href= "Haarcascade_Fullbody.ipynb" align="left" alt="projeto">Detecção Facial</a></h4></h2>
</body>
</html


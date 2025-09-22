# 💧Aplicador de Marcas d'Água em Lote

Este é um script em Python que aplica automaticamente uma marca d'água a todas as imagens de uma pasta. Utilizando a biblioteca Pillow, ele redimensiona a marca d'água de forma proporcional a cada imagem e posiciona-a no canto inferior direito.
✨ Funcionalidades Principais

    Processamento em Lote: Aplica a marca d'água a todas as imagens .jpg de uma pasta de uma só vez.

    Redimensionamento Inteligente: A marca d'água é redimensionada para ocupar 20% da largura de cada imagem de destino, mantendo a sua proporção e garantindo um resultado consistente em imagens de diferentes tamanhos.

    Posicionamento Automático: A marca d'água é sempre colocada no canto inferior direito da imagem.

    Não Destrutivo: As imagens originais não são modificadas. Os resultados são guardados numa nova pasta.

🚀 Como Usar

Para executar este projeto na sua máquina local, siga os passos abaixo.
Pré-requisitos

    Python 3.x instalado na sua máquina.

1. Clone o Repositório

Primeiro, clone este repositório para o seu computador:

    git clone https://github.com/matheuskbraga/automatic-watermark.git

(Lembre-se de substituir SEU-USUARIO e NOME-DO-SEU-REPOSITORIO pelos seus dados)

Depois, entre na pasta do projeto:

    cd NOME-DO-REPOSITÓRIO-DO-PROJETO

2. Instale as Dependências

Este projeto depende da biblioteca Pillow. Para instalá-la, execute o seguinte comando no seu terminal:

    pip install Pillow

3. Prepare as Pastas e Ficheiros (Passo Importante!)

    A sua Marca d'Água: Coloque o ficheiro da sua marca d'água (preferencialmente em formato .png com fundo transparente) na pasta principal do projeto. O script espera que este ficheiro se chame McLaren_Racing_logo.png. Se o seu ficheiro tiver outro nome, lembre-se de o alterar na primeira linha do código.

    As suas Imagens: Crie uma subpasta chamada fotos. Coloque todas as imagens no formato .jpg às quais você deseja adicionar a marca d'água dentro desta pasta.

A estrutura de pastas deve ficar assim:

    .
    ├── fotos/
    │   ├── imagem1.jpg
    │   ├── imagem2.jpg
    │   └── ...
    ├── McLaren_Racing_logo.png  <-- A sua marca d'água
    └── seu_script.py            <-- O seu script principal

4. Execute o Script

Com tudo preparado, basta executar o script Python:

    python watermark.py

Após a execução, uma nova pasta chamada watermark_ok será criada e conterá todas as suas imagens com a marca d'água aplicada.
🎯 Resultado Esperado

O script aplicará a sua marca d'água de forma consistente em todas as suas imagens.

🤝 Contribuições
Sinta-se à vontade para fazer um "fork" deste projeto e sugerir melhorias. Todas as contribuições são bem-vindas!

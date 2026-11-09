# livro-expotec
Projeto de livro colaborativo realizado em oficina na IV Expotec do IFRN Campus Lajes

<!----->

<img src="figures/capa.avif" width="90%"></img>

## Projeto

O projeto consiste em copiar, revisar e editar, de maneira colaborativa, o livro 'A revolução dos bichos', de George Orwell, que pode ser encontrado no [domínio público](https://www.dominiopublico.gov.br/download/texto/cv000100.pdf) do governo federal.

Para isso serão utilizadas principalmente as ferramentas LuaLaTeX, git e Github. Cada equipe de participantes ficará responsável por um capítulo do livro e enviará seu trabalho para este repositório.

Além da correção do texto cada equipe criará, a partir de uma ferramenta de geração de imagens de inteligência artificial, uma imagem que ilustre uma cena de cada capítulo.

## Roteiro

### Fase 1: Preparando as Ferramentas (Primeiros Passos)

1. **Criar a conta no GitHub:** Acesse o site do GitHub e crie uma conta gratuita. Caso já possua uma conta, ignore este passo e utilize a mesma. Ela será o nosso ponto de encontro para juntar todas as partes do livro de forma colaborativa.
2. **Instalar o GitHub Desktop:** Para facilitar o envio dos arquivos e o controle de versão sem precisar decorar códigos ou usar o terminal, baixe e instale o GitHub Desktop. Faça o login com a sua conta.
3. **Baixar o projeto para o computador:** No site do GitHub, acesse o link do repositório oficial da oficina. Clique no botão verde **Code**, escolha **Open with GitHub Desktop** e clone o projeto. Isso criará uma cópia exata de toda a estrutura do livro no computador que você está usando.

### Fase 2: Mão na Massa com o Texto

1. **Extrair o conteúdo:** Abra o arquivo PDF original de domínio público da obra *A Revolução dos Bichos*, disponibilizado previamente na pasta do projeto, e localize o capítulo pelo qual o seu grupo ficou responsável.
2. **Limpar a formatação:** Copie o texto do PDF e cole em um bloco de notas simples. Faça uma leitura atenta para revisar a ortografia, remover quebras de linha que cortam frases no meio, apagar números de página e excluir qualquer cabeçalho que tenha vindo junto na cópia.

### Fase 3: Ilustrando a História

1. **Escolher a cena:** Com base na leitura do capítulo, discuta e escolha uma cena marcante ou representativa para ilustrar.
2. **Criar a ilustração com Inteligência Artificial:** Utilizando uma ferramenta de geração de imagens baseada em inteligência artificial, crie uma ilustração que represente uma cena importante do capítulo em questão. Guarde a imagem resultante na pasta de imagens do nosso projeto no computador.
3. **Criar o prompt:** Para criar a imagem, use este prompt como base:

Classic colored book illustration of a scene from Animal Farm:[Insira a descrição da cena aqui (preferencialmente em inglês)]. Soft pastel color palette, gentle muted pastel tones, colored vintage editorial style, fine ink outlines, soft textured paper background, landscape composition, 1280x851 resolution, --ar 3:2.

### Fase 4: Formatando no LaTeX

1. **Abrir o arquivo do capítulo:** Utilizando o editor de LaTeX escolhido para a oficina, abra o arquivo de texto vazio correspondente ao capítulo de vocês (ex.: `src/main/02.tex`).
2. **Inserir o texto:** Cole o texto já revisado e limpo dentro do documento, logo abaixo da marcação que define o título do capítulo.
3. **Adicionar a imagem:** No local exato onde a cena ocorre na história, utilize a estrutura básica de inserção de figuras do LaTeX para chamar a imagem que você salvou na pasta, não esquecendo de adicionar uma legenda descritiva logo abaixo dela.
4. **Revisar caracteres especiais:** Lembre-se de colocar uma barra invertida (`\`) antes de símbolos do dia a dia como `%`, `$`, `&` e `#`. O LaTeX interpreta esses símbolos como funções matemáticas ou de formatação, e a barra diz ao programa para tratá-los apenas como texto comum.

### Fase 5: Inserindo os Dados dos Colaboradores

1. **Abrir o arquivo dos colaboradores:** Utilizando o editor de LaTeX escolhido para a oficina, abra o arquivo de texto vazio correspondente à lista de colaboradores (`src/front/colab.tex`).
2. **Inserir o texto:** Insira o seu nome e o link da conta do GitHub. Em caso de grupo, insira os dados de cada membro da equipe. Se houver dúvida, basta seguir o exemplo já presente no arquivo e/ou perguntar aos palestrantes.

### Fase 6: Salvando e Juntando o Livro (Commit e Pull Request)

1. **Registrar as alterações (Commit):** Abra o GitHub Desktop novamente. O programa vai listar automaticamente o arquivo de texto que você editou e a nova imagem que adicionou na pasta. Na caixa de texto no canto inferior esquerdo, escreva um resumo curto do que foi feito (ex.: “Adicionado texto limpo e ilustração do Capítulo 2”) e clique em **Commit to main** (ou no nome da branch correspondente).
2. **Enviar para a nuvem (Push):** Agora que o trabalho está salvo no histórico do computador, clique no botão superior **Push origin**. Isso vai subir os arquivos atualizados para o repositório online do GitHub.
3. **Propor a junção (Pull Request):** Acesse a página do projeto no navegador e abra um **Pull Request**. Isso funciona como um pedido formal aos organizadores dizendo: “Nosso capítulo está pronto e revisado, podem juntá-lo ao livro principal!”
4. **A Grande Compilação:** Ao final da oficina, o organizador vai aceitar todos os Pull Requests no GitHub. Com todos os arquivos na mesma pasta, basta compilar o documento principal (`main.tex`) uma única vez. O LaTeX vai puxar e diagramar todos os capítulos automaticamente, gerando o PDF final da nossa edição colaborativa!

### Fase 7: Prompt

> Classic book illustration of a scene from *Animal Farm*: [INSERIR A DESCRIÇÃO DA CENA DO TRECHO AQUI]. Vintage editorial style, woodcut engraving style, detailed ink lines, dramatic lighting, textured paper background, landscape composition, widescreen view, 1280x851 resolution, --ar 3:2.

## Propósito


## Resultado esperado
A expectativa é de que, além da geração do livro, cada participante possa desenvolver habilidades no LaTeX, no Github e/ou na programação de modo geral. Esperamos que esta oficina possa ajudar a expandir os horizontes e explorar e


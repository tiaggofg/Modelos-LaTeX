# Modelos de documentos em LaTeX

Esse é um repositório de modelos de documentos em LaTeX, como trabalhos acadêmicos, provas, listas de exercícios, slides, etc. Caso encontre algo que possa melhorar, não se acanhe em fazer sugestões ou pull requests.

## 🚀 Começando

Para que você possa compilar os scripts em sua máquina é necessário que você tenha o pacote abntex2 (_Absurd Norms for TeX 2_). Ele é bastante útil para criar documentos que precisam seguir as normas da abnt, como TCCs e demais trabalhos acadêmicos. Portanto, a maioria dos modelos dispostos por esse repositório utilizam o abntex2. Para mais informações acesse <https://www.abntex.net.br/>

Caso queira mudar a classe do documento substitua o abntex2 pela classe que deseja, como no exemplo abaixo:

```
documentclass[<opções>]{article}
```

Caso faça isso, esteja ciente que erros podem aparecer e você terá de modificar o código.

### 📋 Pré-requisitos

Além disso, existem outros pré-requisitos e o principal deles é ter o pacote abntex2cite, já que é através dele que todas as citações e referências são feitas.

Outros pacotes essenciais que não podem faltar no documento são:

```
\usepackage[utf8]{inputenc}
```

```
\usepackage{indentfirst}
```

```
\usepackage{fancyhdr}
```

```
\usepackage{lipsum}
```

Os demais pacotes não são necessários para gerar o modelo, mas são muito úteis ao escrever um documento. Por exemplo, para escrever equações, inserir imagens, construir diagramas entre outros.

### 🔧 Instalação

Não vou adentrar em como instalar o LaTeX ou os pacotes, no entanto se você usa windows, a melhor maneira é pelo distribuidor e gerenciador de pacotes MiKTeX. Para saber como instalar e usar acesse: <https://miktex.org/> ou <https://www.ctan.org/pkg/miktex>.

Se você tem alguma distro GNU/Linux também pode usar o MiKTeX, mas aconselha-se que tenha também o TeXLive em sua máquina. Ele é um diretório que contém a ISO oficial do TeX: <https://www.ctan.org/pkg/texlive>.

Para ter a acesso a documentação dos pacotes utilizados e conhecer vários outros que podem ser úteis, acesse: <https://www.ctan.org/>.

## 🛠️ Construído com

- [TeXStudio](https://www.texstudio.org/) - Editor LaTeX

<!--- ## 📄 Licença -->

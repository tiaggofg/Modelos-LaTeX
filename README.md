# Modelos de documentos em LaTeX

Esse projeto é um repositorio de modelos de documentos em LaTeX, como trabalhos academicos, provas, listas de exercicios, slides, etc. Caso encontre algo que possa melhorar, não se acanhe em fazer sugestões ou pull requests.

## 🚀 Começando

Para que você possa compilar o script em sua máquina é necessário que você tenha o pacote abntex2 (*Absurd Norms for TeX 2*). Esse pacote é bastante útil para arquivos que precisam seguir as normas da abnt, como TCCs e demais trabalhos acadêmicos. Portanto, a maioria dos modelos dispostos por esse repositório utilizam o abntex2. Para mais informações acesse <https://www.abntex.net.br/>

Caso queira mudar a classe do documento substitua o abntex2 pela classe que deseja, como no exemplo abaixo:

```
documentclass[<opções>]{article}
```

Caso faça isso esteja ciente que erros podem aparecer e você terar de modificar o código.
### 📋 Pré-requisitos

Além disso, existem outros pré-requisitos e o principal deles é ter o pacote abntex2cite, já que é através dele que todas as citações e referências são feitas.

Outros pacotes essênciais que não podem faltar no documento são:

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

Os demais pacotes não são necessários para gerar o modelo, mas são muito úteis ao escrever um documento. Por exemplo, para escrever equações, inserir imagens, construir diagramar entre outros.

### 🔧 Instalação

Não vou adentrar em como instalar o LaTeX ou os pacotes, no entanto se você usa windows, a melhor maneira é pelo distribuidor e gerenciador de pacotes MiKTeX: <https://miktex.org/> ou <https://www.ctan.org/pkg/miktex>.

Se você tem alguma distro GNU/Linux também pode usar o MiKTeX, mas aconselha-se que tenha também o TeXLive em sua máquina que é um diretório que contém a ISO oficial do TeX: <https://www.ctan.org/pkg/texlive>.

Para ter a acesso a documentção dos pacotes utilizados entre em: <https://www.ctan.org/>.

## 🛠️ Construído com

- [TeXStudio](https://www.texstudio.org/) - Editor LaTeX

<!--- ## 📄 Licença -->
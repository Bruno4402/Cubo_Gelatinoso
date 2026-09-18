![Ilum Escola de Ciência, CNPEM](https://pages.cnpem.br/workshopbioimagens/wp-content/uploads/sites/166/2023/06/logo-ilum.png)


<h1 align="center">Cubo Gelatinoso</h1>

**Nome:** Bruno Bini Camargo  | **Turma:** T26 <br>
**Instituição:** Ilum Escola de Ciência, CNPEM, Campinas

Repositório para armazenar projeto introdutório da disciplina de Aprendizado de Máquina, do 2° semestre do curso de Ciência e Tecnologia na Ilum.

## 🚀 Sobre o projeto:

Este projeto tem como objetivo prever a energia de formação por átomo em materiais para baterias de lítio a partir de propriedades físico-químicas e estruturais, utilizando o algoritmo $k$-Nearest Neighbors ($k$-NN). A proposta foca em avaliar como o tratamento de dados, diferentes técnicas de normalização e a otimização de hiperparâmetros impactam diretamente a precisão do modelo.

O estudo desenvolvido abrange as seguintes etapas:

* Tratamento das variáveis, separação dos atributos e da variável-alvo (*target*), e divisão do *dataset* em conjuntos de treino e teste.
* Avaliação inicial do $k$-NN ($k=3$, $p=2$) sem escalonamento prévio, estabelecendo um RMSE inicial.
* Teste e comparação de três métodos de normalização.
* Teste amostral de 15 hiperparãmetros e posterior variação exaustiva de $k$ e $p$ para localização do melhor hiperparâmetro global.
* Aplicação de *Cross-Validation* com $p$ fixo para mapear o equilíbrio ideal entre menor RMSE e estabilidade (desvio padrão).
* Análise do comportamento de $p$ com $k$ fixo e diagnóstico da distribuição dos erros por amostra.

## :open_file_folder: Arquivos do repositório:

* :page_facing_up: **.gitignore**: Contém informações para ignorar arquivos desnecessários no Git.
* :memo: **Cubo Gelatinoso.ipynb**: Contém o notebook Jupyter do projeto.
* 💹 **materiais_de_bateria_de_lítio.csv**: Contém dataset utilizado no projeto.
* :balance_scale: **LICENSE**: Contém informações da licença desse projeto, a GNU General Public License v2.0.
* :book: **README.md**: Contém a documentação principal do projeto.

## 🖥️ Ferramentas usadas no projeto:

- **Jupyter Lab** para desenvolvimento do código.
- **IA** para resolução de dúvidas de sintaxe, correção de bugs e lógica do modelo, auxílio na elaboração de gráficos complexos, validação cruzada e análise diagnóstica da atividade, indicando melhorias. 

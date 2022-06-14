# Genshin-Impact-Database
# Dados relativos às personagens de Genshin Impact

Dados atualizados de características relativas a personagens do videojogo “Genshin Impact”.
Os dados apresentados são relativos a uma pesquisa feita em outubro de 2021, não sofrendo alterações desde então.
Fonte dos dados/Bibliografia: https://www.kaggle.com/datasets/genshinplayer/genshin-impact-characters-stats


# Contexto

Genshin Impact é um jogo de ação gratuito, desenvolvido e publicado pela “miHoYo” em 2020. É um jogo fantasioso com sistemas de batalha, e está disponível para computador, consolas e telemóveis/tablets.
Os dados apresentados são relativos a características de personagens do videojogo, analisando vertentes como o elemento, as armas, etc.
A estrutura base deste ficheiro foi desenhada para fácil manipulação em Excel/Python/R e não sofrerá alterações, podendo a comunidade analítica considerá-lo um alvo imutável para, por exemplo, alimentar plataformas de visualização/modelação. 


# Estrutura

`Genshin_Impact_All_Character_Stat.csv`: dados extraídos de Kaggle, contém os dados relativos às personagens do videojogo.

`notebooks/`: contém um notebook Python com perguntas e respostas sobre o csv.

`Cartaz - Dados Relativos às Personagens.pdf`: cartaz representativo do projeto.

`Dados relativos às personagens de Genshin Impact.pdf`: relatório com algumas informações pertinentes acerca do projeto realizado.


# Dicionário de dados
Uma explicação do conteúdo em `Genshin_Impact_All_Character_Stat.csv`

| Nome da coluna        | Significado           | Possíveis valores  |
| ------------- |:-------------:| -----:|
| `Character` | Identificação da personagem | Objeto |
| `Lv` | Nível em que se encontra a personagem | Inteiro >= 0 |
| `Rarity` | Raridade da personagem    | Inteiro >= 0 |
| `Element` | Elemento da personagem      | Objeto |
| `Weapon` | Arma utilizada pela personagem      | Objeto |
| `Main Role` | Papel principal da personagem      | Objeto |
| `Ascension` | Evolução da personagem     | Objeto |
| `Base HP` | Valor de vida    | Inteiro >= 0 |
| `Base ATK` | Valor de ataque | Inteiro >= 0 |
| `Base DEF` | Valor de defesa  |  Inteiro >= 0 |

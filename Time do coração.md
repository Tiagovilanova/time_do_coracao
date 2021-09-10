# Time do coração  :heart: :soccer:

## Descrição do projeto:

#### Trata-se de dois projetos que criei, neles utilizo algumas Collections (List e Set). Os projetos possuem três Classes: club, jogadores e rival. As duas últimas classes estão instanciadas na classe club, assim, foi instanciada uma lista do tipo jogadores e Set do tipo rival. 



![image-20210910091933281](C:\Users\Tiago Vila-Nova\AppData\Roaming\Typora\typora-user-images\image-20210910091933281.png)

#### 1 -Primeiro Projeto(time_Do_Coracao) :heart:

##### - O primeiro projeto possui técnicas básicas na aplicação de Collections, como adição de elementos em uma List e Set. 

##### - Além disso, utilizou o método forEach para a apresentação dos elementos contidos na List e Set.

##### - Utilização do sort para ordenação da lista de jogadores conforme o nome e idade;  

### Observação importante: não podemos ordenar os rivais contidos no SET. Assim, não podemos aplicar o sort;





### 2 -Segundo Projeto (time_Do_Coracao_unmodifiable)

#### Vamos entender esse projeto como uma uma cópia do primeiro, no entanto há modificações:

#### primeiro, na classe club foi adicionado um método que adiciona os dados do jogador, observe o método abaixo:

public void adiciona(jogador atleta)
	{this.atleta.add(atleta);}

#### segundo, na mesma classe (club) também foi utilizado a estrutura : Collections.unmodifiableList(atleta), observe o método abaixo: 

public List<jogador> getAtleta() {
		return Collections.unmodifiableList(atleta);
	}

## Observação importante: Com unmodifiableList, novos elementos a lista do tipo jogador só pode executada pelo método adiciona.

## Observação importante: Caso queira adicionar novos elementos na lista da forma tradicional (do projeto anterior), basta criar uma outra lista e colocar o nome da lista anterior como seu argumento (faço isso no meu projeto também).



## Software de execução 

### Eclipse 

### Autor/Linkedin/lattes

Tiago Marcel Santos Vila-Nova

 https://www.linkedin.com/in/tiago-vila-nova-3b88971b9/

https://wwws.cnpq.br/cvlattesweb/PKG_MENU.menu?f_cod=D1A7A1E49EBB3A584221035283983771#







#### 








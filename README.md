# iFood - Python Test

- O prazo para finalizar o teste é de uma semana
- Antes de iniciar o teste, clone o repositório para seu profile. As respostas também devem ser armazenadas em seu respositório
- Após finalizar, envie a URL de seu repositório clonado para security@ifood.com.br

## Questões ## 
 1. Crie um programa em Python para imprimir os **n** primeiros números primos. Seja criativo(a) na escolha do algoritmo.
- Sugestão de entrada de dados:
    `python q1.py -n 10`
   
2. Crie um programa em Python, de preferência concorrente, para fazer o download de todas as URLs de uma lista de sites. Os sites devem estar em um arquivo de entrada. As URLs devem ser armazenadas em um arquivo contendo as URLs organizadas por site.
- Sugestão de entrada de dados:
    `python q2.py -i sites.txt -o resultado.txt`

3. Crie um programa em Python para analisar o arquivo de logs **ifood.csv**. Pede-se:
-   Imprima as URLs únicas por ordem decrescente de total de acessos
-   Quais URLs podem ser phishing? Por quê?

4. Crie uma API em Python que implemente os endpoints 
- /restaurante 
- /restaurante/<id_x>
- /restaurante/<id_x>/prato
- /restaurante/<id_x>/prato/<id_y> 

Implemente os métodos **POST, GET, PUT, DELETE** onde achar conveniente. 
Recomendações:
- Use sua criatividade para especificar o body do request e response
- Dê preferência ao formato json nos requests e responses
- Utilize sqlite para armazenar os dados

**PLUS**: Implemente autenticação e mecanismo de autorização nos endpoints. Sugestão de perfis: cliente e restaurante.



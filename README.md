# aula07
Respostas GCM
1.O gerenciamento de configuração é o processo para estabelecer e manter a consistência dos atributos físicos, funcionais e de performance de um produto durante sua vida, de acordo com seus requisitos, desenho e informações operacionais.
2. Especificação do sistema, Requisitos, código fonte, manuais operacionais, programa executável, descrição de banco de dados , manual do usuário, teste de software\sistema, especificação do projeto.
3.Funcional/Projeto ,Produto : modelagem de Negócios requisitos implementação e Teste, implementação
Produto:
Build, release, inicial.
4. Versão commercial:
	Microsoft Source Control
Microsoft Visual SourceSafe
IBM Rational Clear Case
Borland StarTeam
Gratuitas:
Cvs
Subversion
git   
5. existem dois tipos de arquitetura uma centralizada e uma distribuída (descentralizada)
Centralizada 
Os arquivos ficam num servidor e as modificações são feitas e upadas lá.
Decentralizadas ou distribuídas 
Existe um servidor más as todos os computadores têm uma versão do máster local onde são feitas as alterações e depois são upadas no servidor máster principal tendo também uma vantagem de trabalhar em off-line. O Git por exemplo é uma ferramenta de controle de versão que utiliza uma arquitetura distribuída 
6.uma vantagem é o desenvolvimento em paralelo que todos podem produzir ao mesmo tempo com uma versão do máster deixam o servidor livre para outras funções as alterações feitas são feitas em uma cópia então não vai afetar o principal tendo também uma vantagem de trabalhar em off-line. 
7.Não o repositório está sendo criado no git, mais tem como criar um repositório também no computador.
8.criar um branch, realizar commits e pushes no branch criado, colocar a versão modificada em produção (deplay),realizar o merge no branch máster do repositório local, criar pull request.
9. Ter que ser feito uma alteração no arquivo manual mente o conflito vai dar # file quadrado.py
<<<<<<< branch2

n1= int(input('n1:'))
quadrado = n1*n1
print(quadrado)
print('fim')
=======
print('início')
n1= int(input('n1:'))
# cálculo do quadrado
print('FIM')
>>>>>>> máster
 O resultado será:
# file quadrado.py
print('início')
n1= int(input('n1:'))
# cálculo do quadrado
quadrado = n1*n1
print(quadrado)
print('FIM')

10.nao vai dar nenhum problema e o ficar 
   # file dobro.py 
n = int(input('n:')) 
dobro = 2*n 
print(dobro)
print('fim')


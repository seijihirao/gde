## Instalação ##

 1. Instale o Composer de [getcomposer.org](https://getcomposer.org)
 2. Acesse a pasta raiz do projeto e rode o comando `composer install`
 3. Copie o arquivo `common/config-sample.inc.php` para `common/config.inc.php`
 4. Edite o arquivo `common/config.inc.php` com os dados apropriados
 5. Rode o comando `vendor/bin/doctrine orm:schema-tool:update --force` para criar as tabelas

## Sobre este projeto ##

P: Este é o GDE "de verdade"?  
R: Sim e não: Esta é a versão 2.5 do GDE, atualmente a versão "em produção" é a 2.3.  
  
P: Qual a diferença entre a versão 2.3 e a 2.5?  
R: Em termos de funcionalidades: "avisos", "fóruns", "grupos" e "oportunidades" foram removidos (não eram utilizados). Em termos de backend: a versão 2.3 foi escrita entre 2009 e 2012, e contém código antigo, desatualizado, potencialmente inseguro e, sinceramente, às vezes vergonhoso. Nenhuma biblioteca ou framework foi utilizada, foi tudo feito do zero. Na versão 2.5 foi tudo reescrito para utilizar o ORM [Doctrine](http://www.doctrine-project.org/). Além disso, a versão 2.5 suporta disciplinas com a mesma sigla e níveis diferentes, cursos com o mesmo número e níveis diferentes e oferecimentos com turmas com mais de 2 caracteres, além de várias outras correções menores.  
  
P: Quando o GDE 2.5 vai ao ar?  
R: Assim que algum as burocracias envolvidas forem resolvidas. Espero que isso ocorra antes de 2018!  

P: Já foi tudo reescrito?  
R: Não, esse é um processo lento e trabalhoso, e infelizmente estou fazendo tudo sozinho.  
  
P: E falta muito?  
R: Depende do ponto de vista. Veja a próxima pergunta.  
  
P: O que já funciona nesta versão e o que não funciona?  
R: Segue a lista que vou manter atualizada:  

Funciona:

 - Acontecimentos e Status
 - Amigos
 - Árvore / Integralização (pouco testada)
 - Avaliar Professores
 - Calendário
 - Configurações da Conta
 - Contato (não testada)
 - Convidar um Amigo (não testada)
 - Disciplina
 - Editar Perfil (pouco testada)
 - Eliminar Disciplinas
 - Enquetes
 - Estatísticas (parcial)
 - Frase do Dia
 - Login
 - Inicial
 - Mapa do Campus
 - Notas
 - Oferecimento
 - Perfil (Usuário, Aluno e Professor)
 - Perguntas Frequentes (FAQ)
 - Planejador (pouco testado)
 - Sala
 - Sobre o GDE

Ainda não funciona:

 - Admin
 - API
 - Chat

  
P: E qual o prazo pra isso ser concluído?  
R: Gostaria de dar um prazo, mas isso é impossível. Quero concluir o mais rápido possível para que todos possam colaborar com o projeto.  

P: Por que isso está sendo feito?  
R: Porque eu acredito que a comunidade de alunos (e ex-alunos) da Unicamp podem colaborar com o projeto, e levá-lo muito mais longe do que eu (e meus amigos que me ajudaram) sou capaz (por questões de tempo, conhecimento, ideias, etc).  
  
P: Posso colaborar?  
R: Sim, por favor! Faça fork e envie seu pull request!  

P: Como posso ajudar?  
R: Depende:

 - Se você sabe programar em PHP, fique a vontade para corrigir um problema ou criar uma nova feature. Seu pull request será analisado com carinho!
 - Se você é designer, crie um novo layout mais moderno (quem sabe, responsivo) para o GDE, ou melhore o atual, e envie seu pull request.
 - Se você não se encaixa em nenhuma das opções anteriores, envie sugestões ou problemas encontrados criando uma [Issue](https://github.com/guaycuru/gde/issues).

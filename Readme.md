Github

Testando o modo de inserção de em arquivo

vi "nomeDoArquivo.md" - Editar um arquivo
[i] - entrar no modo de insersão
[ESC] - Sair do modo de insersão
[:wq] - : iniciar comando, w - escrever e salvar, q - sair

Para acessar novamente repita o primeiro comando

 --- Arquivo da aula de Git e GitHub ---

 Ciclo de vida dos status dos arquivos
  untracked
  unmodified
  modified
  staged

-- staged área onde ficam os arquivos que serão submetidos (commit) --

Depois de adionar as modificãções do arquivo com o 'git add <file>', levando tudo para staged,
realiza-se a submissão com o 'git commit -m "Mensagem de instrução sobre modificação na versão"

Depois de salvo, volta-se para untracked.

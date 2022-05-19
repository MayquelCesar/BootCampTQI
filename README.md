# PrimeiroProjetoDIO-Repositorio-GitGithub

## Projeto Git\Github- Utilizando comandos no GitBash

 - **DEMAIS APRENDIZADOS NO ARQUIVO TXT**

- Usei o site da GitHub para mais orientações https://docs.github.com/pt
- Utilizei o guia da Markdown para aprender a syntax básica https://www.markdownguide.org/basic-syntax/
- Criando SHS a partir do Git Bash(aprendizado através do curso Git\Github da DIO)
  - 1º Abrir GitBash
  - 2º digitar: ssh-keygen -t ed25519 -C example@gmail.com
  - 3º digitar: cd /caminho/.ssh/
  - 4º digitar: ls
  - 5º digitar: cat id_ed25519.pub
  - 6º Ir até o site Git e colar a key apresentada no passo acima dentro do campo SHS após nomear.
  - 7º voltar ao GitBash
  - 8º digitar: eval $(ssh-agent -s)
  - 9º digitar: ssh-add ed_ed25519
  - 10º Ir até o site Git copiar o link do SSH
  - 11º voltar ao GitBash
  - 12º digitar: get clone + link ssh copiado do site github.

 - Após terminar o README.md fiz um commit e depois clonei usando o link SHS que criei. 
   - Entrei no GitBash e digitei: git clone (link do SHS)

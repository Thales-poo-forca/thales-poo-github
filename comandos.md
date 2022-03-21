git checkout -b <> -- Cria uma branch nova à partir da branch em que o usuário está.

git pull origin <> -- Faz a mesclagem das branchs, sem necessidade de comit apenas atualiza o que está na branch <<>> e joga na branch atual. Não mantem a rastreabilidade de que houve um merge

git merge --no-ff <> -- Faz a mesclagem das branchs, mas informa que houve uma mesclagem através de um commit de merge
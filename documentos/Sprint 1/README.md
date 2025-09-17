# Sprint 1 - Documentação

## 📌 Objetivo
Implementar as funcionalidades básicas do sistema, incluindo:
- Cadastro e login de usuários.
- Ver lista de propriedades associadas a um usuário.
- Visualização de propriedades no mapa.
- Atribuição de Plus Code a propriedades.
- Editar Plus Codes.
- Emitir certificado ao criar/editar um Plus Code.


### Backlog da Sprint

| RANK   | ITEM   | STATUS |
| :----: | :----: | :----: |
|#1|Criar repositório no GitHub.| 🕓 |
|#2|Backlog do produto.| 🕓 |
|#3|Backlog da sprint.|🕓  |
|#4|Desenvolvimento de protótipo no Figma.|  🕓|
|#5|Criação de telas.|  🕓|
|#6|Configuração do banco de dados.|  🕓|
|#7|Cadastro e login de usuários.| 🕓 |
#8|Acesso ao aplicativo sem login. | 🕓|
|#9|Listar e gerenciar propriedades de um usuário.|🕓 |
|#10|Visualizar suas propriedades no mapa.|🕓 |
|#11|Atribuir Plus Code a uma propriedade.|🕓 |
|#12|Editar o Plus Code de uma propriedade.| 🕓|
|#13|Gerar certificado digital para cada Plus Code.|🕓 |

### Críterios de Aceitação

| RANK   | ITEM   | STATUS |
| :----: | :----: | :----: |
#7|Se cadastrar com base nos seguintes campos: Nome, Sobrenome, Data de nascimento, Senha, Confirmar senha. Tem que ter uma verificação se o CPF é válido e permitir manter logado.| 🕓 |
#8|Ao entrar pela primeira vez, pedir o login. Se o usuário optar por não fazer, só pedir novamente caso ele clique em fazer login ou tente usar uma funcionalidade que seja necessário estar logado (qualquer uma, a não ser traçar rotas).| 🕓 |
#10|Com cores diferentes para aqueles que possuem Plus Codes e com destaque, caso tenha plus code, ao clicar nela deve ser possível ver suas informações básicas (Nome de referência, Plus Code, e foto).|🕓  |
|#11|Somente dentro de sua propriedade. Deve ter um espaço para adicionar uma foto (no máximo 5MB), colocar um nome de referência e uma descrição (o único campo obrigatório é o de nome de referência).|  🕓|
|#12|Mantendo um log das edições, contendo os seguintes campos: Id do log, Evento (criou, editou), Usuário (id de quem alterou), Data (quando alterou timestamp), Propriedade (id da propriedade alterada), PlusCode (sempre o mais recente, se existir), resultado (se teve sucesso ou não), além de gerar um novo certificado ao editar.|  🕓|
|#13|Certificado é essencialmente um PDF com uma data de criação do plus code, o plus code em si, o nome de quem criou, o nome atrelado a esse plus code, e uma hash para poder validar esse certificado, além da necessidade de validar os dados antes de enviar.|  🕓|


[⬅️ Voltar para o README principal](../../README.md)



Conhecendo git e git hub - explicando o codigo
Comandos:
          git --version 
          git init                   - Inicia o Git
          git add                    - Envia o arquivo para a area de stading 
          git status                 - Exibe a situação do repositorio
          git branch -M main         - Mudar o usuario Master para Main já utilizado em muitas empresas em substituição ao master
          git config --global user.email "alexandro.zuza@gmail.com"  (esse comando é necessario quando o git não sabe quem você é, atrela seu email e autentica seu usuário como
                                                                      proprietário da alterações)  
          git config --global user.name "alex" 
                                      OBS.: Após a utilização desses dois comandos, não ocorrerá mais o erro no commit

          git remote add origin https://github.com/alezuza/Git.git (Necessário fazer a conexão remota apenas uma unica vez para um novo repositório)
          git push -u origin main    - envia de fato os arquivos commitados para o github informado no git remote 

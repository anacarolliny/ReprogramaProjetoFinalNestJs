# ReprogramaProjetoFinalNestJs
Essa Γ© a versΓ£o em NestJs e Typescript do projeto final da Reprograma


ReprogramaProjetoFinal

## πArquitetura NestJs

```
 π ProjetoFinalReprograma
   |
   |-  π src
   |    |
   |    |- π configs
   |         |- π configService.ts
             |- π ormconfig.ts
   |
   |    |- π modules
   
   |         π users
   
                  |- π dto
             
                    |- π createParticipantes.ts
                    |- π createProfissionais.ts
   |
   |              |- π infra
                    |- π controllers
                        |- π participantes.controllers.ts
                        |- π profissionais.controllers.ts
                    |- π typeorm
                      |- π entities
                        |- π participantes.ts
                        |- π profissionais.ts
                        
                      |- π repositories
                        |- π participantes.repository.ts
                        |- π profissionais.repository.ts
                  |- π repositories
   |                  |- π participantesRepository.interface.js
                      |- π profissionaisRepository.interface.js
                  |- π useCases
                    |- π createParticipantesService
   |                  |- π createParticipante.service.ts
                      |- π createParticipante.service.spec.ts
   |                |- π createProfissionaisService
   |                  |- π createProfissionais.service.ts
                      |- π createProfissionais.service.spec.ts
   |       
   |         |- π users.module.js 
   |         
   |         
   |         
   |
   |    |- π app.module.ts
   |    |- π main.js 
   |         
   |         
   |
   |    
   |-  π swagger
        |- π swagger_output.json
   |    
   |
   |
   |- π .env
   |- π .env.example
   |- π .gitignore
   |- π package-lock.json
   |- π package.json
   |- π Procfile
      |- π README.md
   |- π server.js
   |- π swagger.js

```

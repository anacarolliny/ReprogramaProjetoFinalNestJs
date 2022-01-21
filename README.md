# ReprogramaProjetoFinalNestJs
Essa é a versão em NestJs e Typescript do projeto final da Reprograma


ReprogramaProjetoFinal

## 📁Arquitetura NestJs

```
 📁 ProjetoFinalReprograma
   |
   |-  📁 src
   |    |
   |    |- 📁 configs
   |         |- 📑 configService.ts
             |- 📑 ormconfig.ts
   |
   |    |- 📁 modules
   
   |         📁 users
   
                  |- 📁 dto
             
                    |- 📑 createParticipantes.ts
                    |- 📑 createProfissionais.ts
   |
   |              |- 📁 infra
                    |- 📁 controllers
                        |- 📑 participantes.controllers.ts
                        |- 📑 profissionais.controllers.ts
                    |- 📁 typeorm
                      |- 📁 entities
                        |- 📑 participantes.ts
                        |- 📑 profissionais.ts
                        
                      |- 📁 repositories
                        |- 📑 participantes.repository.ts
                        |- 📑 profissionais.repository.ts
                  |- 📁 repositories
   |                  |- 📑 participantesRepository.interface.js
                      |- 📑 profissionaisRepository.interface.js
                  |- 📁 useCases
                    |- 📁 createParticipantesService
   |                  |- 📑 createParticipante.service.ts
                      |- 📑 createParticipante.service.spec.ts
   |                |- 📁 createProfissionaisService
   |                  |- 📑 createProfissionais.service.ts
                      |- 📑 createProfissionais.service.spec.ts
   |       
   |         |- 📑 users.module.js 
   |         
   |         
   |         
   |
   |    |- 📑 app.module.ts
   |    |- 📑 main.js 
   |         
   |         
   |
   |    
   |-  📁 swagger
        |- 📑 swagger_output.json
   |    
   |
   |
   |- 📑 .env
   |- 📑 .env.example
   |- 📑 .gitignore
   |- 📑 package-lock.json
   |- 📑 package.json
   |- 📑 Procfile
      |- 📑 README.md
   |- 📑 server.js
   |- 📑 swagger.js

```

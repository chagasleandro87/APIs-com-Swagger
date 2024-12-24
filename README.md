# APIs-com-Swagger:

Criar uma API auto-documentável com Node.js e Swagger é uma prática essencial para facilitar o uso e manutenção de APIs, permitindo que desenvolvedores acessem a documentação diretamente e testem os endpoints de forma interativa.

# Aqui está um passo a passo para criar uma API auto-documentável:

1. Configuração do Ambiente

# Certifique-se de ter o Node.js e o npm instalados no seu sistema.

mkdir api-com-swagger
cd api-com-swagger
npm init -y

# Instale as dependências necessárias:

npm install express swagger-ui-express swagger-jsdoc

# Link da documentação do Fastify:
https://www.npmjs.com/package/@fastify/swagger-ui

# NodeJS utilizado neste projeto foi o 18.2.0
Após a instalação do tsconfig.json segue abaixo a configuração do node 18.2.0

{
  "$schema": "https://json.schemastore.org/tsconfig",
  "display": "Node 18",

  "_version": "18.2.0",

  "compilerOptions": {
    "lib": ["es2023"],
    "module": "node16",
    "target": "es2022",

    "strict": true,
    "esModuleInterop": true,
    "skipLibCheck": true,
    "moduleResolution": "node16"
  }
}

https://github.com/tsconfig/bases/blob/main/bases/node18.json

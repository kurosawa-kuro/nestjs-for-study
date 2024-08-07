# nestjs-for-study

 nest new project-name

 npm install --save-dev @nestjs/config

 npm install prisma @prisma/client

 npx prisma init

 DATABASE_URL="postgresql://postgres:postgres@localhost:5432/web_app_db_integration?schema=public"

 JWT_SECRET="6b6eb1a4cb31c08e470389d80d35c29ff1751c6bccff9bbb8dfdf854e54583ee"

 npx prisma migrate dev --name init

 nest g module prisma
 nest g service prisma --no-spec
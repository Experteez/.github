# <h1 align="center"> Experteez - Frontend and Backend - Hacker Stage 2 Hackfest 2024 ✨ </h1>

## Repository
Terdapat 2 repository dalam github organization ini, yaitu Experteez-Frontend dan Experteez-Backend.

## Branching

-   `main` branch adalah branch utama yang digunakan untuk deploy ke production
-   `development` branch adalah branch yang digunakan untuk development

## Commit Message Convention (Semantic)

-   `feat`: (new feature for the user, not a new feature for build script)
-   `fix`: (bug fix for the user, not a fix to a build script)
-   `docs`: (changes to the documentation)
-   `style`: (formatting, missing semi colons, etc; no production code change)
-   `refactor`: (refactoring production code, eg. renaming a variable)
-   `test`: (adding missing tests, refactoring tests; no production code change)
-   `chore`: (updating grunt tasks etc; no production code change)

## How to Run Locally (Frontend)

1. Clone repository Experteez-Frontend (branch `main`)
2. cd ke root folder
3. Buka folder project di Visual Studio Code (`code .` in CLI)
4. Buka terminal dan run `npm install`
5. Run `npm run dev` untuk menjalankan server
6. Buka browser dan akses`http://localhost:3000`

## How to Run Locally (Backend)

1. Clone repository Experteez-Backend (branch `main`)
2. cd ke root folder
3. Buka folder project di Visual Studio Code (`code .` in CLI)
4. Buka terminal dan run `go mod vendor`
5. Run `go run main.go` untuk menjalankan server
6. Buka browser dan akses`http://localhost:8080`

### Or if you guys want to run it using docker

1. Clone repository Experteez-Backend (branch `main`)
2. cd ke root folder
3. Buka folder project di Visual Studio Code (`code .` in CLI)
4. Nyalakan docker desktop
5. Buka terminal di Visual Studio Code dan run `docker build --tag experteez-backend .`
6. Tunggu sampai selesai build, dan cari image hasil build di docker desktop dan klik tombol Run untuk membuat container dan menjalankannya, untuk pilihan Port dibebaskan ya.
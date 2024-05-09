# <h1 align="center"> EpidemIT - Frontend, Backend, and ML - Slashcom X Hackathon 2024 ✨ </h1>

## Repository
Terdapat 3 repository dalam github organization ini, yaitu EpidemIT-Frontend, EpidemIT-Backend, dan EpidemIT-ML.

## Branching

-   `main` branch adalah branch utama yang digunakan untuk deploy ke production
-   `develop` branch adalah branch yang digunakan untuk development

## Commit Message Convention (Semantic)

-   `feat`: (new feature for the user, not a new feature for build script)
-   `fix`: (bug fix for the user, not a fix to a build script)
-   `docs`: (changes to the documentation)
-   `style`: (formatting, missing semi colons, etc; no production code change)
-   `refactor`: (refactoring production code, eg. renaming a variable)
-   `test`: (adding missing tests, refactoring tests; no production code change)
-   `chore`: (updating grunt tasks etc; no production code change)

## How to Run Locally (Frontend)

1. Clone repository EpidemIT-Frontend (branch `main`)
2. cd ke root folder
3. Buka folder project di Visual Studio Code (`code .` in CLI)
4. Buka terminal dan run `npm install`
5. Run `npm run dev` untuk menjalankan server
6. Buka browser dan akses`http://localhost:3000`

## How to Run Locally (Backend)

1. Clone repository EpidemIT-Backend (branch `main`)
2. cd ke root folder
3. Buka folder project di Visual Studio Code (`code .` in CLI)
4. Buka terminal dan run `go mod tidy`
5. Run `go run main.go` untuk menjalankan server
6. Buka browser dan akses`http://localhost:8080`
   
## How to Run Locally (ML)

1. Clone repository EpidemIT-ML (branch `main`)
2. cd ke root folder `my-app`
3. Buka folder project di Visual Studio Code (`code .` in CLI)
4. Buka terminal dan run `npm install`
5. Run `npm run dev` untuk menjalankan server
6. Buka browser dan akses`http://localhost:3001`

### Or if you guys want to run it using docker

1. Clone repository EpidemIT-Backend (branch `main`)
2. cd ke root folder
3. Buka folder project di Visual Studio Code (`code .` in CLI)
4. Nyalakan docker desktop
5. Buka terminal di Visual Studio Code dan run `docker build --tag EpidemIT-backend .`
6. Tunggu sampai selesai build, dan cari image hasil build di docker desktop dan klik tombol Run untuk membuat container dan menjalankannya, untuk pilihan Port dibebaskan ya.
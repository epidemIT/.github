# <h1 align="center"> EpidemIT - Frontend, Backend, and ML - Slashcom X Hackathon 2024 ✨ </h1>

## About

EpidemIT muncul sebagai platform pendidikan IT berbasis web yang didedikasikan untuk memberikan kesempatan belajar komprehensif yang dapat diakses oleh individu dengan disabilitas atau mereka yang menghadapi keterbatasan keuangan kapanpun dan di manapun. Nama "EpidemIT" sendiri berasal dari kata "Epidemic" yang berarti penyebaran cepat, yang mencerminkan tujuan platform untuk menyebarluaskan pendidikan IT secara luas dan efektif dan inkulsif . EpidemIT menawarkan dua layanan inti, yaitu "Learn with Mentor" dan "Project Based Learning". EpidemIT mengintegrasikan teknologi AI terkini termasuk text-to-speech, text summarizer, dan content-based filtering untuk meningkatkan pengalaman belajar. Selain itu, platform ini memberikan dukungan bantuan keuangan kepada pengguna yang kurang mampu secara ekonomi, memastikan akses yang adil terhadap sumber daya pendidikan.

Dengan memanfaatkan teknik gamifikasi, EpidemIT memberikan insentif belajar dan meningkatkan keterlibatan pengguna melalui tantangan interaktif, reward, dan mekanisme pelacakan kemajuan (level). Fitur pembelajaran berbasis proyek dirancang dengan baik untuk menarik minat pengguna dengan materi belajar interaktif dan dinamis sehingga dapat memupuk semangat dan keterlibatan yang berkelanjutan. Selaras dengan Sustainable Development Goals (SDGs) 4 (Quality Education) dan 8 (Decent Work and Economic Growth), EpidemIT berupaya memberdayakan individu dan masyarakat melalui pendidikan sehingga mempromosikan inklusi sosial dan pemberdayaan ekonomi secara global.

## Team Members (Team FOCUS)
- Auvarifqi Putra Diandra (Hustler, AI/ML Engineer)
- Ucha (UI/UX Designer)
- Gibran Fasha Ghazanfar (Fullstack Engineer, DevOps Engineer)
- Nicholas (AI/ML Engineer, Frontend Engineer)
- Mochamad Syahrial Alzaidan (Fullstack Engineer)

## Website URL
- [EpidemIT](https://main.d1iex298jj9b2k.amplifyapp.com)

## Repository
Terdapat 3 repository dalam github organization ini, yaitu EpidemIT-Frontend, EpidemIT-Backend, dan EpidemIT-ML.

## Tech Stack

**Frontend:** Next.js 13.5.6, Typescript, TailwindCSS

**Backend:** Go, GoFiber, GORM, CockroachDB, PostgreSQL, DatoCMS (Headless CMS)

**ML:** Next.js 14.2.3, Typescript, Flask, Python, Jupyter Notebook

**Deployment:** AWS Amplify (Frontend and ML), GCP; Artifact Registry, Cloud Build, Cloud Run (Backend), Docker (Containerization)

**Tools** : Git, Visual Studio Code, Figma, Canva, Miro, Google Docs, Google Drive, Zoom, Postman API, DBeaver

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

## Screenshots of Application

### Landing Page

<img src="./profile/screenshots/landing.png" alt="landing-page">

### Login Page

<img src="./profile/screenshots/login.png" alt="login-page">

### Sign Up Page

<img src="./profile/screenshots/signup.png" alt="sign-up-page">

### MentorMiit (Find Mentor Page)

<img src="./profile/screenshots/mentormiit.png" alt="find-mentor-page">

### Mentor Details

<img src="./profile/screenshots/mentor-details.png" alt="mentor-details">

### Mentor Schedulling 1

<img src="./profile/screenshots/mentor-scheduling.png" alt="mentor-scheduling-1">

### Mentor Schedulling 2 (Confirm Booking Mentor)

<img src="./profile/screenshots/confirm-booking-mentor.png" alt="mentor-scheduling-2">


### ProjectiT (Find Project Based Learning Page)

<img src="./profile/screenshots/projectit.png" alt="find-project-page">

### Project Details

<img src="./profile/screenshots/project-details.png" alt="project-details">

### Financial Aid For Project Based Learning 1

<img src="./profile/screenshots/financial-aid-1.png" alt="financial-aid-1">

### Financial Aid For Project Based Learning 2

<img src="./profile/screenshots/financial-aid-2.png" alt="financial-aid-2">

### Dashboard Page (Main)

<img src="./profile/screenshots/dashboard-main.png" alt="dashboard-main">

### Dashboard Page (Mentors)

<img src="./profile/screenshots/dashboard-mentors.png" alt="dashboard-mentors">

### Dashboard Page (Projects)

<img src="./profile/screenshots/dashboard-projects.png" alt="dashboard-projects">

### Project Based Learning Materials/Modules Page (Content)

<img src="./profile/screenshots/materials.png" alt="project-materials">

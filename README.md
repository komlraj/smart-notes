# [Smart Notes](https://smart-notes-47nc881lh-komal-rajs-projects.vercel.app/)

An AI-powered personal notes app built with Next.js, TypeScript, Supabase, and OpenAI.

## 🚀 Getting Started

### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/your-username/smart-notes.git
cd smart-notes
```

### **2️⃣ Install Dependencies**
```sh
pnpm install
```

### **3️⃣ Set Up Supabase**
To set up the backend, follow the steps in this **[YouTube tutorial](https://www.youtube.com/watch?v=6ChzCaljcaI&t=425s)** from **32:10 to 35:00**.

### **4️⃣ Create `.env.local` File**
In the project root, create a `.env.local` file with the following details:
```env
DATABASE_URL=<your_database_url>
SUPABASE_URL=<your_supabase_url>
SUPABASE_ANON_KEY=<your_supabase_anon_key>
NEXT_PUBLIC_BASE_URL=http://localhost:3000
OPENAI_API_KEY=<your_openai_api_key>
```

### **5️⃣ Run Database Migrations**
```sh
pnpm run migrate
```

### **6️⃣ Start the Development Server**
```sh
pnpm dev
```
The app will be running at **[http://localhost:3000](http://localhost:3000)**.

## 🏗 Building for Production
To create an optimized production build, run:
```sh
pnpm build
pnpm start
```

## 📜 License
This project is licensed under the MIT License.

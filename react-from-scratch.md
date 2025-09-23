# 🚀 Build a React App from Scratch

## 🔹 Why build from scratch?
- When you have **special requirements** not covered by frameworks.
- To **learn the fundamentals** of how React works under the hood.
- To **experiment** with building your own framework.

---

## 🔹 Step 1: Choose a Build Tool
React needs a build tool to run locally and prepare production builds.

Popular choices:
- **Vite** ⚡ (modern, fast)
  ```bash
  npm create vite@latest my-app -- --template react
  ```
- **Parcel** 📦 (zero config, scalable)
  ```bash
  npm install --save-dev parcel
  ```
- **Rsbuild** 🚀 (high performance with Rspack)
  ```bash
  npx create-rsbuild --template react
  ```

---

## 🔹 Step 2: Add Core Features
When starting with SPA, you need to add manually:
1. **Routing** → React Router, Tanstack Router.  
2. **Data Fetching** → React Query, SWR, RTK Query.  
3. **GraphQL** → Apollo, Relay.  
4. **Code Splitting** → supported by Vite, Parcel, Rsbuild.

---

## 🔹 Rendering Strategies
- **SPA** → simple, slower initial load.  
- **SSR** → server prepares HTML (faster).  
- **SSG** → prebuilt HTML at build time (great for static pages).  
- **RSC** → split components between server and client (advanced).  

---

## 🔹 Summary
- From-scratch setup = full control, but more effort.  
- Frameworks like **Next.js** or **Remix** provide these features out of the box.  

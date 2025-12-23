# Nuxtify 🚀

A sleek **Nuxt 3 framework** project designed to accelerate modern web development with built-in **CI/CD**, testing, and responsive dashboards.

---

## About the Project

Nuxtify is a professional **Nuxt 3** project demonstrating full-stack and frontend skills.
It includes a **dashboard**, **user management interface**, and **responsive design**. Focus is placed on modern **DevOps practices**, **CI/CD integration**, and **automated testing**.

---

## Preview

![Project Screenshot](public/favicon.ico)

> Clean, modern design powered by **Nuxt 3**, **Vue 3**, and **TypeScript**.

---

## Features

* Full-featured dashboard with **summary cards**.
* Admin interface for **user management**.
* SPA navigation with **role-based access control**.
* Responsive UI using **Bootstrap**.
* Built-in **CI/CD workflows** with GitHub Actions.
* Unit and integration tests with **Vitest**.

---

## Tech Stack

| Category           | Technology                       |
| ------------------ | -------------------------------- |
| Frontend           | Nuxt 3, Vue 3, TypeScript        |
| State Management   | Pinia / Vuex                     |
| Forms & Validation | VeeValidate / Custom Handling    |
| Icons              | Font Awesome / Custom SVGs       |
| Animations         | Vue Transitions / CSS Animations |
| DevOps / CI        | GitHub Actions                   |
| Testing            | Vitest, Vue Test Utils           |
| Build Tool         | Vite                             |

---

## Project Structure

```
CommonShare-technical-assessment/
├── .github/workflows/    # GitHub Actions CI/CD workflows
├── app/                  # Vue components / pages
│   ├── app.vue
│   ├── dashboard.vue
│   └── users.vue
├── plugins/              # Nuxt plugins
├── public/               # Static assets (favicon, robots.txt, users.json)
├── tests/                # Unit & integration tests
│   ├── app.test.ts
│   └── setup.ts
├── nuxt.config.ts        # Nuxt configuration
├── package.json          # Project metadata & scripts
├── tsconfig.json         # TypeScript configuration
├── vitest.config.ts      # Vitest configuration
└── README.md             # Project documentation
```

---

## Installation

```bash
# Clone the repository
git clone https://github.com/ongunakaycom/Nuxtify.git
cd Nuxtify

# Install dependencies
npm install

# Run in development mode
npm run dev
```

---

## Running Tests

```bash
npm run test
```

---

## Build for Production

```bash
npm run build
npm run preview
```

---

## GitHub Actions (CI/CD)

The project uses GitHub Actions to:

* ✅ Run build and lint checks on pull requests
* 🧪 Run tests automatically
* 🚀 Deploy to platforms like Netlify, Vercel, or GitHub Pages

**Sample workflow (`.github/workflows/ci.yml`):**

```yaml
name: Nuxt CI/CD

on:
  push:
    branches: [main]
  pull_request:
    branches: [main]

jobs:
  build-and-test:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - name: Setup Node
        uses: actions/setup-node@v4
        with:
          node-version: '18'
      - run: npm install
      - run: npm run build
      - run: npm run test
```

---

## Contribution

Contributions, PRs, and feedback are welcome!
Feel free to **fork**, **improve**, or **experiment** with the project.

---

## License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

---

## About Me

Hi, I’m **Ongun Akay**, a Senior Full-Stack Developer specializing in frontend and backend technologies.

* 🌐 Website: [ongunakay.com](https://ongunakay.com)
* 💼 LinkedIn: [linkedin.com/in/ongunakay](https://linkedin.com/in/ongunakay)
* 🧑‍💻 GitHub: [github.com/ongunakaycom](https://github.com/ongunakaycom)
* 📬 Email: [info@ongunakay.com](mailto:info@ongunakay.com)

I’m always open to **collaborations**, challenging projects, and opportunities to improve my skills.


# GitHub Portfolio

### If you're struggling to create a portfolio website that looks professional, you don't have to search any further. You can use this GitHub Portfolio template to create your very own personalized portfolio using just your GitHub username! The website is designed to be user-friendly and easily customizable, which makes it an ideal solution for developers and freelancers alike.

---

## View live preview [here](https://my-github-portfolio.netlify.app/)

---

# Installation :arrow_down:

### You will need to download Git and Node to run this project

- [Git](https://git-scm.com/downloads)
- [Node](https://nodejs.org/en/download/)

#### Make sure you have the latest version of both Git and Node on your computer.

```
node --version
git --version
```

## <br />

# Getting Started :dart:

### Fork and Clone the repo

To Fork the repo click on the fork button at the top right of the page. Once the repo is forked open your terminal and perform the following commands

```
git clone https://github.com/anandk008/github-portfolio.git

cd github-portfolio
```

### Install packages from the root directory

```bash
npm install
# or
yarn install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

---

# Usage :joystick:

If you want to use Google Analytics, Please create a new `.env` file from `.env.example` file and provide the value.

Eg:

```env
NEXT_PUBLIC_GTM = ""
```

### Now, you have to customize user data in the `data` [folder](https://github.com/anandk008/developer-portfolio/tree/main/data).

Eg:

```javascript
export const userData = {
  githubUser: 'anandk008',
  devUsername: "anandk008",
  github: 'https://github.com/anandk008',
  instagram: 'https://www.instagram.com/anand_kadale_/',
  linkedIn: 'https://www.linkedin.com/in/anandk008/',
  geeksforGeeks: 'https://auth.geeksforgeeks.org/user/anandk008',
  codeChef: 'https://codechef.com/users/anand_008',
  leetcode: "https://leetcode.com/anand_008/",
  resume: "https://drive.google.com/file/d/1GXKQoVyiLu8i-OX1fEhaai7j9K_6nW0t/view?usp=sharing",
  skills: ['C','C++','HTML', 'CSS','JavaScript', 'NodeJS', 'ReactJS', 'Git', 'GoLang', 'Python', 'Docker', 'Kubernetes'],
  timezone: '+5'
};
```

---

---

# Packages Used :package:

|   Used Package List   |
| :-------------------: |
|         next          |
|  @next/third-parties  |
|         axios         |
|      react-icons      |
| react-github-calendar |
|         sass          |
|      tailwindcss      |

---

## Disclaimer

In this repository, I have used some open source APIs. All credits go to the owners of those repositories.

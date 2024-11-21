# [WebShell | Terminal Portfolio Website](https://terminal.vokave.com/)

> Forked from [https://github.com/nasan016/webshell](https://github.com/nasan016/webshell)

![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

## Features

- **[Tab]** for auto completion.
- **[Esc]** to clear the input line.
- **[↑][↓]** to scroll through your command history.

## Configuration

Most of the configuration is done in the `config.json` file.

> Generate ascii [here](https://patorjk.com/software/taag/). ANSI Shadow is the current font family.

```json
{
  "ascii": [
    "░▒▓█▓▒░░▒▓█▓▒░░▒▓██████▓▒░░▒▓█▓▒░░▒▓█▓▒░░▒▓██████▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓████████▓▒░ ",
    "░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░        ",
    " ░▒▓█▓▒▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒▒▓█▓▒░░▒▓█▓▒░        ",
    " ░▒▓█▓▒▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓███████▓▒░░▒▓████████▓▒░░▒▓█▓▒▒▓█▓▒░░▒▓██████▓▒░   ",
    "  ░▒▓█▓▓█▓▒░ ░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░ ░▒▓█▓▓█▓▒░ ░▒▓█▓▒░        ",
    "  ░▒▓█▓▓█▓▒░ ░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░ ░▒▓█▓▓█▓▒░ ░▒▓█▓▒░        ",
    "   ░▒▓██▓▒░   ░▒▓██████▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░  ░▒▓██▓▒░  ░▒▓████████▓▒░ "
  ],
  "repoLink": "https://github.com/dabit3/terminal-portfolio",
  "social": {
    "email": "viggo@vokave.com",
    "github": "vise",
    "linkedin": "viggos",
    "twitter": "0xViggos",
    "phaver": "viggos",
    "orb": "viggos",
    "lens.protocol": "viggos.lens"
  },
  "aboutGreeting": "Hi I'm Viggo. I'm a full stack product engineer specializing in high impact developer marketing.",
  "projects": [
    [
      "React Native AI",
      "Full stack framework for building cross-platform mobile AI apps.",
      "https://github.com/dabit3/react-native-ai"
    ],
    [
      "React Native Elements",
      "Cross-Platform React Native UI Toolkit.",
      "https://github.com/react-native-elements/react-native-elements"
    ]
  ]
}
```

## Run the Project Locally:

Clone the repository

```shell
git clone https://github.com/nasan016/webshell.git
```

Go to the project directory

```shell
cd webshell
```

Install the dependencies

```shell
npm install
```

Start the server

```shell
npm run dev
```

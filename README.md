Skip to content
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 
@GGstudio420 
oGranny
/
readme-template-extension
1
06
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
readme-template-extension/snippets/snippets.code-snippets
@oGranny
oGranny edited readme
Latest commit fd21efb on 21 Oct 2020
 History
 1 contributor
185 lines (185 sloc)  7.82 KB
  
{
    "github md template": {
        "prefix": "!!!",
        "body": [
            "<!--",
            "repo name: ${1:BEST-README}",
            "description: ${2:An awesome README template to jumpstart your projects!}",
            "github name: ${3: oGranny}",
            "link: ${4:LINK}",
            "logo path: ${5:assets/logo.png}",
            "screenshot: ${6:assets/ss.png}",
            "twitter: ${7:your_username}",
            "email: ${8:example@email.com}",
            "-->",
            "",
            "<!-- PROJECT SHIELDS -->",
            "[![Contributors][contributors-shield]][contributors-url]",
            "[![Forks][forks-shield]][forks-url]",
            "[![Stargazers][stars-shield]][stars-url]",
            "[![Issues][issues-shield]][issues-url]",
            "[![MIT License][license-shield]][license-url]",
            "[![LinkedIn][linkedin-shield]][linkedin-url]",
            "",
            "",
            "",
            "<!-- PROJECT LOGO -->",
            "<br />",
            "<p align=\"center\">",
            "\t<a href=\"$4\">",
            "\t\t<img src=\"$5\" alt=\"Logo\" width=\"80\" height=\"80\">",
            "\t</a>",
            "\t<h3 align=\"center\">$4</h3>",
            "\t<p align=\"center\">",
            "\t\t$1",
            "\t\t<br />",
            "\t\t<a href=\"$4\"><strong>Explore the docs �</strong></a>",
            "\t\t<br />",
            "\t\t<br />",
            "\t\t<a href=\"${https://github.com/$1/$3}\">View Demo</a>",
            "\t\t�",
            "\t\t<a href=\"$4/issues\">Report Bug</a>",
            "\t\t�",
            "\t\t<a href=\"$4/issues\">Request Feature</a>",
            "\t</p>",
            "</p>",
            "",
            "",
            "",
            "<!-- TABLE OF CONTENTS -->",
            "## Table of Contents",
            "",
            "* [About the Project](#about-the-project)",
            "\t* [Built With](#built-with)",
            "* [Getting Started](#getting-started)",
            "\t* [Prerequisites](#prerequisites)",
            "\t* [Installation](#installation)",
            "* [Usage](#usage)",
            "* [Roadmap](#roadmap)",
            "* [Contributing](#contributing)",
            "* [License](#license)",
            "* [Contact](#contact)",
            "* [Acknowledgements](#acknowledgements)",
            "",
            "",
            "",
            "<!-- ABOUT THE PROJECT -->",
            "## About The Project",
            "",
            "[![Product Name Screen Shot][product-screenshot]]($6)",
            "",
            "${There are many great README templates available on GitHub, however, I didn't find one that really suit my needs so I created this enhanced one. I want to create a README template so amazing that it'll be the last one you ever need.}",
            "",
            "Here's why:",
            "* Your time should be focused on creating something amazing. A project that solves a problem and helps others",
            "* You shouldn't be doing the same tasks over and over like creating a README from scratch",
            "* You should element DRY principles to the rest of your life :smile:",
            "",
            "Of course, no one template will serve all projects since your needs may be different. So I'll be adding more in the near future. You may also suggest changes by forking this repo and creating a pull request or opening an issue.",
            "",
            "A list of commonly used resources that I find helpful are listed in the acknowledgements.",
            "",
            "### Built With",
            "This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.",
            "* [Bootstrap](https://getbootstrap.com)",
            "* [JQuery](https://jquery.com)",
            "* [Laravel](https://laravel.com)",
            "",
            "",
            "",
            "<!-- GETTING STARTED -->",
            "## Getting Started",
            "",
            "This is an example of how you may give instructions on setting up your project locally.",
            "To get a local copy up and running follow these simple example steps.",
            "",
            "### Prerequisites",
            "",
            "This is an example of how to list things you need to use the software and how to install them.",
            "* npm",
            "```sh",
            "npm install npm@latest -g",
            "```",
            "",
            "### Installation",
            "",
            "1. Get a free API Key at [https://example.com](https://example.com)",
            "2. Clone the repo",
            "```sh",
            "git clone https://github.com/your_username_/Project-Name.git",
            "```",
            "3. Install NPM packages",
            "```sh",
            "npm install",
            "```",
            "4. Enter your API in `config.js`",
            "```JS",
            "const API_KEY = 'ENTER YOUR API';",
            "```",
            "",
            "",
            "",
            "<!-- USAGE EXAMPLES -->",
            "## Usage",
            "",
            "Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.",
            "",
            "_For more examples, please refer to the [Documentation]($4)_",
            "",
            "",
            "",
            "<!-- ROADMAP -->",
            "## Roadmap",
            "",
            "See the [open issues]($1/issues) for a list of proposed features (and known issues).",
            "",
            "",
            "",
            "<!-- CONTRIBUTING -->",
            "## Contributing",
            "",
            "Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.",
            "",
            "1. Fork the Project",
            "2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)",
            "3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)",
            "4. Push to the Branch (`git push origin feature/AmazingFeature`)",
            "5. Open a Pull Request",
            "",
            "",
            "",
            "<!-- LICENSE -->",
            "## License",
            "",
            "Distributed under the MIT License. See `LICENSE` for more information.",
            "",
            "",
            "",
            "<!-- CONTACT -->",
            "## Contact",
            "",
            "Your Name - [@$7](https://twitter.com/$7) - $8",
            "",
            "Project Link: [$4]($4)",
            "",
            "",
            "",
            "<!-- MARKDOWN LINKS & IMAGES -->",
            "<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->",
            "[contributors-shield]: https://img.shields.io/github/contributors/$3/$1.svg?style=flat-square",
            "[contributors-url]: https://github.com/$3/$1/graphs/contributors",
            "[forks-shield]: https://img.shields.io/github/forks/$3/$1.svg?style=flat-square",
            "[forks-url]: https://github.com/$3/$1/network/members",
            "[stars-shield]: https://img.shields.io/github/stars/$3/$1.svg?style=flat-square",
            "[stars-url]: https://github.com/$3/$1/stargazers",
            "[issues-shield]: https://img.shields.io/github/issues/$3/$1.svg?style=flat-square",
            "[issues-url]: https://github.com/$3/$1/issues",
            "[license-shield]: https://img.shields.io/github/license/$3/$1.svg?style=flat-square",
            "[license-url]: https://github.com/$1/$3/blob/master/LICENSE.txt",
            "[product-screenshot]: $6",
            "",
        ],
        "description": "readme template",
        "scope": "markdown",
    }
}
© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
Loading complete

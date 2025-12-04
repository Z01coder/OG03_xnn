<!-- Improved compatibility of Back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>



<!-- LANGUAGE SWITCHER -->
<div align="right">
  <strong>Language:</strong> <a href="README.en.md">English</a> | <a href="README.md">Русский</a>
</div>




<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->




<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h1 align="center">Debuger</h3>

  <p align="center">
    Arcade game on Python using Pygame library
    <br />
  </p>
</div>

<div align="center">
  <img src="img/dbg.gif" alt="Debuger" />
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About the Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#development-screenshots">Development Screenshots</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About the Project

"Debuger" is an arcade game created in Python using the Pygame library. It is a reimagined version of a shooting gallery game, inspired by the scientific meme about the origin of the term "bug". In this game, you play as a "debugger" fighting bugs that are trying to stick to a printed circuit board. The goal is to eliminate as many bugs as possible within a limited time.

<details>
  <summary><strong>Project Goals and Objectives</strong></summary>

**Goals:**
* Create an engaging arcade game with simple gameplay
* Demonstrate the capabilities of the Pygame library for game development
* Implement game mechanics with a timer and score counting
* Create a visually appealing retro-style interface

**Key Objectives:**
* Develop a game loop with mouse event handling
* Implement a hit counting system and statistics display
* Create an intro screen with the ability to transition to the game
* Integrate sound effects and background music
* Implement a system for random target appearance on screen
* Add a timer to limit game time (30 seconds per round)
* Create a system for displaying current and previous records

</details>

<details>
  <summary><strong>Results</strong></summary>

**Implemented Functionality:**
* Intro screen with image, transition to game on mouse click
* Gameplay with clicking on bugs on the circuit board
* Real-time hit counting system
* Game timer (30 seconds per round)
* Display of current and previous records
* Random target appearance in different screen locations
* Sound effects on hit
* Background music during gameplay
* Random background color changes between rounds

**Created Components:**
* Main game file `main.py` with complete game loop
* System for loading and displaying images (intro, background, targets)
* Mouse event handling for hit detection
* Timer and round management system
* Integration of sound effects and music through Pygame Mixer

</details>

<p align="right">(<a href="#readme-top">Back to top</a>)</p>



### Built With

Main technologies and libraries used in the project:

* [![Python][Python-badge]][Python-url]
* [![Pygame][Pygame-badge]][Pygame-url]

Additional dependencies:
* `pygame>=2.0.0` - library for creating games and multimedia applications

<p align="right">(<a href="#readme-top">Back to top</a>)</p>



<!-- GETTING STARTED -->
<details>
  <summary><strong>Getting Started</strong></summary>

Instructions for installing and running the game locally.

### Prerequisites

To work with the project, you need to install:

* Python 3.x
  ```sh
  # Check Python version
  python --version
  ```

### Installation

Below are instructions for installing and running the game.

1. Clone the repository
   ```sh
   git clone https://github.com/Z01coder/Debuger-game.git
   cd Debuger-game
   ```

2. Create a virtual environment (recommended)
   ```sh
   python -m venv venv
   # Windows
   venv\Scripts\activate
   # Linux/Mac
   source venv/bin/activate
   ```

3. Install dependencies
   ```sh
   pip install -r requirements.txt
   ```

4. Run the game
   ```sh
   python main.py
   ```

5. Game controls:
   - On the intro screen, click the mouse to start the game
   - In the game, click on bugs appearing on the screen
   - Each hit counts as a point
   - A round lasts 30 seconds, after which the game restarts
   - Your previous record is saved and displayed in the top right corner

</details>

<p align="right">(<a href="#readme-top">Back to top</a>)</p>



<!-- USAGE EXAMPLES -->
<details>
  <summary><strong>Usage</strong></summary>

The game provides simple and engaging gameplay:

### Gameplay:

1. **Intro Screen**
   - When you start the game, an intro screen with the game title is displayed
   - Click the mouse anywhere on the screen to start the game

2. **Main Gameplay**
   - Bugs (targets) appear on the screen in random locations
   - Click on bugs to earn points
   - Each hit is accompanied by a sound effect
   - Background music plays during the game

3. **Scoring System**
   - Current number of hits is displayed in the top left corner
   - Previous record is displayed in the top right corner
   - After completing a round (30 seconds), the current result becomes the previous record

4. **Features:**
   - Bugs appear in random screen locations after each hit
   - Game background changes color randomly between rounds
   - Various bug images are used for variety

</details>

<p align="right">(<a href="#readme-top">Back to top</a>)</p>



<!-- DEVELOPMENT SCREENSHOTS -->
<details>
  <summary><strong>Development Screenshots</strong></summary>

Below are screenshots of the game development process:

![Development Screenshot 1](img/devscr1.png)
![Development Screenshot 2](img/devscr2.png)
![Development Screenshot 3](img/devscr3.png)
![Development Screenshot 4](img/devscr4.png)
![Development Screenshot 5](img/devscr5.png)
![Development Screenshot 6](img/devscr6.png)

</details>

<p align="right">(<a href="#readme-top">Back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

<details>
  <summary><strong>Show completed development stages</strong></summary>

### Completed Stages:

- [x] **Stage 1: Basic Project Structure**
  - [x] Creating the main `main.py` file
  - [x] Initializing Pygame and setting up the game window
  - [x] Setting screen dimensions (1280x720)

- [x] **Stage 2: Resource Loading**
  - [x] Loading background map image
  - [x] Loading intro image
  - [x] Loading target images (bugs)
  - [x] Loading application icon

- [x] **Stage 3: Intro Screen**
  - [x] Implementing intro screen display
  - [x] Handling mouse click to transition to game
  - [x] Handling window close on intro screen

- [x] **Stage 4: Main Game Loop**
  - [x] Implementing main game loop
  - [x] Handling window close events
  - [x] Handling mouse clicks

- [x] **Stage 5: Hit System**
  - [x] Determining hit on target when clicking
  - [x] Counting number of hits
  - [x] Moving target to random location after hit
  - [x] Random selection of target image

- [x] **Stage 6: Timer and Rounds**
  - [x] Implementing game timer (30 seconds)
  - [x] Automatic round restart after time expires
  - [x] Saving previous record

- [x] **Stage 7: Statistics Display**
  - [x] Displaying current number of hits
  - [x] Displaying previous record
  - [x] Setting font and text color

- [x] **Stage 8: Sound Effects**
  - [x] Integrating Pygame Mixer for sound work
  - [x] Loading and playing background music
  - [x] Adding sound effect on hit
  - [x] Setting sound volume

- [x] **Stage 9: Visual Effects**
  - [x] Random background color changes between rounds
  - [x] Displaying background map image
  - [x] Displaying targets on screen

</details>

### Planned Improvements:

- [ ] Adding difficulty level system
- [ ] Implementing leaderboard
- [ ] Adding different bug types with different point values
- [ ] Implementing bonus and special effects system
- [ ] Adding animations for bugs
- [ ] Improving visual effects on hit
- [ ] Adding settings menu (volume, screen resolution)
- [ ] Implementing achievements system
- [ ] Adding game pause
- [ ] Creating mobile version

<p align="right">(<a href="#readme-top">Back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">Back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">Back to top</a>)</p>



<!-- CONTACT -->
## Contact

* [![GitHub][GitHub-badge]][GitHub-url]
* [![Gmail][Gmail-badge]][Gmail-url]
* [![Telegram][Telegram-badge]][Telegram-url]

<p align="right">(<a href="#readme-top">Back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

I express sincere gratitude to [Zerocoder](https://zerocoder.ru/) University and its entire team for creating an inspiring and professional educational environment. For preparing "IT-astronauts" at the Zerocoder "cosmodrome".

Special thanks to:

[Kirill Pshinnik](https://kpshinnik.ru/), the university director, for inspiring achievements;

Teachers [Nina Stefantsova](https://neural-courses.ru/teacher/nina-stefancova/), [Maxim Vershinin](https://neural-courses.ru/teacher/maksim-vershinin/), and [Darya Bobrovskaya](https://neural-courses.ru/teacher/darya-bobrovskaya/) — for deep knowledge, patience, and willingness to always help;

Nikita Murkin, course curator, for clear organization and mentoring;

Elizaveta, manager, for care, efficiency, and constant friendliness.

Thanks to you, this project became possible!

<p align="right">(<a href="#readme-top">Back to top</a>)</p>



<!-- GRACE HOPPER -->
<details>
  <summary><strong>Grace Hopper</strong></summary>

<div align="center">
  <img src="img/image.webp" alt="Grace Hopper" />
  <p><strong>Grace Hopper</strong></p>
</div>

Grace Murray Hopper (1906-1992) was an American computer scientist and rear admiral in the United States Navy. She was one of the first programmers of the Harvard Mark I computer and developed the first compiler for a computer programming language.

Hopper popularized the idea of machine-independent programming languages, which led to the development of COBOL, one of the first high-level languages. She is also known for finding the first "bug" in a computer — an actual moth stuck in a relay of the Mark II computer in 1947. This incident became the source of the term "debugging" in programming.

Throughout her outstanding career, Grace Hopper received numerous awards and honorary titles, including the National Medal of Technology and Innovation of the United States. She remains an inspiring figure in the history of computer science and a symbol of female leadership in technology.

</details>

<p align="right">(<a href="#readme-top">Back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[Python-badge]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://www.python.org/
[Pygame-badge]: https://img.shields.io/badge/Pygame-FF6F00?style=for-the-badge&logo=pygame&logoColor=white
[Pygame-url]: https://www.pygame.org/
[GitHub-badge]: https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white
[GitHub-url]: https://github.com/Z01coder
[Gmail-badge]: https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white
[Gmail-url]: mailto:zolotuxin.alexey@gmail.com
[Telegram-badge]: https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white
[Telegram-url]: https://t.me/AZVXAN


# 💿 final project

For your final project in this class, you will code a C++ project from scratch, outside of zyBooks. You have a few options for this assignment, and you'll need to choose 1 of the following:

1. [🛡 Text-Based Adventure Game](#text-based-adventure-game)
2. [🧊 QR Code Generator](#qr-code-generator)
3. [🎨 Your Own Design](#your-own-design)

There are specific requirements for each option, but all of your final projects will require:

- Work in pairs. Collaboration and [pair programming](https://www.newyorker.com/magazine/2018/12/10/the-friendship-that-made-google-huge) are important skills to learn! Choose someone in your same Friday lab section (either CC1 or CC2) so that you can use that time and space to work together.

- Each person will need to write a short (~500 word) statement about the division of labor between you and your partner, and some brief reflections on how the project synthesizes what you have learned in this class.

- Your code will be evaluated on the specific requirements for each project, as well as _style_: is your code legible? Do you have **comments** that help your fellow programmers understand your work? Do you use loops to avoid repetition, efficient `if/else` statements, vectors or linked lists when necessary, and multiple files when you are writing classes? Have you developed a unique and elegant way of solving the problem or creating the project?

- For this project, you are allowed to use outside sources to incorporate into your code. However, you will need to **cite these sources** specifically in code comments - see more information [here](https://github.com/mab253/cpp_spring26/blob/main/ai-citations.md). **When in doubt, cite!** And please reach out to ask if you have questions about this requirement.

## Text-Based Adventure Game

Create a text-based game, in the style of [Colossal Cave Adventure](https://grack.com/demos/adventure/). You will need to create your own storyline, write text-based prompts for your user to navigate the game, and write an ending (or multiple endings) for your user's character.

This is a very open-ended project, but your code must include the following:
- at least 15 functions that you write, outside of `main`
- at least 2 classes, and multiple instances of creating objects of those classes
- at least 1 game-within-a-game, where your user must play a game or complete a task using `rand()`, the psuedo-random number generator
- at least 2 variables that changes with your user throughout the gameplay (for example: a score; an inventory of things they are holding; etc.) - and we should have the option to see an output of this score, inventory, etc.
- at least 2 instances of [ASCII art](https://www.asciiart.eu/)
- at least 20 "locations," or decision/branch points, for your users to navigate *

*The game does not have to be as long as Colossal Cave Adventure (there are 140 map "locations" in that game, when the user gets a chance to make a decision!), but this game should be an involved, significant experience to build and to play; it should take us more than 5 minutes to get through the action. Stretch yourself - creativity and any added features here will be rewarded!

A few examples: your user is an astronaut exploring Mars, and she finds a locked safe in a crater and needs to crack the combination to open the safe as part of the mission; OR your user gets a new job counting rats in NYC subway tunnels, and needs to guess which train is coming first to avoid danger; OR your user is a student studying in the CCNY library, who finds a book with a note in it, which leads them to a party where they have to play [Blackjack](https://en.wikipedia.org/wiki/Blackjack) at the door in order to get in; OR your user is starting a garden, and they have to respond to random acts of weather by choosing the right tools and actions; OR your user is a shipwrecked stray cat and they have to find their way home, including picking up items on an island and guessing a password in order to stow away on a pirate ship; etc. etc ... this is a chance to be creative and explore a story that you enjoy. You could also check out [_Choose Your Own Adventure_ books](https://samizdat.co/cyoa/books/) for inspiration.

## QR Code Generator

Create a program that generates QR codes in the terminal. Your QR ("quick-response") generator should take an input string, convert that string into binary data, and then display that data as a grid in the terminal. It should also be able to receive QR output from your system as input, and then decode that data back into plaintext.

Your code must include the following:
- at least 1 class
- write at least 10 functions outside of `main` to perform your tasks
- you need to encode a creative, unique signature in the QR output; this signature should not interfere with the ability to decode the plaintext message
- somewhere in your program's output, you should explain this unique signature to your users
- your user should have the option to download the QR encoded output to a txt file (check out [zyBooks 9.7](https://learn.zybooks.com/zybook/CUNYCSC10300BlountSpring2026/chapter/9/section/7)
- include a `checksum` function, that runs after your user input string and makes sure that the QR output has the same `checksum` result; show this `checksum` result to your user*
- you may need to research some new methods in order to solve these problems - make sure to [cite your sources](https://github.com/mab253/cpp_spring26/blob/main/ai-citations.md)!
- you might want to start this research with [this video](https://www.youtube.com/watch?v=w5ebcowAJD8)

*what's a `checksum`? It is a simple function that helps ensure your data hasn't been corrupted. If you run the input text through the function and the output encoded QR through the same function, the output should give the same result. These can be quite simple or incredibly complex ... I would suggest with starting simple with the `checksum`. Focus on designing a function that works for your program, no need to implement advanced error correction algorithms.

*note that the goal of this project is to use principles we have learned in this class to develop a unique graphical way of representing binary data ... NOT going off to find a library where someone else has already done the work of creating QR codes!

How will you display your encoded data in the output? Creativity and any added features here will be rewarded!

## Your Own Design

Do you have a project idea that you and your partner really want to build? (Maybe something with [openFrameworks](https://openframeworks.cc/), something with [raylib](https://www.raylib.com/), something like the "mini LLM" AI we made in class, something with physical computing like Arduino, maybe something with cryptography?) You can send me your idea via e-mail or Discord by Friday **May 1st,** and I will either approve it or suggest changes in scope/difficulty.

## Due Dates

1. First milestone: choose your project (1, 2, or your own idea) and your partner from your lab section **by Friday May 1st.** You will need to fill out [this form](https://airtable.com/appbqrZUDUsULkaDS/shrCdAh6tbOMoCWYV) to share your project choice and your partner by 11:59pm on May 1. **Note:** on 👈 this form, if you would like me to match you with a partner, you can choose this preference.

2. Final project delivery, including short reflection texts and code, due **Monday, May 18th** @ 11:59pm. I will share a submission form and requirements closer to this due date.

## important notes

- **No late work accepted for final projects.** It's too close to when final grades are due! If you have an accomodation, _you need to tell me this beforehand_.
- **Remember to add comments and [CITE YOUR SOURCES!](https://github.com/mab253/cpp_spring26/blob/main/ai-citations.md)**
- [Academic honesty](https://github.com/mab253/cpp_spring26#academic-honesty-and-integrity), as always, applies to this assignment - even more so as this should represent your own work, as this is not a lab/practice problem. Violations of the academic honesty policy will have serious consequences, _including but not limited to failing this course_. **Do not plagiarize writing or code!**

### partner matches:
(05/04/2026)

Zeqin C - Brandon C.
Jean S - Matthew D.
Zahra H - Samantha G.
Robert C - Daniel A.
Kelvin O - Justin G
Eduarda R. - Alexis P.
Arham S. - Azeez S.
Tao R. - Josiah W. 
Hsu Y - Juliet J
Zilong L.Y. - Le Tian F.W.
Haroon A. - Colin R.
Rafia T. - Zakai M. - Muhammad H. 
Antony J. - Marcos O. 
Faysal R. - Luis F.

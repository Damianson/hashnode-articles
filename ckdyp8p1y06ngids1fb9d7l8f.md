## Walks Like Python, Runs Like C

Somewhere on Earth,  
A Time-Space,  
var PublicationDate.

Hello Readers,

I'm delighted that you're here to read the first entry in this series, hop on 🚀.
*****
You're a data scientist you analyze chunks of data, you're a scientist and you use computers and programming languages to aid your research, you're a beginner that wants to learn a programming language or you're a programmer that wants to learn a general purpose language, well welcome to the world of Julia!
![Yes! Julia](https://res.cloudinary.com/damianson/image/upload/v1597673740/J31n_yeyxa7.gif)

So what is Julia? Julia's documentation presented it as such:

> It is a flexible dynamic language, appropriate for scientific and numerical computing, with performance comparable to traditional statically-typed languages.

Python programmers know how slow it is sometimes when performing complex numerical computations. Well, hello Julia! Once you understand Julia it'll be easy to write code that is nearly as fast as C. Yup you heard that right. Now you'll probably understand
> Walks like Python. Runs like C.

Julia is greatly influenced by Python so it's syntax is easy to understand and a well written code runs with almost as much speed as C (cool right?)
### GETTING STARTED WITH JULIA
The easiest way to run Julia codes is by starting an interactive session ( aka REPL). This can be done by launching the Julia executable or running `julia` from the command line. With this you can try Julia code bits without saving them.
To exit the interactive session you can press CTRL-D or simply type `exit()`. You can also try Julia online at [repl.it](https://repl.it/@logankilpatrick/TryJulia#main.jl) to run codes online without installing Julia on your local machine.
#### INSTALLING JULIA
This part will be really short. Why? Getting up and running with Julia is really easy! You can download Julia from [Julia's download page](https://www.julialang.org/downloads/). At the time this article was written the current stable release was version 1.5.0. I'll recommend you always download the current stable release. 
![current stable.PNG](https://res.cloudinary.com/damianson/image/upload/e_sharpen:400/v1597673913/current_stable_cpk5g4.png)
After downloading, the installation is also straightforward. You can find the installation instructions for Windows, MacOS, Linux and FreeBSD [here](https://julialang.org/downloads/platform/). Remember to follow the instructions for adding Julia to PATH on Windows or create a symlink if you're on MacOS or Linux. Doing this will enable us to start a Julia repl or run Julia commands directly from the terminal. Julia can also be installed using Chocolatey
```
choco install julia --confirm
``` 
 With this you can run julia directly from the terminal by typing `julia` + enter. If you use the HomeBrew package manager you can run  
```
brew cask install julia
```
This automatically adds Julia to the user's PATH so the user can run Julia from the terminal.
#### HELLO WORLD
It has become somewhat of a culture to start off a new language with a simple "Hello World", we can also use this to test our installation. So, let's hop on it shall we? 😏
##### **"Hello World!" in a terminal session**
To run our Hello World program in a terminal session, simply open your terminal and run
```
julia
```
The Julia REPL will launch
![julia repl.PNG](https://res.cloudinary.com/damianson/image/upload/v1597674355/julia_repl_aggcnj.png)
*(Yes! Julia was installed perfectly. If you didn't get the same result then Julia might've not been installed correctly, you can go to their downloads page and try again or you can ask your questions about the installation via [Julia's Discourse](https://discourse.julialang.org/))*

Then run
```
print("Hello World!")
```

![hello julia.PNG](https://res.cloudinary.com/damianson/image/upload/v1597679455/hello_julia_crbkqj.png)
Yay, you've just written your first Hello World program in Julia.😎
##### **"Hello World!" in a code editor**
Open any code editor. Create a new file and name it helloworld.jl (".jl" is the file extension for Julia programs).
Then edit the file and type
```
print("Hello World!")
```
![hellojuliavscode.PNG](https://res.cloudinary.com/damianson/image/upload/e_sharpen:100/v1597673565/hellojuliavscode_zeu0jh.png)
save the file.  
Open your terminal, navigate to the directory where your file was saved if you're not in the directory. In my case my file was saved in a folder called "julia" under "programming resources".
You can just go to the place where your file was saved, copy the file path and run
```
cd FILE_PATH
```
replace `FILE_PATH` with the path to your file.
After that, run
```
julia helloworld.jl
```

![juliafromfile.PNG](https://cdn.hashnode.com/res/hashnode/image/upload/v1597671956233/-cJzGiiFL.png)
Sweet! 😋You've successfully written your first Julia program from a code editor.  
The code editor I'm using is Visual Studio Code with the Julia extension installed. Julia also has extensions or plugins for Atom, Jupyter, IntelliJ IDEA, Vim, Emacs, Sublime Text and Notepad++ you can go to [julialang.org](https://julialang.org/) to learn more. Also visit [julialang.org](https://julialang.org/) to learn more about Julia's ecosystem in Visualization, General Purpose, Data Science, Machine Learning, Scientific Domains and Parallel Computing.  
In my next letter(Yes, Article), We'll learn about Variables in Julia. Sign up for my newsletter to get updates on my next article.  
  
Your Loving Language,  
Julia.



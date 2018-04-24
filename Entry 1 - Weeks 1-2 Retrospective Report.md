## Entry 1 - Weeks 1-2 Retrospective Report

*Note: The first and second weeks are documented in a single report as I did not write the first week's report on-schedule.*

​	In the two weeks since my residency I've started my first project in Python, in which I've been introduced to two new libraries, a simple scripting language used for writing keyboard macros called AutoHotKey, and got some experience applying coding to a real-world application. In addition to the technical work, I've also learned more about software design from a user-experience/*UX* perspective, and added to my list of projects for the future.

### Week One

​	Week one began with my return home from Vermont, and the work that I did during week one was primarily exploring *jupyter* notebooks using *nteract*, an interactive text editor that allows me to cleanly write text alongside blocks of live, editable code. This format encourages exploration much more than plain text or command line interfaces, and I've really enjoyed exploring the different ways that I can use it. Learning the notebook format has also taught me how to write in *markdown*, a minimal text formatting language related to HTML, which emphasizes simplicity and readability in a way that I find somewhat reminiscent of Python's own emphasis on simplicity and readability.

Here, I'll discuss in greater detail the more noteworthy things I did this week:

- **Jupyter/iPython Notebooks** - From now on in these journal entries, I'll refer to these as "notebooks" for simplicity's sake. Notebooks are markdown based documents that can display blocks of code inline with formatted text that are able to run the code and display live output in the form of text, audio, images, animations, interactive elements, video, and much more. They can be viewed and edited using a web browser or desktop software on Mac, PC, and Linux, as well as many mobile platforms.  

  ​	Notebooks can be a very powerful and versatile tool for presenting ideas and work in the form of computational essays and also as a means of rapid experimentation and prototyping. Each separate block of code runs independently of the others though shares values such as variables, imported modules, and functions. This means that if I have a bug in one code block which causes it to return an error message, the others can still run on their own. During the scripting process, the ability to break down computational problems into a modular subset of simpler problems which can be solved independently makes the whole process much more intuitive. Then, once each sub-problem is solved, it's just a matter of taking the modular blocks of code and tying them together. This has made coding much more intuitive to me, turning what used to feel like searching for needles in an endless haystack, into an enjoyable and intuitive process that can be applied to solving a variety of problems. 

  ​	Notebooks are also a very useful format to use when writing computational essays, wherein there will be both text which has to be easy to read for a human audience and modular computer code in a variety of languages.


- **Markdown** - This journal is actually being written in markdown as I type, though it may later be exported to a PDF or Word document; just a relevant note. Before this week I had heard of markdown as it is used to format comments on the social content sharing site *Reddit*, but up until this week I really only knew how to write in italics. I'm now at least familiar enough to write this essay which includes an image and a couple of headings, lists, and text styles. I've already really started to like writing in markdown because of the fact that it's a pretty distraction-free work experience. Below is a live screenshot of my desktop as I write this: 

  ​

  ![1524539613435](C:\Users\CAEDON~1\AppData\Local\Temp\1524539613435.png)

  ​

   	As you can see, there's really not a whole lot going on onscreen. There's the text, and that's about it. By minimizing the amount of interaction with the graphical interface, markdown makes writing feel extremely 	  smooth. I'm using an especially minimal editor called *Typora* which adds a few shortcuts for things like *italics*, **bold**, <u>and underline</u>, and displays only the text with an option to view both plain-text markdown code, and formatted text as shown above. This minimal, largely text-only interface is common among markdown editors and is what brings a lot of people to markdown as their primary writing tool. This is in stark contrast to my experience in Word document editors such as Word and Google Docs, wherein I regularly have to break my flow of thought in order to interact with the graphical elements. Writing in markdown, my hands barely leave the keyboard. This makes for a pretty dramatic improvement, especially as somebody in particular who tends to struggle with focus and attention. I will likely start doing much more work in notebooks written in markdown using Typora or another minimal editor just because of how simple and enjoyable it is to work this way.

  ​	In week two I am going to start planning and developing my first automation script in Python. The purpose of this script will be to give me the ability to quickly perform a web search for content copied to the clipboard using a keyboard shortcut.

# Intelligent Text

Simple software to help writing texts. It provides insights while the user is writing by searing for articles related to what is being written.

## Requeriments

- [Google Scholar Paper Finder](https://github.com/maikelronnau/google_scholar_paper_finder) - custom search engine
- [rake-nltk](https://github.com/csurfer/rake-nltk) - keyword extractor base
- [TextRank](https://github.com/davidadamojr/TextRank) - keyword extractor
- [Scholar](https://github.com/ckreibich/scholar.py) - search engine base
- [Pyinstaller](http://www.pyinstaller.org/) - to compile the search engine

## How to setup

- Install [Pyinstaller](http://www.pyinstaller.org/)
- Clone [Google Scholar Paper Finder](https://github.com/maikelronnau/google_scholar_paper_finder) repository 
- Compile the script *search_engine.py* using Pyinstaller: *pyinstaller search_engine.py -F*. The compiled file will be under *dist* folder
- Clone this repository, create a folder named *search_engine* in its root directory and put the search engine compiled file inside, under the name *search_engine.exe*
- Open this repository project using NetBeans and build the project
- Get the compiled project inside the folder *store*

## Components

- Java interface
- Python article search engine

### Author

**Maikel Maciel Rönnau**  
*Computer Scientist  
maikel.ronnau@ulbra.edu.br  
[Linkedin](https://br.linkedin.com/in/maikelronnau)*

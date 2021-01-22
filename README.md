# ITV Latex report template

<img src="logos/logo_itv_2021.png" alt="ITV" width="250px"/>

This report template for the Instituto Tecnologico Vale (ITV) has support for:

  - ABNT references
  - Multilingual (Brazilian portuguese and english)
  - Very flexible, including annexes and acronym list!

# How to use

  - ~~Use the already available www.overleaf.com template.~~ This template was disabled temporarly as Overleaf received a take-down notice. :-(
  - Download/clone this repo and use your favorite LaTeX editor!

# Configurations

  - ```\renewcommand{\ITVlocation}{MI}```: ITV localization, it can be DS or MI.
  
  - ```\prodtecnica```: Technical production number, this is given by the ITV library.
    For example:  `\prodtecnica{N001/2077\\DOI:00.00000/PROD.TEC.ITV.Snow}`

  - ```\titulo```: Document title.
    For example: `\titulo{Report Title/Título do relatorio}`

  - ```\nomeprojeto```: project name.
    For example: `\nomeprojeto{Project name/Nome do projeto}`

  - ```\outrossubtitulos{~} % opcional```: Extra subtitles

  - ```\autores```: authors from ITV that participated in the project. The names are separated by a newline or \\.  Ex: Author 1\\Author 2\\Author 3.
    For example: ```\autores{
      Jon Snow\\
      Son Goku\\
      Megaman X7 Maverick\\
      Conan The Barbarian
    }```
  
  - ```\newcommand{\autoresexternos}```: authors from the external partnership. As the previous command, every author is separated by newline or \\. This command is optional and can be disabled by commenting the declaration.
    For example: ```\newcommand{\autoresexternos}{ % optional
      Cleyton Dias\\
      Gabriel Garcia\\
      Jhonson Santos\\
      Robson Gomes
    }```

  - ```\local```: Local of the document, generally it must be "Ouro Preto\\Minas Gerais, Brasil" for ITV MI.
    For example: `\local{Ouro Preto\\Minas Gerais, Brasil}`

  - ```\data```: Date of the document, in month/year format.
    For example: `\data{Março/2020}`

  - ```\parceirologo```: Partner logo, this is optional and can be disabled by commenting the command.
    For example: `\parceirologo{logos/logo_parceiro_base.png} % optional`
    
## Screenshot

<img src="img/examples/screenshot.png" alt="screenshot" width="250px"/>

# Development

Want to contribute? Great! pull request are welcome!

## Future work

  - Cleaner parameter setup
  - Better way for internationalization
    
License
----

MIT
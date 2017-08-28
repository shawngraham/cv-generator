Shawn's CV generator

- based on Steve Miller's 'Make your cv look pretty with markdown' <http://svmiller.com/blog/2016/03/svm-r-markdown-cv/> and uses his latex template
- publications and conference presentations automatically generated from my bibtext files, 'my pubs' and 'conferences' using Alex Singleton's code snippets from here
<https://github.com/alexsingleton/personal_site_source/blob/master/cv.Rmd>

- getting latex correctly configured was a nightmare. I have [basicTeX](https://www.tug.org/mactex/index.html) installed on my machine. All of the dependencies that I needed to install went into `\users\shawngraham\Library\texmf\tex\` ; I had to make the `texmf\tex\` directories. .sty files were obtained from https://www.ctan.org/pkg/. I never could get FontAwesome to install correctly, so I just nuked that part.

- In my bib files, I use keywords to sort the various entries into the official Carleton U categories. Carleton's categories don't imagine a world where the internet happened, which as you can imagine, is frustrating for me. Anyway. I export the selected entries into new .bib files for the purposes of generating the cv.

My intention is to add to the bib files throughout the year, and generate the updated cv & annual report once. I had been adding to a word doc higglypiggly but that didn't work worth a damn, and I was making mistakes.

blueletters is a **blog** of LETTER documents

## Fonts: Arial

sudo apt install ttf-mscorefonts-installer systemfonts::system_fonts()

## extension & template

1.  Install and Create

    -   *quarto use template fischerpj/quarto-letter* because it's a fork of mcanouil

    -   quarto use template mcanouil/quarto-letter

<!-- -->

1.  Add / Install just the \_extensions folder

    -   quarto add mcanouil/quarto-letter
    -   *quarto add fischerpj/quarto-letter* creates \_extensions folder

## log

-   REMOTELY i.e. on github, create this repo from scratch and empty without README as **https://github.com/fischerpj/blueletters.git**
-   LOCALLY create in RStudio the version of this project with **quarto create project blog blueletters**
-   PUSH with
    -   git remote add origin https://github.com/fischerpj/blueletters.git
    -   git branch -M main
    -   git push -u origin main
-   GENERATE the site with **quarto render**
-   2604: resume with letter schott2
-   2606 PUSHUP + remove xps

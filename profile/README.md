360info is an open access global information agency that tackles the world’s biggest challenges and offers practical solutions.

We publish **research-driven, solutions-focused, and ready-to-use content** and deliver it to republishers **without charge, under Creative Commons.** By partnering with hundreds of publishers looking to add in-depth context and more diverse voices to their news journalism, we better inform readers worldwide.

![image](https://user-images.githubusercontent.com/6520659/158499127-38260d62-cb39-4a70-80e7-6e2f1862d88d.png)

## ♻️ Use + Remix our Special Reports

Because our content is released under Creative Commons, you can use + remix it as much, or as little, as you like without charge. All we require is that you acknowledge us and the sources of our data. You can use the text in our reports by directly downloading them from [our website](https://360info.org), but we also allow you to alter reproduce and remix the graphics and multimedia we create.

To get started, **[browse our repositories](https://github.com/orgs/360-info/repositories)** and look for ones that begin with `report-` (such as [report-nuclear-weapons](https://github.com/360-info/report-nuclear-weapons)). We create these for our Special Reports, and they contain everything you need.

### 📊 Ready-to-use graphics

If you don't want to recreate our full analysis from scratch, we generally publish finished graphics in the `out` folder. This is perfect if you want to drop use our content straight into your story or to make minor adjustments for your own branding. Examples include:

* PNGs (for publishing on the web),
* SVGs (for use in Illustrator or other editing software)
* HTML (for interactives)

In cases where we produce videos or animations using Adobe Creative Cloud or other software, we keep project files on the [360 Google Drive](https://drive.google.com/drive/folders/1zNaEtm8jkKWF-IltlV12_36tk7ST_ihG?usp=sharing).

### 💻 Reproduce our analyses

If you'd like to re-run our analyses, we typically use [R](https://r-project.org) alongside the [Quarto](https://quarto.org) publishing system. Exact requirements are described in each repository. Look for files ending in `.qmd`, `.r` or `.rmd`.

### 🗂 Use our source data

Smaller data sources, such as CSV files, are often stored in the `data` folder. In some cases, we may store larger, manually processed files on the [360 Google Drive](https://drive.google.com/drive/folders/1zNaEtm8jkKWF-IltlV12_36tk7ST_ihG?usp=sharing). In other cases, our analysis scripts may download source data directly from another source, such as Our World in Data.

## 🔧 Tools

We also maintain a few tools used in our production process. Most prominent among these is [`themes360info`](https://github.com/360-info/themes360info), a package for aligning graphics in [`ggplot2`](https://ggplot2.tidyverse.org) with our house style.

## ❓ Issues

If you have problems recreating or using our data, code or graphics, you can file an issue (if you have a GitHub account) in a repository using the **Issues** tab. Otherwise, please email us at <info@360info.org>.

---
layout: about
title: the project
permalink: /
subtitle: A sonification of the tuning systems put forth in Boethius's <i>De institutione musica</i>

profile:
  align: right
  image: 
  image_circular: false # crops the image to make it circular
  more_info: >
    

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---
<style>

h3 {
  text-decoration: underline;
}

.boethiuscitation {
        padding-left: 1.5em;
        text-indent:-1.5em;
    }

</style>

<h3>Why does this website exist?</h3>

This website exists to allow visitors to compare the tuning systems of Boethius, Aristoxenus, and Archytas, as put forth by Boethius in <i>De institutione musica</i>.

The information Boethius provides about each tuning system does not readily lend itself to comparison; moreover, to see the difference numbers allows for one type of comparison, while listening to the difference allows for another. This site is meant to assist with the latter.

<h3>What <i>is</i> this website?</h3>
This website is a digital collection of audio files based on the tuning systems in<i>De institutione musica</i>. Boethius records his own system, as well as those of Aristoxenus and Archytas. Boethius also discusses Ptolemy's tuning system, but most of that discussion has been lost and cannot be recreated without turning to Ptolemy's own survivng work; as such Ptolemy's tuning system has not been included at this point in time.

Boethius was a 6th century CE scholar from Rome who wrote on a wide variety of subjects, including philosophy, mathematics, and music. The other two, Aristoxenus and Archytas, were both 4th century BCE Greek writers; Aristoxenus is known for favoring musical tunings that sounded most pleasing to the ear, while Archytas favored a system of tuning that relied more on mathematical ratios

<h3>How do you use the website?</h3>

There is no navigation order to the website, but there are three main ways to access the files. Under the [by author](/fundamentals-of-music/byauthor/) tab, the sound files are organized by author; if you want to compare Boethius's diatonic and chromatic scales, for example, that page would be a good place to start. Under the [by genus](/fundamentals-of-music/bygenus/) tab, the sound files are organized by genus. If you want to compare Boethius' diatonic to Archytas, that page would be a good place to start. Under the [alltunings](/fundamentals-of-music/alltunings) tab, the sound files are presented in a compact manner without additional information; if you already know the terminology and just want to access the files efficiently, that page would be the most useful.

Lastly, if the terminology is unfamiliar or confusing, there is a basic glossary and explanation page under [music basics](/fundamentals-of-music/musicbasics).

<h3>How were the audio files made?</h3>

All the files on this website were made using sine waves at frequencies calculated from the information in <i>De institutione musica</i> and compiled in the DAW Ableton. 

<h3>How was the information from <i>De institutione musica</i> used to determine the frequencies for the audio files?</h3>

How the information was used depended on the author. For Boethius and Archytas, the process was similar, as Boethius supplies proportions of string lengths as a means of conveying relative tuning. For example, Boethius gives the numbers 4608, 4374, 3888, and 3456 as relative string lengths for the synemmenon diatonic tetrachord. The lengths of the strings are inversely proportionate to the frequncies played. For example, 3456 is 3/4 of 4608, so the frequency of a note played on the string of 3456 parts in length would thus be a fourth up from the string 4608 parts in length (as 4/3 is the ratio correlating with the fourth). Using this information, I was able to calculate that if the 4608 string were to sound out at 432.0 Hz, then the next three strings of the synemmenon tetrachord would sound at (rounding to the nearest 0.1 Hz) 455.1, 512.0, and 576.0 (aka 4/3 of 432.0) respectively. Using the same logic, I was able to determine what frequency each note in Boethius's full scale would align with. 

Archytas was a similar situation, though Boethius provides a single tetrachord for each of his tuning systems rather than a full scale for the diatonic, chromatic, and enharmonic each. Nevertheless, the logic is the same. For Archytas' diatonic, the numbers 2016, 1944, 1701, and 1512 are reported. If a string of 2016 parts in length sounded at 432.0 Hz, then the rest of the tetrachord would sound at 448.0, 512.0, and 576.0. Moreover, since the construction of a full scale is based on a consistent structure of tetrachords and whole tones (see [music basics](/fundamentals-of-music/musicbasics/)), the 2016, 1944, 1701, and 1512 numbers can be used to generate the entire scale, as these numbers represent ratios of lengths rather than set lengths of a real unit. 

Aristoxenus' section was the most difficult to convert from the information given to the frequencies, as Boethius reports his work not in lengths but in the size of intervals. Boethius reports that according to Aristoxenus there are 60 equally sized parts within a tetrachord--that is, 60 equally sized intervals. To add intervals together involves multiplying their respective ratios--a fourth (4/3) and a fifth (3/2) can be added ((4 x 3)/(3 x 2)) to get an octave (2/1). 

An interval equivalent to a 60th part of 4/3s, then is the sixtieth root of 4/3rds. Needless to say, this is not a nice number, and the existence of calculators was invaluable here. 

Boethius then reports Aristoxenus's tunings in terms of these intervals. Between the lowest and second lowest notes of Aristoxenus' sharp diatonic tetrachord lies 12 of these equally sized, 60th root of 4/3 intervals. Between the second lowest and second highest lie 24, and between the second highest and the highest lie 24 as well. The frequency of the second note then is equal to the first note multiplied by twelve times the sixtieth root of four thirds, and so on and so forth. 

So, assuming that the lowest note is tuned to 432.0 Hz, the rest of the notes lie at 457.6, 512.4, and 576.0 Hz. 

I chose to round to the nearest 0.1 Hz because I consider it a good compromise between accuracy and quality assurance. While the sine wave generator I used accepted inputs of up to the thousandths place, I was unable to determine whether the sine wave generated actually reflected the number inputted or was rounding, whereas I was able to determine by ear the difference between two sine waves tuned a tenth apart. That said, two sine waves a tenth of a Hz apart are nearly indistinguishable, and as such, I consider accuracy to the 10th place to be reasonably true to Boethius's original intentions. 

<h3>What do these terms mean?</h3>

For a quick run down on some of the music theory terms, see [music basics](/fundamentals-of-music/musicbasics).

<h3>What is the scholarly basis for this website?</h3>

The vast majority of the information for this website comes from Boethius's <i>De institutione musica</i>. Specifically, I consulted Calvin Bower's 1989 translation: 

<div class = "boethiuscitation">
<p>Boethius. <i>Ancius Manlius Severinus Boethius: Fundamentals of Music.</i> Edited by Claude V. Palisca. Translated by Calvin M. Bower. New Haven: Yale University Press, 1989. 
</p>
</div>



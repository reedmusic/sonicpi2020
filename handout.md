# Sonic Pi Workshop
*Faculty of Education, 19 June 2019*
<br>*E Reed. ereed - at - swchs.net*

Notes available (clickable links) online at [mrreedswchs.github.io](http://mrreedswchs.github.io)

## Advantages over other software

**Bold** = serious advantage over other music tech software

* Maths
	* **Randomisation**
	* **Choice**
	* **Mathematical processes**
	* **Microtones**
	* **Polyrhythm**
	* **Phasing and polytempo**
* Music tech
	* Synthesis
		* Envelope control (ADSR)
		* Amp, pan, and other controls via in-line options or `use_synth_defaults`/`use_sample_defaults`
	* Samples
		* Built-in samples
		* **External samples just by quoting path**
		* **Quickly change rate and pitch**
		* **Reverse!**
	* **Oscilloscope!**
	* **Live control** through `live_loop`
	* **OSC** and MIDI I/O
	* **Live audio in** through `synth :sound_in` and `live_audio`[^1]
* Computer science
	* Loops + **iteration**
	* Chain methods
	* Defining and recalling variables
	* **Text-based, easy to share**
	* **The audible made visible (and not Western notation)**
* Other features
	* **Free**
	* **Record audio straight from the programme and control in real time**
	* **Built-in tutorial and code examples**

## Disadvantages

* Maths
	* Easy to make addition mistakes so that loops don't synchronise
* Text-based [concurrency](https://www.youtube.com/watch?v=7sEMKXrRaAs#t=7m05s); slight difficulty of `live_loop` and the friction between concurrent live_loops and linear compositions. This can be bridged with `in_thread`, but which do you privilege in a short SoW?
* Music tech
	* Text based so difficult to visualise, e.g. pitch of notes, envelope shape...
	* Clunky MIDI and Audio I/O. Compare this to Logic, for example.
* Computer science
	* Sterility? Relative difficulty of introducing `amp:` options or other expression
* Students might be better than you!

## Points of interest

* Low barrier to entry but difficult to master
* Errors highlighted immediately
* Tangible outcomes or high degree of abstraction
* Possible STEM funding

## Resources for learners

### mehackit
* <https://sonic-pi.mehackit.org/exercises/en/01-introduction/01-introduction.html>
<br>Excellent and comprehensive course from beginner to expert. Lots of links to music theory and accompanying graphics/explanations. Highly recommended for use in lessons.

### Raspberry Pi Foundation

* <https://projects.raspberrypi.org/en/projects/getting-started-with-sonic-pi>
<br>More basic but still very useful course.

* <https://github.com/raspberrypilearning/sonic-pi-lessons>
<br>(Archived) Scheme of work developed by Pi foundation for the Live & Coding research project.

* <https://www.raspberrypi.org/magpi-issues/Essentials_Sonic_Pi-v1.pdf>
<br>Magpi magazine. A bit old now but a great PDF resource. Good ideas for making printed resources of your own.

### Sam Aaron

* <https://sonic-pi.net/tutorial.html>
<br>The easiest resource, since it's baked into the app itself (just click the *Help* button in Sonic Pi). A great online resource too, presented in an ebook style.

* <https://in-thread.sonic-pi.net/t/sonic-pi-online-resources/17>
<br>Forum thread containing loads of resources

### Youtube

* [https://www.youtube.com/user/daveconservatoire/playlists](https://www.youtube.com/watch?v=4BPKaHV7Q5U&list=PLaitaNxyd8SHvTQjRGnMdKLsARXW7iYyp)
<br>Dave Conservatoire. 30 videos! Great stuff. While you're at it, check out his [MuseScore series](https://www.youtube.com/watch?v=vVXjsQR8zqo&list=PLaitaNxyd8SE_D6PtNvA5vXn8VpXsbA7Z)

### Codecademy: Ruby

* <https://www.codecademy.com/learn/learn-ruby>
<br>Since Sonic Pi uses Ruby, this would be a useful course for teachers or to direct students who wanted to master the computer science elements.

### Blogs and isolated posts

* <https://rbnrpi.wordpress.com/>
* <https://manwaringmusic.blog/2018/04/24/sonic-pi-diaries-pt-2/>
* <https://www.bbc.co.uk/programmes/p031dq3j> - Sonic Pi and BBC Ten Pieces

## Research and further reading

* Collins (2016): Live coding and teaching SuperCollider: <http://dro.dur.ac.uk/17855/1/17855.pdf>
* <https://algorave.com/>
* <https://toplap.org/>


## Sonic Pi in use

* A playlist of my explorations and my students' work: <https://www.youtube.com/playlist?list=PLUzqDorR42SQpTcLEXTBuj-D0rAYYI52A>
* Sonic Pi in use in the Albert Hall: <https://vimeo.com/328673793#t=59m10s>

## Other stuff

* <https://github.com/tmcw/big> - Simple JS presentations
* <http://jmcglone.com/guides/github-pages/> - Simple web storage
* <http://www.gitbook.com> - WYSIWYG ebook/tutorial creation. Absolutely brilliant. Great github integration if you fancy.
* <https://www.patreon.com/samaaron> - Sonic Pi needs support to continue development


[^1]: Don't forget to stop! `live_audio :foo, :stop`

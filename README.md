![image (2)](https://user-images.githubusercontent.com/87339163/208270834-bb67ffd4-d2cb-4296-957b-9a4837ee9a84.png)
A Meticulously designed workhorse theme for [Obsidian](https://obsidian.md/).

Origami features extensive changes to the base UI, to create a clean and unobtrusive interface that you can work for hours in. Inspiration was taken from centuries of human typography and the timelessness of ink and folded paper ✒️

Origami was crafted with 💖 to mimic the soft tactility of a sheet of paper, and merge it with the word processing of digital tools ⌨️ and is my personal daily driver 🦾

>🥳 Winner of Obsidian October (O_O) Best New Theme 2022 🥰

# Color &
## Typography

![image (3)](https://user-images.githubusercontent.com/87339163/208278011-23580464-19c3-450b-b5ed-a8775eca75fb.png)

The color design of Origami is the result of over one hundred hours of research during Obsidian October (O_O), and a background in design. Inspiration was taken from studies on legibility and contrast,[^1] in an attempt to bridge tried and true pen & paper 📝with advances in digital design.

The high contrast light[^2] and dark mode[^3] follows proven[^4] standards[^5] in contrast.

Notably, optimal contrast is black text on a light background. This has been shown to reduce strain in resolving characters, and improve reading comprehension. The rule of thumb is that your screen color should match the lightness of the background it is against; in a simple example, you should have a light screen against a light wall and a dark screen against a dark wall to reduce eye strain.

🌞
> In light mode, we already know that color white reflects all the wavelengths of the visible light spectrum, this makes the pupil not need to dilate to let in more light. This makes it easier for the human eye to read more comfortably if the text is black on a white background, and it also favors better understanding and retention of what is read. The constricted pupil has to work less to focus the text.
> <cite> [Ailon Webs](https://www.ailonwebs.com/en/blog/web-page-design/dark-mode-and-light-mode/index.php) </cite>

🌚
> In contrast, dark mode causes the pupil to dilate to let in more light. This is why, many people find dark mode more comfortable when there is little light in the environment, but it is not always recommended to use it. By nature the human eye can see very well during the day and not so well at night, the best contrast for the eye is dark text on a light background.
> <cite> [Ailon Webs](https://www.ailonwebs.com/en/blog/web-page-design/dark-mode-and-light-mode/index.php) </cite>

### Typography
The font choices I finally landed with for Origami were the result of hours of research on legibility[^6] and my own testing. Personally, I find long paragraphs of text hard to read with most web design, This is often because line height and font size[^7] pairing is _hard_. I have always struggled with it, and due to dyslexia, some paragraphs are downright impossible to read. Bad line height[^8] can be called waterfalling, and often causes my eyes to ‘unfocus’ while reading.[^9] I used a few tools[^10] and careful tweaking to zero in on settings I could read comfortably for hours in both dark & light mode.

![image (7)](https://user-images.githubusercontent.com/87339163/208278030-58e68327-5f0d-411e-9b90-92a6e0256441.png)

A few of my favorite resources on good type design are Libre Fonts by Womxn, Uncut,[^11] Beautiful Web Type[^12] and a few type scale calculators[^13].[^14][^15]

Headings are based off of experiments with my personal site, and are tailored for my workflow Header one and two are meant to be used as a central landmark, with eye catching demarking.

![image (8)](https://user-images.githubusercontent.com/87339163/208278034-e5094cd6-841f-468f-bfa8-b22154b046fb.png)

Most of the time, you shouldn’t extend past heading 4 (warning: opinion). That being said, I style 4 & 5 as 1:1 with body text; the difference being weight and type softness to signify areas of interest. Finally, heading 6 is slightly smaller, for sub tagging small notes.

Finally, the fonts I chose are as follows:

**For UI**:
- Currently I have swapped to Uncut Sans, for more neutral glyphs at small text size. Variable fonts also allow me to style weight and slant without tons of font imports.

**For Text**:
- [Fraunces](https://github.com/undercasetype/Fraunces) and Uncut sans have both been used here, for body text and links respectivly. In the future, I am going to add a toggle for a "serif dominant" and "sans-serif" dominant switch.

**For monospace**:
- Evil Martin

I may spend way too much time researching typefaces. The end result is a few that I absolutely adore. These are typefaces that have withstood-stood my daily usage. And I say that having tried nearly every font on Google, Adobe, and Envato.

Unfortunately, some of my favorite typefaces couldn’t make it into the theme. This is simply because my brain is very small, and licencing is both expensive and confusing. One such type was Tiempos Text, my absolute favorite.

Exclusion breeds innovation or something, I don’t know, and the open-source community is incredible. Hours of research into serif fonts, especially variable ones, eventually led me to a typeface called Fraunces.

Fraunces is a ‘wonky font’ and I love it.

It checks every box I need. Amazing backstory, lovely characters, and tons of control via CSS axis. One thing that drew me to the typeface was its ‘wonk’ & ‘soft’ axi. These control axi would let me change the one embedded typeface well enough to serve all of my text needs.

Embedding, or importing, typefaces was something I wanted to be careful with. I wanted this to be a workhorse theme that anyone could use on any device. Large fonts could bloat our file size –especially if I needed to embed a font.

Unfortunately, the Google hosted version of Fraunces didn’t expose the axi I needed for my CSS. So I needed to find a way to embed a variable font, and the normal font-face converter I typically used wouldn’t work.

I eventually tracked down a [stack overflow](https://stackoverflow.com/questions/26867893/converting-and-rendering-web-fonts-to-base64-keep-original-look) (of course 💖) with an absolute legend who provided a wonderful embed to base64 encode variable fonts.

Finally, I was left with variables I could play around with to give different markdown demarking unique styling. Special consideration was spent looking over lists, settings, links, and many other typographical stylings.

Personally, I use Obsidian to bullet journal with daily notes. Since I have issues with visually identifying blocks of content, and often work with lists, I styled top level list items with a border to help section off areas of content

### Extras
- Custom folder collapse styling, originally by `@anbis` and adapted by myself.
- Colorful headings with Style Settings.
- Handpicked accent colors, also with Style Settings.
- Canvas support, including UI and color options.
- Special buttons!
- Settings, prompts, tooltips, tags, links, and much more have been themed to create a unified experience.
- `<cite> </cite>` support, courtesy of [Palatinate](https://github.com/eleanorkonik/-palatinate)

![bttnz](https://user-images.githubusercontent.com/87339163/207750815-c75e445f-7f0b-48aa-ae56-43f08db67927.gif)

### Plugin Support

![image (6)](https://user-images.githubusercontent.com/87339163/208278025-f1d60a11-9c83-4bcf-b0d1-4aaaaa9ca97a.png)
_Omnisearch_

![image (5)](https://user-images.githubusercontent.com/87339163/208278021-a3489617-0511-4de5-bb3f-ed0dda125bf4.png)
_Better Command Palette + My Canvas board for making this readme!_

![image (4)](https://user-images.githubusercontent.com/87339163/208278018-a631ed47-2754-46af-9574-3310717028e6.png)
_The brand new Canvas feature_

- [Style Settings](https://github.com/mgmeyers/obsidian-style-settings)
- [Make.md](https://www.make.md/) (including 90% visual parity with theme file explorer, including file icons)
- [Kanban](http://matthewmeye.rs/obsidian-kanban/)
- [Omnisearch](https://github.com/scambier/obsidian-omnisearch)
- [Better Command Palette](https://github.com/AlexBieg/obsidian-better-command-palette)
- [Influx](https://github.com/jensmtg/influx)
- [Strange New Worlds](https://github.com/TfTHacker/obsidian42-strange-new-worlds)
- [Reminder](https://github.com/uphy/obsidian-reminder)
- [Memo](https://github.com/Quorafind/Obsidian-Memos)
- [Surfing](https://github.com/Quorafind/Obsidian-Surfing)

## Todo
- [ ] Polish aspects of the theme
- [ ] Refactor to clean up and move more clunk to new variables
- [ ] Style Settings
- [ ] New color schemes
- [ ] Monochrome mode
- [ ] Fix font hardcoding for other languages
- [ ] Sans serifed font
- [ ] Maybe monospace body font?
- [ ] Make better graphics to finish showing off the theme

# Credits 🥰
- ✨ **Carboxyl & Pseudometa**, for the lovely name 💖
- 🐕**Anubis** for their rainbow folders
- 🖥️ **Lukemt** for their smooth live headers
- 💎 Obsidian, for the amazing program to theme
- ⌨️ The amazing **plugin** developers, for their time
- 🎨 The gifted **theme** community, for their inspiration
- 👯 Countless members of the community, for helping me test things
- 😈 Myself, for writing all of this
- 🎡 John Wheeler, for having a really cool name
- 💖 You, for reading this & trying my theme

**Other, about**
For Obsidian October, I challenged myself to build a theme for how I used Obsidian. I wanted to finally learn how to (somewhat) write CSS. I never believed I would have ended up winning O_O, and I am beyond grateful for the consideration! It was an amazing experience learning, and I cannot wait to keep working on the theme :)

[^1]: [Contrast Standard Resources](https://webaim.org/resources/contrastchecker/)
[^2]: [Are humans more adapted to "light mode" or "dark mode"?](https://biology.stackexchange.com/questions/97635/are-humans-more-adapted-to-light-mode-or-dark-mode)
[^3]: [Applying Color Theory to Digital Displays](https://www.uxmatters.com/mt/archives/2007/01/applying-color-theory-to-digital-displays.php#:~:text=Black%20text%20on%20a%20white,optimal%20readability%20for%20body%20text.)
[^4]: [Contrast Sensitivity](https://www.sciencedirect.com/science/article/pii/B9780123742032002359)
[^5]: [Dark Mode vs. Light Mode: Which Is Better?](https://www.nngroup.com/articles/dark-mode/)
[^6]: [Typeface features and legibility research](https://www.sciencedirect.com/science/article/pii/S0042698919301087)
[^7]: [Font size guidelines for responsive websites](https://www.editorx.com/shaping-design/article/font-size)
[^8]: [The ideal line length & line height in web design](https://pimpmytype.com/line-length-line-height/)
[^9]: [Is there an optimal font size / line height ratio?](https://ux.stackexchange.com/questions/35270/is-there-an-optimal-font-size-line-height-ratio)
[^10]: [The good line-height](https://www.thegoodlineheight.com/)
[^11]: [Typewolf](https://www.typewolf.com/)
[^12]: [Guide to Only the Best Open-Source Typefaces](https://beautifulwebtype.com/)
[^13]: [What’s the right font size in web design?](https://pimpmytype.com/font-size/)
[^14]: [Type Scale Calculator](https://type-scale.spencermortensen.com/4/2.5/0/1.125em/Libre%20Franklin%20900/Readex%20Pro%20300)
[^15]: [The Typographic Scale](https://spencermortensen.com/articles/typographic-scale/)

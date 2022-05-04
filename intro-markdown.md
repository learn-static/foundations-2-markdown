# Introduction to Markdown
This brief module provides instructions that give newcomers experience using Markdown, a human-readable markup language for adding formatting to plain text files.

## What is Markdown?
Markdown was developed as a simple way to write content for the web without using HTML (hyptertext markup language), a language commonly used to write content for websites.
It allows for a straight-forward way to structure text, links, images, code, tables, and lists within a plain text document without using tags like those used in HTML.

Using Markdown, we can format text in structured ways using...

- Headings
- Paragraphs and Line Breaks
- Emphasis, e.g. bold and italics
- Lists, e.g. numbered lists and unordered lists
- Images
- Hyperlinks
- Blockquotes

For this learning exercise, we will learn how to use headings, paragraphs, line breaks, emphasis, lists, images, and hyperlinks. 
To learn how to use other parts of the Markdown syntax visit [Markdown Guide](https://www.markdownguide.org/cheat-sheet/).

**Why use Markdown?**
- It can be fast to use while writing webpage content
- It is used all over the place. It's a standard used by GitHub and other tools people use reguarly to communicate over the Internet.
- It converts easily to HTML
- It is future-friendly. This means Markdown within a plain text file that has the file extension `.md` can be opened and used by any current day or future computer program. There is no reason to worry about outdated versions of your plain text files.

## Step 1. Create a Markdown File Within a GitHub repository

1. Create a new GitHub repository or use the one that you've already made while working through [foundations-0-github](https://github.com/learn-static/foundations-0-github).
2. On your repository's home page, locate and click the "Add file" button, situated to the right above your repository's files. When this button is clicked, a drop-down menu will appear. Select the option "Create new file".
3. An option to name your file will appear toward the top of your screen. Give your file the name `index.md`. 
4. Add a commit message to the "Commit changes" box at the bottom of the page, then click the green "Commit changes" button to save your new Markdown file.
5. Click your repository's name (located in the top left of the window) to return to the repository's home page, where you should now see `index.md` listed in the repository's files.

---

## Step 2. Headings

### Headings

Headings are used to title sections in your document, and are indicated with one or more pound signs (`#`) in front of them:

```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

When writing for the web, Markdown headings will translate into HTML headings.

One `#` indicates the largest heading: Heading 1:

# Heading 1

Two `##` indicates Heading 2, which is slightly smaller than Heading 1:

## Heading 2

Three `###` indicates Heading 3, and so on.

Make sure to organize your headings in hierarchical order (i.e. always nest Heading 2 underneath Heading 1, etc.) to ensure your webpage is readable and accessible.
(To learn more about headings and web accessibility visit [A11y styleguide - Structure](https://a11y-style-guide.com/style-guide/section-structure.html)).

#### Practice Using Headings

1. From the base of your repository, click on the `index.md` link to open the file.
2. In the top right corner of the `index.md` file, locate and click on the pencil icon.
3. You are now in GitHub's editing mode and can begin writing.
4. In the first line of your `index.md` file, add a Heading 1 that reads, `# Yōkai Senjafuda: Stories about Ghosts and Monsters`
5. On line 3, add a Heading 2 that reads, `## Section 1`
6. On line 4, add a Heading 3 that reads, `## Section 2`
7. To see how your headings will look once you commit your file, you can "preview" the file: Near the top of the file you're editing, locate and click on the "Preview" tab (to the right of the "Edit File" tab). Preview mode will allow you to see how your headings will render on a webpage. When you're satisfied with the preview and ready to get back to editing, click on the "Edit File" tab.

---

## Step 3. Paragraphs and Line Breaks

Paragraphs in Markdown can be written exactly as you write them in Microsoft Word, but *without a tabbed first sentence* and *with a blank line in between paragraphs*.
In other words, you can string together sentences one after another as you are used to doing when you write papers or emails, and they will appear in a paragraph on the front end of the webpage.

*However*, be aware that **if you don't put an empty line *between* your paragraphs when you write them, they will all join into one *massive* paragraph on your webpage**.

For example, these two paragraphs have a blank line in between them, and will translate accordingly from the back end to the front end:

**`index.md` view**:

`This digital exhibition focuses on tiny slips of paper—senjafuda 千社札—that depict Japanese ghosts and monsters—yōkai 妖怪. Both senjafuda and yōkai have their roots in Japanese popular culture in the early modern period (17th-19th centuries), and both continue to cast a spell on viewers today.`

`The phenomenon of senjafuda dates back to the late 18th century. They were originally made by pilgrims to paste on the walls of temples and shrines as a sort of devotional graffiti.`

**"Front end" view**: 

This digital exhibition focuses on tiny slips of paper—senjafuda 千社札—that depict Japanese ghosts and monsters—yōkai 妖怪. Both senjafuda and yōkai have their roots in Japanese popular culture in the early modern period (17th-19th centuries), and both continue to cast a spell on viewers today.

The phenomenon of senjafuda dates back to the late 18th century. They were originally made by pilgrims to paste on the walls of temples and shrines as a sort of devotional graffiti. 

**But the following two paragraphs will merge into one paragraph when rendered on the front end, even though they are written on separate lines on the back end:**

**`index.md` view**:

```
This digital exhibition focuses on tiny slips of paper—senjafuda 千社札—that depict Japanese ghosts and monsters—yōkai 妖怪. Both senjafuda and yōkai have their roots in Japanese popular culture in the early modern period (17th-19th centuries), and both continue to cast a spell on viewers today.
The phenomenon of senjafuda dates back to the late 18th century. They were originally made by pilgrims to paste on the walls of temples and shrines as a sort of devotional graffiti.
```

**"Front end" view**:

This digital exhibition focuses on tiny slips of paper—senjafuda 千社札—that depict Japanese ghosts and monsters—yōkai 妖怪. Both senjafuda and yōkai have their roots in Japanese popular culture in the early modern period (17th-19th centuries), and both continue to cast a spell on viewers today.
The phenomenon of senjafuda dates back to the late 18th century. They were originally made by pilgrims to paste on the walls of temples and shrines as a sort of devotional graffiti.

**So, make sure to leave empty lines between your paragraphs, and between headings and paragraphs.**

#### Practice Using Paragraphs

1. Copy the following paragraphs and line breaks and paste them underneath the heading `## Section 1` in your `index.md` file. Make sure to leave a blank line between the Section 1 heading and the following text:

```
This digital exhibition focuses on tiny slips of paper—senjafuda 千社札—that depict Japanese ghosts and monsters—yōkai 妖怪. Both senjafuda and yōkai have their roots in Japanese popular culture in the early modern period (17th-19th centuries), and both continue to cast a spell on viewers today.

The phenomenon of senjafuda dates back to the late 18th century. They were originally made by pilgrims to paste on the walls of temples and shrines as a sort of devotional graffiti. Later they became collector’s items, and by the middle of the 19th century they had become miniature masterpieces of woodblock printed art. Senjafuda depict a dizzying variety of themes with meticulous craftsmanship and vivid, stylish graphic design.

Yōkai simply means “monster,” but it’s best understood as referring specifically to monsters (and sometimes ghosts) as imagined in early modern Japan, particularly as depicted in wood-block prints. From Mizuki Shigeru to Studio Ghibli, from The Ring to Yōkai Watch, Japanese popular culture (including anime, manga, books, and film) is full of yōkai imagery.

The University of Oregon’s collection of senjafuda is one of the largest in the world. It includes many senjafuda depicting yōkai. This exhibit uses senjafuda to explore yōkai culture, and yōkai to explore senjafuda culture.
```

2. To see how your paragraphs will look once you commit your file, you can "preview" the file: Near the top of the file you're editing, locate and click on the "Preview" tab (to the right of the "Edit File" tab). Preview mode will allow you to see how your paragraphs will render on a webpage. When you're satisfied with the preview and ready to get back to editing, click on the "Edit File" tab.

---

## Step 4. Emphasis

Emphasis can be added to text by applying italics or bold styles. 
Markdown uses the asterisk (`*`) character to add styling controls.

To make a word or phrase *italic*, add one asterisk before and after that word or phrase, like this: `*example phrase*`.
The asterisks won't be visible on your webpage, but your text will appear italicized.

To make a word or phrase **bold**, add two asterisks before and after that word or phrase, like this: `**example phrase**`.
Again, the asterisks won't be visible on your webpage, but your text will appear bold.

To make a word or phrase ***italic and bold***, add three asterisks before and after that word or phrase, like this: `***example phrase***`.
Again, the asterisks won't be visible on your webpage, but your text will appear both italic and bold.

#### Practice Using Emphasis

1. Copy the following text and line breaks and paste it underneath the heading `## Section 2` in your `index.md` file. Make sure to leave a blank line between the Section 2 heading and the following text:

```
*senjafuda 千社札*

**yōkai 妖怪**

***The University of Oregon’s collection of senjafuda is one of the largest in the world. It includes many senjafuda depicting yōkai. This exhibit uses senjafuda to explore yōkai culture, and yōkai to explore senjafuda culture.***
```

2. To see how your emphasized text will look once you commit your file, you can "preview" the file: Near the top of the file you're editing, locate and click on the "Preview" tab (to the right of the "Edit File" tab). Preview mode will allow you to see how your emphasized text will render on a webpage. When you're satisfied with the preview and ready to get back to editing, click on the "Edit File" tab.

---

## Step 5. Lists

You can create lists in two different ways:

A bullet list is created using a hyphen (`-`) in front of each bullet point:

- dog
- cat
- muffin

A numbered list is created using a number followed by a period (`.`) in front of each list item:

1. one
2. two
6. three
2. four

#### Practice Using Lists

1. Copy the following list and paste it underneath the heading `## Section 1` in your `index.md` file. Make sure to leave a blank line between the Section 1 heading and the following text:

```
Digital collections used in the "Yōkai Senjafuda: Stories about Ghosts and Monsters" digital exhibit:

1. The Star Collection
2. The Shōbundō collection
```

2. Copy the following list and paste it underneath the heading `## Section 2` in your `index.md` file. Make sure to leave a blank line between the Section 2 heading and the following text:

```
Categories of ghosts and monsters found in the "Yōkai Senjafuda: Stories about Ghosts and Monsters" digital exhibit:

- Kappas
- Oni
- Cats
- Foxes
- Tengu
```

3. To see how your lists will look once you commit your file, you can "preview" the file: Near the top of the file you're editing, locate and click on the "Preview" tab (to the right of the "Edit File" tab). Preview mode will allow you to see how your lists will render on a webpage. When you're satisfied with the preview and ready to get back to editing, click on the "Edit File" tab.

---

## Step 6. Hyperlinks

To link to another page or site, insert the link title (what you want displayed to the site visitors) into square brackets (`[]`), followed by a URL in parentheses (`()`).

`[GitHub Help](https://help.github.com/)` in your `index.md` file will look like [GitHub Help](https://help.github.com/) on your webpage.

### Practice Using Hyperlinks

1. Copy the following hyperlink and paste it underneath the heading `## Section 1` in your `index.md` file. Make sure to leave a blank line between the Section 1 heading and the following text:

```
[Yōkai Senjafuda Digital Exhibit](https://glam.uoregon.edu/yokaisenjafuda/page/welcome)
```

3. To see how your hyperlink will look once you commit your file, you can "preview" the file: Near the top of the file you're editing, locate and click on the "Preview" tab (to the right of the "Edit File" tab). Preview mode will allow you to see how your hyperlink will render on a webpage. When you're satisfied with the preview and ready to get back to editing, click on the "Edit File" tab.

---

## Step 7. Images

Add an image to your webpage using the following combination:

`!
Images can be added with Markdown by adding `!`, `[ ]`, `( )`, and `" "` to create a string using an alterntative text description, an image file directory path on your web server or website address, and optionally adding a title after the URL in the paraenthesis. Something to note, 

Note that it is best practice to always add an alternative text description.
This ensures that screen readers can convey the contents of images to users with visual impairments.

- `!` tells Markdown that you want to add an image
- `[ ]` tells Markdown that you want to add an alternative text description
- `( )` tells Markdown what is the file directory path or website address your image file is located
- `" "` tells Markdown to optionally add a title

Here is an example of what the Markdown code looks when you add an image.

```
![Two-unit votive slip with double black border. Kabuki scene with young female dancing. Flames on kimono and falling around her. Decorative fan shapes at top with ren mark patterns and black text.](https://oregondigital.org/downloads/oregondigital:df728t07k "Two-unit votive slip with double black border. Kabuki scene with young female dancing. Flames on kimono and falling around her. Decorative fan shapes at top with ren mark patterns and black text.")
```

### Let's apply this to GitHub ###
1. Within the Edit file tab of `index.md`, add an image below the header "Senjafuda collections at the University of Oregon" using the information below.

**Image alternative text description:** Two-unit votive slip with double black border. Stone buddha sculpture with supernatural surroundings. Multiple white slips with black text at top.

**Image URL:** https://oregondigital.org/media/medium-images/c/5/oregondigital-df72bk65c.jpg

**Optional Image Title:** Two-unit votive slip with double black border. Stone buddha scultpure with supernatural surroundings. Multiple white slips with black text at top.

Here is an example of what your image code should look like.
![Figure showing where to add the Markdown image code to the Edit file tab.](/assets/images/markdown-015.png)

2. Click Preview to see how it renders. It should look like the figure below.

![Figure showing an image rendered within the Edit file tab.](/assets/images/markdown-016.png)

## How to Add Blockquotes
### About Blockquotes
Blockquotes allows you to offset text from the main text to be distinguishable and identified visually. They are typically used for long quotes. To make blockquotes we use the `>` symbol. In order to make a blockquote, you have to add `>` at the beginning of your quote.

There are three approaches to using blockquotes
**1. Using a single blockquote**
To add a single blockquote, add `>` at the beginning of the paragraph.

Here is how it looks in Markdown.
```
>Frederick Starr (1858-1933) was an American anthropologist at the University of Chicago who visited Japan frequently between 1904 and 1933. His primary interest during his stays in Japan was the social networks of collectors who were focused on objects associated with the early modern era, particularly collectors of traditional toys and senjafuda. Starr, his traveling companion Manuel Gonzales, and his interpreter Maebashi Hanzan were prominent fixtures at numerous senjafuda exchange meetings in the early 20th century, and Starr became so associated with the senjafuda scene that the press gave him the nickname “Professor Votive Slip” (Ofuda hakushi). Starr also wrote a short book about the history of senjafuda that was published in English in 1917 as The Nosatsu Kai and in Japanese (in a translation and adaptation by Fujisato Kōko) as Nōsatsu shi in 1921.
```

Here is how it looks when Markdown renders.
>Frederick Starr (1858-1933) was an American anthropologist at the University of Chicago who visited Japan frequently between 1904 and 1933. His primary interest during his stays in Japan was the social networks of collectors who were focused on objects associated with the early modern era, particularly collectors of traditional toys and senjafuda. Starr, his traveling companion Manuel Gonzales, and his interpreter Maebashi Hanzan were prominent fixtures at numerous senjafuda exchange meetings in the early 20th century, and Starr became so associated with the senjafuda scene that the press gave him the nickname “Professor Votive Slip” (Ofuda hakushi). Starr also wrote a short book about the history of senjafuda that was published in English in 1917 as The Nosatsu Kai and in Japanese (in a translation and adaptation by Fujisato Kōko) as Nōsatsu shi in 1921.

**2. Using blockquotes for multiple paragraphs**
Similar to adding a `>` at the beginning of each paragraph, when blockquoting multiple paragraphs you need to add `>` at the start of each paragraph and then the line between them.

Here is how it looks in Markdown.
```
>Starr amassed a huge collection of senjafuda both through his frequent attendance at exchange meetings and by procuring scrapbooks put together by other collectors. As a result of his persistence in acquiring senjafuda his collection not only thoroughly documents the years he was active in senjafuda (the 1910s to early 1930s), but also contains examples going back to the mid-19th century. After his death, his senjafuda collection was acquired by Gertrude Bass Warner (1863-1951), a traveler and collector of Japanese, Chinese, and Korean art and founder of the University of Oregon Art Museum (now the Jordan Schnitzer Museum of Art). The senjafuda mounted in scrapbooks (more than 50 of them) are now housed in Special Collections and University Archives (University of Oregon Libraries), while the loose slips are housed in the Jordan Schnitzer Museum of Art.
>
> Henry Smith has examined Starr's scholarly interest in Japan in detail, noting Starr's consistent attention to the religious dimension of culture—clearly visible in senjafuda, as this exhibition shows. Smith also notes that Starr's interest in “the social matrices in which these objects came to be collected, depicted, and exchanged in…distinctive subcultures of modern Japan” gives his work value in a contemporary context as well. But Starr had an eye for phenomena that appealed to a playful as well as a scholarly bent. When asked by a reporter for a Japanese newspaper what his interests were, he reeled off a list that began with kappa and tengu. It's no wonder, then, that yōkai are well represented in his senjafuda collection.
```

Here is how it looks when Markdown renders.
>Starr amassed a huge collection of senjafuda both through his frequent attendance at exchange meetings and by procuring scrapbooks put together by other collectors. As a result of his persistence in acquiring senjafuda his collection not only thoroughly documents the years he was active in senjafuda (the 1910s to early 1930s), but also contains examples going back to the mid-19th century. After his death, his senjafuda collection was acquired by Gertrude Bass Warner (1863-1951), a traveler and collector of Japanese, Chinese, and Korean art and founder of the University of Oregon Art Museum (now the Jordan Schnitzer Museum of Art). The senjafuda mounted in scrapbooks (more than 50 of them) are now housed in Special Collections and University Archives (University of Oregon Libraries), while the loose slips are housed in the Jordan Schnitzer Museum of Art.
>
> Henry Smith has examined Starr's scholarly interest in Japan in detail, noting Starr's consistent attention to the religious dimension of culture—clearly visible in senjafuda, as this exhibition shows. Smith also notes that Starr's interest in “the social matrices in which these objects came to be collected, depicted, and exchanged in…distinctive subcultures of modern Japan” gives his work value in a contemporary context as well. But Starr had an eye for phenomena that appealed to a playful as well as a scholarly bent. When asked by a reporter for a Japanese newspaper what his interests were, he reeled off a list that began with kappa and tengu. It's no wonder, then, that yōkai are well represented in his senjafuda collection.

**3. Using blockquotes that are nested within other blockquotes**
What is different about nested blockquotes compared to blockquoting multiple paragraphs is the addition of an extra greater than character. When nesting a quote within a quote use `>>`.

### Let's apply this to GitHub

Here is how it looks in Markdown.
```
>Starr amassed a huge collection of senjafuda both through his frequent attendance at exchange meetings and by procuring scrapbooks put together by other collectors. As a result of his persistence in acquiring senjafuda his collection not only thoroughly documents the years he was active in senjafuda (the 1910s to early 1930s), but also contains examples going back to the mid-19th century. After his death, his senjafuda collection was acquired by Gertrude Bass Warner (1863-1951), a traveler and collector of Japanese, Chinese, and Korean art and founder of the University of Oregon Art Museum (now the Jordan Schnitzer Museum of Art). The senjafuda mounted in scrapbooks (more than 50 of them) are now housed in Special Collections and University Archives (University of Oregon Libraries), while the loose slips are housed in the Jordan Schnitzer Museum of Art.
>
> >Henry Smith has examined Starr's scholarly interest in Japan in detail, noting Starr's consistent attention to the religious dimension of culture—clearly visible in senjafuda, as this exhibition shows. Smith also notes that Starr's interest in “the social matrices in which these objects came to be collected, depicted, and exchanged in…distinctive subcultures of modern Japan” gives his work value in a contemporary context as well. But Starr had an eye for phenomena that appealed to a playful as well as a scholarly bent. When asked by a reporter for a Japanese newspaper what his interests were, he reeled off a list that began with kappa and tengu. It's no wonder, then, that yōkai are well represented in his senjafuda collection.
```

Here is how it looks when Markdown renders.

>Starr amassed a huge collection of senjafuda both through his frequent attendance at exchange meetings and by procuring scrapbooks put together by other collectors. As a result of his persistence in acquiring senjafuda his collection not only thoroughly documents the years he was active in senjafuda (the 1910s to early 1930s), but also contains examples going back to the mid-19th century. After his death, his senjafuda collection was acquired by Gertrude Bass Warner (1863-1951), a traveler and collector of Japanese, Chinese, and Korean art and founder of the University of Oregon Art Museum (now the Jordan Schnitzer Museum of Art). The senjafuda mounted in scrapbooks (more than 50 of them) are now housed in Special Collections and University Archives (University of Oregon Libraries), while the loose slips are housed in the Jordan Schnitzer Museum of Art.
>
>>Henry Smith has examined Starr's scholarly interest in Japan in detail, noting Starr's consistent attention to the religious dimension of culture—clearly visible in senjafuda, as this exhibition shows. Smith also notes that Starr's interest in “the social matrices in which these objects came to be collected, depicted, and exchanged in…distinctive subcultures of modern Japan” gives his work value in a contemporary context as well. But Starr had an eye for phenomena that appealed to a playful as well as a scholarly bent. When asked by a reporter for a Japanese newspaper what his interests were, he reeled off a list that began with kappa and tengu. It's no wonder, then, that yōkai are well represented in his senjafuda collection.

### Let's apply this to GitHub
We are going to add 1 blockquote to `index.md`.

1. Within the Edit file tab of `index.md`, add a multi-paragraph blockquote within the ordered list under the item "The Star Collection".

Use this text to make the multi-paragraph blockquote.

>Frederick Starr (1858-1933) was an American anthropologist at the University of Chicago who visited Japan frequently between 1904 and 1933. His primary interest during his stays in Japan was the social networks of collectors who were focused on objects associated with the early modern era, particularly collectors of traditional toys and senjafuda. Starr, his traveling companion Manuel Gonzales, and his interpreter Maebashi Hanzan were prominent fixtures at numerous senjafuda exchange meetings in the early 20th century, and Starr became so associated with the senjafuda scene that the press gave him the nickname “Professor Votive Slip” (Ofuda hakushi). Starr also wrote a short book about the history of senjafuda that was published in English in 1917 as The Nosatsu Kai and in Japanese (in a translation and adaptation by Fujisato Kōko) as Nōsatsu shi in 1921.
>
>Starr amassed a huge collection of senjafuda both through his frequent attendance at exchange meetings and by procuring scrapbooks put together by other collectors. As a result of his persistence in acquiring senjafuda his collection not only thoroughly documents the years he was active in senjafuda (the 1910s to early 1930s), but also contains examples going back to the mid-19th century. After his death, his senjafuda collection was acquired by Gertrude Bass Warner (1863-1951), a traveler and collector of Japanese, Chinese, and Korean art and founder of the University of Oregon Art Museum (now the Jordan Schnitzer Museum of Art). The senjafuda mounted in scrapbooks (more than 50 of them) are now housed in Special Collections and University Archives (University of Oregon Libraries), while the loose slips are housed in the Jordan Schnitzer Museum of Art.
>
>Henry Smith has examined Starr's scholarly interest in Japan in detail, noting Starr's consistent attention to the religious dimension of culture—clearly visible in senjafuda, as this exhibition shows. Smith also notes that Starr's interest in “the social matrices in which these objects came to be collected, depicted, and exchanged in…distinctive subcultures of modern Japan” gives his work value in a contemporary context as well. But Starr had an eye for phenomena that appealed to a playful as well as a scholarly bent. When asked by a reporter for a Japanese newspaper what his interests were, he reeled off a list that began with kappa and tengu. It's no wonder, then, that yōkai are well represented in his senjafuda collection.

Here is an example of what the Markdown code looks like.
![Figure showing what Markdown for a multi-paragraph blockquote looks like within the Edit file tab.](/assets/images/markdown-017.png)

2. Click Preview to see how it renders. It should look like the figure below.
![Figure showing what Markdown for a multi-paragraph blockquote looks like within the Edit file tab.](/assets/images/markdown-018.png)


# Let's Make a Commit
Now we're ready to make a commit because you've just finished creating your first webpage that used Markdown to structure text.

1. Go to the bottom of your `index.md` file while still in edit mode.
2. Find the "Commit changes" section
3. Title your commit and then add a description about what you are committing.

**Commit Text Example**

Commit title
>Adding text and images to the file

Commit description
>This is my first attempt at using Markdown with GitHub. I've added - Headings, Paragraphs and Line Breaks, Emphasis, e.g. bold and italics, Lists, e.g. numbered lists and unordered lists, Images, Hyperlinks, and Blockquotes using content from the University of Oregon's Yōkai Senjafuna digital exhibit.

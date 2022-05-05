# Introduction to Markdown
This brief module provides instructions that give newcomers experience using Markdown, a human-readable markup language for adding formatting to plain text files.

## What is Markdown?
Markdown was developed as a simple way to write content for the web without using HTML (hyptertext markup language), a language commonly used to write content for websites.
It allows for a straight-forward way to structure text, links, images, code, tables, and lists within a plain text document without using tags like those used in HTML.

Using Markdown, we can format text using...

- Headings
- Paragraphs and Line Breaks
- Emphasis, e.g. bold and italics
- Lists, e.g. numbered lists and unordered lists
- Images
- Hyperlinks
- Block quotes

We'll cover everything in this list during this learning exercise.
To learn how to use other parts of the Markdown syntax not covered here visit [Markdown Guide](https://www.markdownguide.org/cheat-sheet/).

**Why use Markdown?**
- It can be fast to use while writing webpage content
- It is used all over the place. It's a standard used by GitHub and other tools people use regularly to communicate over the Internet.
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
6. On line 4, add a Heading 2 that reads, `## Section 2`
7. To see how your headings will look once you commit your file, you can "preview" the file: Near the top of the file you're editing, locate and click on the "Preview" tab (to the right of the "Edit File" tab). Preview mode will allow you to see how your headings will render on a webpage. When you're satisfied with the preview and ready to get back to editing, click on the "Edit File" tab.

---

## Step 3. Paragraphs and Line Breaks

Paragraphs in Markdown don't require any special markup.
They can be written exactly as you write them in Microsoft Word, but *without a tabbed first sentence* and *with a blank line in between paragraphs*.
In other words, you can string together sentences one after another as you are used to doing when you write paragraphs in papers or emails, and they will appear in a paragraph on the front end of the webpage.

*However*, be aware that **any text with no empty lines between will be joined into a paragraph.**.
You should also leave an empty line between headings and paragraphs.

For example, take a look at the following three sentences.

**Markdown file view**:

```
This digital exhibition focuses on tiny slips of paper—senjafuda 千社札—that depict Japanese ghosts and monsters—yōkai 妖怪. 
Both senjafuda and yōkai have their roots in Japanese popular culture in the early modern period (17th-19th centuries).

The phenomenon of senjafuda dates back to the late 18th century.
```

**"Front end" view**: 

This digital exhibition focuses on tiny slips of paper—senjafuda 千社札—that depict Japanese ghosts and monsters—yōkai 妖怪. 
Both senjafuda and yōkai have their roots in Japanese popular culture in the early modern period (17th-19th centuries)..

The phenomenon of senjafuda dates back to the late 18th century. 

Since there is an empty line above the third sentence, this starts a new paragraph. 
This gives you the option to write a paragraph all on one line (like a word processor), or to put each sentence on its own line. 
Splitting the sentences can make editing and version control easier.

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
Markdown uses the asterisk (`*`) character to add styling.

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

***The University of Oregon’s collection of senjafuda is one of the largest in the world.***
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

2. To see how your hyperlink will look once you commit your file, you can "preview" the file: Near the top of the file you're editing, locate and click on the "Preview" tab (to the right of the "Edit File" tab). Preview mode will allow you to see how your hyperlink will render on a webpage. When you're satisfied with the preview and ready to get back to editing, click on the "Edit File" tab.

---

## Step 7. Images

Add an image to your webpage using the following formula:

`![alt text description](path to image)"optional image title"`

- **Alt text description**: The alternative text description should be a short description of the image. It will ensure that screen readers can convey the contents of images to users with visual impairments.
- **Path to image**: This is the image's source, and can either be a URL to an image stored elsewhere or a filepath to an image in your current GitHub repository.
- **Optional image title**: If given, the title will display underneath the image. Use the title option to give some context about your image, and keep it brief. If you choose not to include a title, simply end the formula after the "path to image" value, like so: `![alt text description](path to image)`

### Practice Adding Images

1. Copy the following image code and paste it underneath the heading `## Section 2` in your `index.md` file. Make sure to leave a blank line between the Section 2 heading and the following text:

```
![Image of a woman in a kimono dancing. Flames are falling around her and decorative fan shapes are above her.](https://oregondigital.org/downloads/oregondigital:df728t07k)"Kabuki scene with young female dancing"
```

2. To see how your image will look once you commit your file, you can "preview" the file: Near the top of the file you're editing, locate and click on the "Preview" tab (to the right of the "Edit File" tab). Preview mode will allow you to see how your image will render on a webpage. When you're satisfied with the preview and ready to get back to editing, click on the "Edit File" tab.

---

## Step 8. Block quotes

Block quote formatting can be used to distinguish sections of your text.

Add `>` to the beginning of a line of text to make it a block quote.

Example: 

```
> Block quote.
> Continuing the quote.
```

Displays as:

> Block quote.
> Continuing the quote.

1. Copy the following block quote code and paste it underneath the heading `## Section 1` in your `index.md` file. Make sure to leave a blank line between the Section 1 heading and the following text:

```
> Frederick Starr (1858-1933) was an American anthropologist at the University of Chicago who visited Japan frequently between 1904 and 1933.
```

2. To see how your block quote will look once you commit your file, you can "preview" the file: Near the top of the file you're editing, locate and click on the "Preview" tab (to the right of the "Edit File" tab). Preview mode will allow you to see how your block quote will render on a webpage. When you're satisfied with the preview and ready to get back to editing, click on the "Edit File" tab.

---

## Step 9. Commit Your Changes

Congratulations, you've just finished creating your first Markdown document!

1. Scroll to the bottom of your `index.md` file while still in edit mode.
2. Type a commit message into the "Commit changes" text box.
3. Click the green "Commit changes" button to save your changes.

---

## Further Learning

**Ready to continue on in the Learn-Static sequence?**
Next up is [foundations-3-data](https://github.com/learn-static/foundations-3-data).

**Interested in learning more about Markdown?**
Check out these external resources:

- [Markdown Guide](https://www.markdownguide.org/cheat-sheet/)
- [Github Guides: Mastering Markdown](https://guides.github.com/features/mastering-markdown/)

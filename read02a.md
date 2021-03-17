Markdown (Links to an external site.) is a way to style text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like # or *.

 

Syntax guide
Here’s an overview of Markdown syntax that you can use anywhere on GitHub.com or in your own text files.

Headers
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag
Emphasis
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_
Lists
Unordered
* Item 1
* Item 2
  * Item 2a
  * Item 2b
Ordered
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
Images
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
Links
http://github.com - automatic!
[GitHub](http://github.com)
Blockquotes
As Kanye West said:

> We're living the future so
> the present is our past.
Inline code
I think you should use an
`<addr>` element here instead.

GitHub Flavored Markdown
GitHub.com uses its own version of the Markdown syntax that provides an additional set of useful features, many of which make it easier to work with content on GitHub.com.

Note that some features of GitHub Flavored Markdown are only available in the descriptions and comments of Issues and Pull Requests. These include @mentions as well as references to SHA-1 hashes, Issues, and Pull Requests. Task Lists are also available in Gist comments and in Gist Markdown files.

Syntax highlighting
Here’s an example of how you can use syntax highlighting with GitHub Flavored Markdown (Links to an external site.):

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
You can also simply indent your code by four spaces:

    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
Here’s an example of Python code without syntax highlighting:

def foo():
    if not bar:
        return True
Task Lists
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
If you include a task list in the first comment of an Issue, you will get a handy progress indicator in your issue list. It also works in Pull Requests!

Tables
You can create tables by assembling a list of words and dividing them with hyphens - (for the first row), and then separating each column with a pipe |:

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
Would become:

First Header	Second Header
Content from cell 1	Content from cell 2
Content in the first column	Content in the second column
SHA references
Any reference to a commit’s SHA-1 hash (Links to an external site.) will be automatically converted into a link to that commit on GitHub.

16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac
Issue references within a repository
Any number that refers to an Issue or Pull Request will be automatically converted into a link.

#1
mojombo#1
mojombo/github-flavored-markdown#1
Username @mentions
Typing an @ symbol, followed by a username, will notify that person to come and view the comment. This is called an “@mention”, because you’re mentioning the individual. You can also @mention teams within an organization.

Automatic linking for URLs
Any URL (like http://www.github.com/) will be automatically converted into a clickable link.

Strikethrough
Any word wrapped with two tildes (like ~~this~~) will appear crossed out.

Emoji
GitHub supports emoji (Links to an external site.)!

 

Headings (Links to an external site.)
To create a heading, add one to six # symbols before your heading text. The number of # you use will determine the size of the heading.

# The largest heading
## The second largest heading
###### The smallest heading
Rendered H1, H2, and H6 headings

Styling text (Links to an external site.)
You can indicate emphasis with bold, italic, or strikethrough text.

Style	Syntax	Keyboard shortcut	Example	Output
Bold	** ** or __ __	command/control + b	**This is bold text**	This is bold text
Italic	* * or _ _	command/control + i	*This text is italicized*	This text is italicized
Strikethrough	~~ ~~		~~This was mistaken text~~	This was mistaken text
Bold and nested italic	** ** and _ _		**This text is _extremely_ important**	This text is extremely important
All bold and italic	*** ***		***All this text is important***	All this text is important
Quoting text (Links to an external site.)
You can quote text with a >.

In the words of Abraham Lincoln:

> Pardon my French
Rendered quoted text

Tip: When viewing a conversation, you can automatically quote text in a comment by highlighting the text, then typing r. You can quote an entire comment by clicking , then Quote reply. For more information about keyboard shortcuts, see "Keyboard shortcuts (Links to an external site.)."

Quoting code (Links to an external site.)
You can call out code or a command within a sentence with single backticks. The text within the backticks will not be formatted.

Use `git status` to list all new or modified files that haven't yet been committed.
Rendered inline code block

To format code or text into its own distinct block, use triple backticks.

Some basic Git commands are:
```
git status
git add
git commit
```
Rendered code block

For more information, see "Creating and highlighting code blocks (Links to an external site.)."

Links (Links to an external site.)
You can create an inline link by wrapping link text in brackets [ ], and then wrapping the URL in parentheses ( ). You can also use the keyboard shortcut command + k to create a link.

This site was built using [GitHub Pages](https://pages.github.com/).

Rendered link

Tip: GitHub automatically creates links when valid URLs are written in a comment. For more information, see "Autolinked references and URLS (Links to an external site.)."

Section links (Links to an external site.)
You can link directly to a section in a rendered file by hovering over the section heading to expose the link:

Section link within the README file for the github/scientist repository

Relative links (Links to an external site.)
You can define relative links and image paths in your rendered files to help readers navigate to other files in your repository.

A relative link is a link that is relative to the current file. For example, if you have a README file in root of your repository, and you have another file in docs/CONTRIBUTING.md, the relative link to CONTRIBUTING.md in your README might look like this:

[Contribution guidelines for this project](docs/CONTRIBUTING.md)
GitHub will automatically transform your relative link or image path based on whatever branch you're currently on, so that the link or path always works. You can use all relative link operands, such as ./ and ../.

Relative links are easier for users who clone your repository. Absolute links may not work in clones of your repository - we recommend using relative links to refer to other files within your repository.

Lists (Links to an external site.)
You can make an unordered list by preceding one or more lines of text with - or *.

- George Washington
- John Adams
- Thomas Jefferson
Rendered unordered list

To order your list, precede each line with a number.

1. James Madison
2. James Monroe
3. John Quincy Adams
Rendered ordered list

Nested Lists (Links to an external site.)
You can create a nested list by indenting one or more list items below another item.

To create a nested list using the web editor on GitHub or a text editor that uses a monospaced font, like Atom (Links to an external site.), you can align your list visually. Type space characters in front of your nested list item, until the list marker character (- or *) lies directly below the first character of the text in the item above it.

1. First list item
   - First nested list item
     - Second nested list item
Nested list with alignment highlighted

List with two levels of nested items

To create a nested list in the comment editor on GitHub, which doesn't use a monospaced font, you can look at the list item immediately above the nested list and count the number of characters that appear before the content of the item. Then type that number of space characters in front of the nested list item.

In this example, you could add a nested list item under the list item 100. First list item by indenting the nested list item a minimum of five spaces, since there are five characters (100. ) before First list item.

100. First list item
     - First nested list item
List with a nested list item

You can create multiple levels of nested lists using the same method. For example, because the first nested list item has seven spaces (␣␣␣␣␣-␣) before the nested list content First nested list item, you would need to indent the second nested list item by seven spaces.

100. First list item
     - First nested list item
       - Second nested list item
List with two levels of nested items

For more examples, see the GitHub Flavored Markdown Spec (Links to an external site.).

Task lists (Links to an external site.)
To create a task list, preface list items with a regular space character followed by [ ]. To mark a task as complete, use [x].

- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request
Rendered task list

If a task list item description begins with a parenthesis, you'll need to escape it with \:

- [ ] \(Optional) Open a followup issue

For more information, see "About task lists (Links to an external site.)."

Mentioning people and teams (Links to an external site.)
You can mention a person or team (Links to an external site.) on GitHub by typing @ plus their username or team name. This will trigger a notification and bring their attention to the conversation. People will also receive a notification if you edit a comment to mention their username or team name. For more information about notifications, see "About notifications (Links to an external site.)."

@github/support What do you think about these updates?

Rendered @mention

When you mention a parent team, members of its child teams also receive notifications, simplifying communication with multiple groups of people. For more information, see "About teams (Links to an external site.)."

Typing an @ symbol will bring up a list of people or teams on a project. The list filters as you type, so once you find the name of the person or team you are looking for, you can use the arrow keys to select it and press either tab or enter to complete the name. For teams, enter the @organization/team-name and all members of that team will get subscribed to the conversation.

The autocomplete results are restricted to repository collaborators and any other participants on the thread.

Referencing issues and pull requests (Links to an external site.)
You can bring up a list of suggested issues and pull requests within the repository by typing #. Type the issue or pull request number or title to filter the list, and then press either tab or enter to complete the highlighted result.

For more information, see "Autolinked references and URLs (Links to an external site.)."

Referencing external resources (Links to an external site.)
If custom autolink references are configured for a repository, then references to external resources, like a JIRA issue or Zendesk ticket, convert into shortened links. To know which autolinks are available in your repository, contact someone with admin permissions to the repository. For more information, see "Configuring autolinks to reference external resources (Links to an external site.)."

Content attachments (Links to an external site.)
Some GitHub Apps provide information in GitHub for URLs that link to their registered domains. GitHub renders the information provided by the app under the URL in the body or comment of an issue or pull request.

Content attachment

To see content attachments, you must have a GitHub App that uses the Content Attachments API installed on the repository. For more information, see "Installing an app in your personal account (Links to an external site.)" and "Installing an app in your organization (Links to an external site.)."

Content attachments will not be displayed for URLs that are part of a markdown link.

For more information about building a GitHub App that uses content attachments, see "Using Content Attachments (Links to an external site.)."

Using emoji (Links to an external site.)
You can add emoji to your writing by typing :EMOJICODE:.

@octocat :+1: This PR looks great - it's ready to merge! :shipit:

Rendered emoji

Typing : will bring up a list of suggested emoji. The list will filter as you type, so once you find the emoji you're looking for, press Tab or Enter to complete the highlighted result.

For a full list of available emoji and codes, check out the Emoji-Cheat-Sheet (Links to an external site.).

Paragraphs (Links to an external site.)
You can create a new paragraph by leaving a blank line between lines of text.

Ignoring Markdown formatting (Links to an external site.)
You can tell GitHub to ignore (or escape) Markdown formatting by using \ before the Markdown character.

Let's rename \*our-new-project\* to \*our-old-project\*.

To see a list of every image we support, check out the Emoji Cheat Sheet
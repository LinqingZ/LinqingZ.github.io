1. `git init`: Creates a new Git repository in the current directory.
2. `git clone <repository>`: Copies a repository from a remote source to your local machine.
3. `git add <file>`: Adds a file to the staging area for the next commit.
4. `git commit -m "<message>"`: Records the changes in the repository, accompanied by a descriptive message.
5. `git status`: Displays the current state of the repository, including modified, staged, and untracked files.
6. `git log`: Shows a chronological list of commits, including their commit messages and identifiers.
7. `git branch`: Lists all branches in the repository.
8. `git branch <branch-name>`: Creates a new branch with the specified name.
9. `git checkout <branch-name>`: Switches to the specified branch.
10. `git merge <branch-name>`: Integrates changes from the specified branch into the current branch.
11. `git pull`: Fetches and merges changes from a remote repository to the current branch.
12. `git push`: Uploads local branch commits to a remote repository.
13. `git remote add <name> <url>`: Associates a remote repository URL with a name.
14. `git remote -v`: Lists all remote repositories associated with the current repository.
15. `git diff`: Shows the differences between the current state and the previous commit.
16. `git reset <file>`: Unstages a file, removing it from the staging area.
17. `git stash`: Temporarily stores modified and staged changes, allowing you to switch branches.
18. `git tag <tag-name>`: Creates a lightweight tag for the current commit.
19. `git checkout <commit-id>`: Checks out a specific commit, creating a "detached HEAD" state.


###Markdown (.md) files are widely used for creating structured and formatted documentation. Here are some tips to effectively use Markdown files:

1. Use headings: Utilize the various heading levels (e.g., `#`, `##`, `###`) to organize your content into sections and subsections. Headings make your document easy to navigate and provide a clear hierarchy.
# Heading 1
## Heading 2
### Heading 3

2. Formatting text: Markdown provides simple ways to format text. You can use asterisks or underscores to emphasize (`*italic*` or `_italic_`) or make text bold (`**bold**` or `__bold__`). You can also create inline code snippets with backticks (` `).
*Italic text*
**Bold text**
`Inline code`

3. Lists: Markdown supports both ordered and unordered lists. Use `-` or `*` for unordered lists and numbers for ordered lists. Indentation is important to maintain the correct list structure.
- Item 1
- Item 2
- Item 3
1. First item
2. Second item
3. Third item

4. Links: Create hyperlinks by enclosing the link text in square brackets `[ ]` and the URL in parentheses `( )`. For example, `[OpenAI](https://openai.com)` will create a link to the OpenAI website.
[OpenAI](https://openai.com)

5. Images: Embed images in your Markdown file using the following syntax: `![Alt Text](image-url)`. Replace `Alt Text` with a descriptive alternative text for accessibility and `image-url` with the URL or path to the image file.
![Alt Text](https://example.com/image.jpg)

6. Code blocks: Presenting code snippets or blocks is essential in technical documentation. Use triple backticks (```) before and after the code block to create a fenced code block. You can also specify the language for syntax highlighting after the opening backticks, such as "```python".
```python
def greet():
    print("Hello, world!")
```
Java Code
```java
public class HelloWorld {
public static void main(String[] args) {
System.out.println("Hello, World!");
}
}
```
7. Tables: Markdown allows you to create simple tables using pipe `|` characters to separate columns and hyphens `-` to define the header row. You can also align columns using colons `:`.
Tables:

8. Horizontal rules: Insert a horizontal rule to visually separate sections by using three hyphens (`---`), three asterisks (`***`), or three underscores (`___`) on a separate line.

8. Horizontal rule:

9. Escape characters: Markdown uses certain characters for formatting. If you want to display those characters as regular text, you can use the backslash `\` to escape them. For example, to display an asterisk without formatting, use `\*`.

10. Preview and test: To ensure your Markdown file appears as intended, preview it in a Markdown editor or use online Markdown editors that provide live previews. This helps you catch any formatting or syntax errors before publishing or sharing the file.




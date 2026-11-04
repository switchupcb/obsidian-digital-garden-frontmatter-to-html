# Obsidian Digital Garden Frontmatter to HTML

You use this [Obsidian Digital Garden](https://github.com/oleeskild/obsidian-digital-garden) community plugin to add a note's frontmatter to the note's published HTML webpage body.

## How do you use this plugin?

You must perform the following steps for your note's frontmatter to be added the note's published HTML webpage body.
1. **Let frontmatter passthrough** - Toggle `let all frontmatter through (dg-pass-frontmatter)` to **ON** in the [note settings](https://docs.forestry.md/getting-started/03-note-settings/) _\[Obsidian Settings > Community Plugins > Digital Garden Settings > Display (Manage Note Settings) > `let all frontmatter through (dg-pass-frontmatter)` > Apply changes to site\]_.
2. **Publish Notes** - Use the command palette to _`Digital Garden: Publish All Notes Marked For Publish`: Your note's frontmatter is not sent to the site template until this happens_.
3. **Install Frontmatter to HTML** - Install this Obsidian Digital Garden community plugin from the [note settings](https://docs.forestry.md/getting-started/03-note-settings/) _\[Obsidian Settings > Community Plugins > Digital Garden Settings > Plugins (Manage plugins) > Browse & Install > `Frontmatter to HTML by SwitchUpCB` or Install from GitHub with `https://github.com/switchupcb/obsidian-digital-garden-frontmatter-to-html`\]_.

## Why don't you see the frontmatter properties?

You must style the frontmatter property HTML elements to see the frontmatter properties on the webpage.

**The frontmatter properties are hidden with the CSS properties `display: none` and `visibility: hidden` by default.** So, the frontmatter data is in the webpage HTML source code, but hidden from view.

_You can confirm this behavior from the webpage with `inspect` tools (e.g., `inspect element`)_.

### How do you style the frontmatter properties?

You can style the frontmatter property elements with CSS.

There are multiple ways to add custom CSS to an Obsidian Digital Garden.
1. You can implement the `<style>` tag in the markdown note (from your Obsidian application).
2. You can implement Dynamic CSS/SCSS using [Obsidian Digital Garden](https://docs.forestry.md/advanced/css-customization/).
3. `forestry.md` users can implement Dynamic CSS/SCSS from the dashboard "Appearance" page _\[Click Garden Name > Appearance > Scroll to Custom styles > Add style\]_.

### How do you move the frontmatter properties?

You can move the frontmatter property elements by adding JavaScript to your markdown note (from your Obsidian application) with the `<script>` tag.









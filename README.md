news
====

Contributing news content
---

Please review [template.md](template.md) for a sample layout and structure of a post. You can use standard Markdown to write your material (which includes HTML as well, see [Daring Fireball's][df] syntax guide for Markdown for more information). There are also some specific Jekyll related formatting and syntax you can use such as highlighting code blocks, read [Jekyll's][jkdoc] for help.

The RSS feed is automatically built from the list of posts and added to ``feed.xml``.

Please use the date formatting "FullYear-Month-Day" for both the naming of files and the date within the post's YAML, example file name: 2014-08-18-title-of-post.md

[df]: http://daringfireball.net/projects/markdown/syntax
[jkdoc]: http://jekyllrb.com/docs/home/

Modifying layouts, includes, etc
---

``_includes/`` will contain snippets that are included upon generation of the site itself. This involves the ``<head>``, site header, navigation, and footer (only seen at bottom of individual post page).

``_layouts/`` contains the two primary layouts that build the structure of the site itself. ``default.html`` is the base structure which everything is built off of. ``post.html`` is the structure for individual posts.

``main.css`` is the primary stylesheet for the entire site. ``syntax.css`` is the stylesheet for code blocks (``<pre><code>``).

# Dungeon World Compendium Classes

* Built with [Jekyll-db](https://github.com/rypan/jekyll-db), which uses [Jekyll](http://jekyllrb.com/), [ListJS](http://listjs.com/), and [Bootstrap](http://getbootstrap.com/).


## View Playbooks
[Visit the website](https://exposit.github.io/dw-ccs/)

## Submit a Playbook
[Create a new file here](https://github.com/exposit/dw-ccs/new/gh-pages/_posts) and submit a pull request.  
File name format is `{[currentyear}}-{{currentmonth}}-{{currentday}}-{{classname}}.md`.  
Example: `2018-01-03-the-dw-class.md`.

Verify that the chosen date is not in use for the class name you want first.

NOTE: some fields may not be in use indefinitely, please just do your best.

### File Format
Example format below. Copy and paste and change for the playbook you're submitting. You can also choose an existing file as a template.

```yaml
---
layout: entry
link: http://www.thedwclass.world
author: ['Jane Doe', 'John Smith']
source: The DW Supplement
source-url: http://thedungeon.world/supplement

excerpt: Put the description of your class here. OPTIONAL

trigger: When you do this thing...

categories:
- category (use an existing category please, otherwise you'll get a not-found)

license: cc-by, cc-by-sa, non-open, unknown
cost: paid, free, pwyw

tags:
- setting (if there is one)
- pack (if there is one)
- class tags like armored, tank, holy, warrior, music, etc.

---

  Any content you want shown on the individual entry page should go here. If you don't use an
  explicit excerpt field above, one will be generated here, using the first 200 characters.
  Note: Please use your own words or just a short quote from the product page.

```

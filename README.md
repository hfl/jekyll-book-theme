# What's `jekyll-book-theme`?

It's another Jekyll static site generator theme for classic books
(e.g. Strange Case of Dr. Jekyll and Mr Hyde, A Tale of Two Cities, The Trial, etc.)
that is, a ready-to-fork template pack.

See a live demo @ [`drjekyllthemes.github.io/jekyll-book-theme` »](http://drjekyllthemes.github.io/jekyll-book-theme/)

For example:

```
├── _config.yml                               # book configuration
├── _chapters                                 # sample chapters
|   ├── 01.md
|   ├── 02.md
|   ├── ...
|   └── 10.md
├── _layouts                           
|   └── default.html                   # master layout template
├── css                               
|   ├── _settings.scss                 # style settings (e.g. variables)
|   └── style.scss                     # master style page
└── index.html                         # all-in-one page book template
```

will result in an all-in-one book page:

```
└── _site                                # output build folder; site gets generated here
    ├── css
    |   └── style.css                    # styles for pages (copied 1:1 as is)
    └── index.html                       # all-in-one book page
```


## Example Classic

### Strange Case of Dr. Jekyll and Mr. Hyde

by Robert Louis Stevenson

> Mr. Utterson the lawyer was a man of a rugged countenance, that was
> never lighted by a smile; cold, scanty and embarrassed in
> discourse; backward in sentiment; lean, long, dusty, dreary, and
> yet somehow lovable.

- 01 // [Story of the Door](_chapters/01.md)
- 02 // [Search for Mr. Hyde](_chapters/02.md)
- 03 // [Dr. Jekyll was Quite at Ease](_chapters/03.md)
- 04 // [The Carew Murder Case](_chapters/04.md)
- 05 // [Incident of the Letter](_chapters/05.md)
- 06 // [Remarkable Incident of Dr. Lanyon](_chapters/06.md)
- 07 // [Incident at the Window](_chapters/07.md)
- 08 // [The Last Night](_chapters/08.md)
- 09 // [Dr. Lanyon's Narrative](_chapters/09.md)
- 10 // [Henry Jekyll's Full Statement of the Case](_chapters/10.md)



## Meta

**License**

The theme is dedicated to the public domain.
Use it as you please with no restrictions whatsoever.

**Questions? Comments?**

Post them to the [jekyll talk forum](https://talk.jekyllrb.com). Thanks!


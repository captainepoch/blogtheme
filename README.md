# Blogtheme
The theme that generates my website. 100% free of JavaScript. It's based on
[simple-style][simple-style].

You can look at the theme at [adol.pw][blog].

# Configuration
There is a [`config.toml`][config] example file in the root of the project.

# Comments
This theme is provided with a `comment.html` where your preferred comment
service should be added.

The comment section provided to the blog is powered by [SourceHut
mailist][srht_lists]. If you want to use another, please be free to delete all
the content inside of the block and use your preferred comment service.

Also, you may delete the `srht_*` configuration variables at the `config.toml`
file and use yours.

## SourceHut mailist comments
To setup your public inbox link and the `mailto` link, you have to change the
following values in the `config.toml` file:

  - `srht_public_inbox`: link to your public inbox (e.g.
    `https://lists.sr.ht/~captainepoch/public_inbox`).
  - `srht_mail`: link for **sending** the email (e.g.
    `~captainepoch/public_inbox@lists.sr.ht`).
  - `srht_subject`: `true` or `false`. This will include, at the end, `Re:
    {TITLE}` (where `{TITLE}` it's your post's title) as a subject.

You can view this at any of my posts at [adol.pw][blog].

# License
[MIT][license].


  [blog]: https://adol.pw
  [config]: https://git.sr.ht/~captainepoch/blogtheme/tree/master/config.toml
  [license]: https://git.sr.ht/~captainepoch/blogtheme/tree/master/COPYING
  [simple-style]: https://git.sr.ht/~captainepoch/simple-style
  [srht_lists]: https://lists.sr.ht/

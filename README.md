# Bloggy

[![Dependency Status](https://gemnasium.com/erictheise/bloggy.png)](https://gemnasium.com/erictheise/bloggy)

A few years back, I wanted to incorporate a blog into a Rails application. Whether due to an unfortunate google search
or the actual state of [Jekyll](http://jekyllrb.com/) development at the time, I ended up using
[Bloggy](https://github.com/zbruhnke/bloggy). It, too, had some issues, but it had its smart and enthusiastic users and
it seemed to provide a straight path to accomplishing what I hoped to accomplish.

Eventually I created this fork to strip out the unused requirements that made it difficult to track Jekyll's progress.
And at this point in time, I've ceased using Bloggy entirely; realistically, it adds nothing that offsets the barriers
it creates to using many of Jekyll's desirable features. You should be able to do anything you need to do through the
configuration of `source:` and `destination:` in `_config.yaml` and your layouts.

When [Gemnasium](http://gemnasium.com/) alerts me to bump a version of a dependency, I'll do that, and keep this
repository going for those who, for some reason, can't migrate away. But I'd encourage you to maneuver your blog away
from relying on Bloggy and just use Jekyll directly.

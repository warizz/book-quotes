# Write code that is easy to delete, not easy to extend.

[link](http://programmingisterrible.com/post/139222674273/write-code-that-is-easy-to-delete-not-easy-to)

>Every line of code written comes at a price: maintenance. To avoid paying for a lot of code, we build reusable software. The problem with code re-use is that it gets in the way of changing your mind later on.

>The more consumers of an API you have, the more code you must rewrite to introduce changes. Similarly, the more you rely on an third-party api, the more you suffer when it changes. Managing how the code fits together, or which parts depend on others, is a significant problem in large scale systems, and it gets harder as your project grows older.

>My point today is that, if we wish to count lines of code, we should not regard them as “lines produced” but as “lines spent”

...

>Even so, the easiest code to delete is the code you avoided writing in the first place.

...

>It’s good to copy-paste code a couple of times, rather than making a library function, just to get a handle on how it will be used. Once you make something a shared API, you make it harder to change.

...

>It’s simpler to delete the code inside a function than it is to delete a function.

...

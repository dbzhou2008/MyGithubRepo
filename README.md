# MyGithubRepo
this is public github repo
The expressions outer::inner::foo() and outer::foo() are interchangeable. Inline namespaces are primarily intended for ABI compatibility across versions.
Namespaces can be confusing, because they complicate the mechanics of figuring out what definition a name refers to.
Inline namespaces, in particular, can be confusing because names aren't actually restricted to the namespace where they are declared. They are only useful as part of some larger versioning policy.
In some contexts, it's necessary to repeatedly refer to symbols by their fully-qualified names. For deeply-nested namespaces, this can add a lot of clutter.


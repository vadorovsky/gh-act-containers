# containers

Set of container images which can be used in GitHub actions, with an emphasis
on musl-based Linux distros.

To make it as easy as possible to use them in your actions, they come with:

- Configured `sudo`.
- A regular user (`runner`), which belongs to the `wheel` group.

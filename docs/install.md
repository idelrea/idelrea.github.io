# Onion Launchpad installation

## Getting the code

The Onion Launchpad codebase can be obtained directly from the [repository][]
by running the following command:

    git clone --recursive https://gitlab.torproject.org/tpo/onion-services/onion-launchpad.git

[repository]: https://gitlab.torproject.org/tpo/onion-services/onion-launchpad

## Dependencies

This project relies on [Lektor](https://www.getlektor.com/)
and some dependencies detailed at the
[TPA CI templates](https://gitlab.torproject.org/tpo/tpa/ci-templates) project.

A [provision script][] is available as an example of dependency
installation from a [Debian][] stable system, and can be adapted to your own environment
and needs.

[provision script]: https://gitlab.torproject.org/tpo/onion-services/onion-launchpad/-/blob/main/scripts/provision?ref_type=heads
[Debian]: https://www.debian.org

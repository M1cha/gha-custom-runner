# gha-custom-runner

I need certain changes to [actions/runner](https://github.com/actions/runner)
and the workflow in this repository automatically applies them to new releases
and creates a patched release with the same tag and asset names.

This way, this repository can be used as a drop-in replacement URL when updating
the runner without it's self-update e.g. using ansible.

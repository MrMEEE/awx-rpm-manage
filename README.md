# awx-rpm-manage

The AWX-RPM Management Tool has been released :)

So.. what does it do?

For now, it does "only" updating and control of package exclude lists..

But the exclude lists should help solve previous package conflicts, please report back if it doesn't.

So right now the only command available is:

```awx-rpm-manage update```

Which should update all packages on the system, also the awx-rpm dependencies and update awx-rpm to newest package with the current release.

24.0.0 has just been released, but I hope to have release "awx-rpm-manage upgrade" ready together with the next release.

After that, installation and configuration will be in focus.

awx-rpm-manage is available as rpm in the 24.0.0 repo.

All awx-rpm-manage issues should be reported at: https://github.com/MrMEEE/awx-rpm-v2/issues

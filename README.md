# awx-rpm-manage

The AWX-RPM Management Tool has been released :)

So.. what does it do?

For now, it does "only" updating, upgrading and control of package exclude lists..

But the exclude lists should help solve previous package conflicts, please report back if it doesn't.

So right now the commands available is:

```awx-rpm-manage update```

Update all packages on the system, also the awx-rpm dependencies and update awx-rpm to newest package with the current release.

```awx-rpm-manage upgrade```

Give the choice to upgrade to a newer release.


Installation and configuration will be in focus, now that upgrading works.

awx-rpm-manage is available as rpm in the 24.0.0 and 24.1.0 repos.

```dnf install awx-rpm-manage```

All awx-rpm-manage issues should be reported at: https://github.com/MrMEEE/awx-rpm-v2/issues

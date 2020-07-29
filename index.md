## Linux <3 FreeBSD

Software from Linux and available only on Linux re-engineered for FreeBSD users. Maintained by [Kai Lyons](https://twitter.com/kailikeslinux), founder of [Fivnex](https://fivnex.co) trying to make FreeBSD and Linux interchangable

### What are our projects?
- `Snap4BSD`: A project dedicated to running the Snap packaging system on FreeBSD, and packaging the final result (without the closed-source backend).
- `Flatpak4BSD`: A project dedicated to running Flatpaks on FreeBSD, just like we are doing for Snaps.
- `BSDAppImage`: Another project dedicating time to get AppImages working (natively) on FreeBSD.
- `Debany`: A project to run `.deb` package installation on FreeBSD

### What needs to be done?
For each project, there are several limitations we need to overcome, the biggest being the native ports for Snap, Flatpak, and AppImage to be ran on FreeBSD. It is possible, but difficult to hack together for an average user. Especially the Systemd requirement. We will need R&D, and a lot of time and energy to properly port these projects without Systemd, the only reason for that is Systemd is darn-near impossible to install on FreeBSD without risking speed/usability in many of the tries I did to get Snap working on FreeBSD. While it is possible to do it, it is best we mess with these systems and push them into the traditional BSD init system FreeBSD uses.

### Where to join? 
For now, just submit projects to kai@fivnex.co to submit new projects and to join the org on GitHub. Otherwise just fork and send merge requests to help out! Have a wonderful day, and Linux <3 FreeBSD!

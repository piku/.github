`piku` allows you do `git push` deployments to your own servers, no matter how small they are.

It is currently able to deploy, manage and independently scale multiple applications per host on both ARM and Intel architectures, and works on any cloud provider (as well as bare metal) that can run Python, `nginx` and `uwsgi`.

### Core values

 * Must run on low end devices.
 * Accessible to hobbyists and K-12 schools.
 * ~1500 lines readable code.
 * Functional code style.
 * Few (single?) dependencies
 * [12 factor app](https://12factor.net).
 * Simplify user experience.
 * Cover 80% of common use cases.
 * Sensible defaults for all features.
 * Leverage distro packages in Raspbian/Debian/Ubuntu (Alpine and RHEL support is WIP)
 * Leverage standard tooling (`git`, `ssh`, `uwsgi`, `nginx`).
 * Preserve backwards compatibility where possible

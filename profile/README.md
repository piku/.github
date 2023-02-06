[`piku`](https://github.com/piku/piku) allows you to Heroku-style `git push` deployments to your own servers, no matter how small they are, and with any runtime (Python, Ruby, Java, NodeJS, etc. - add your own here.) 

It is currently able to deploy, manage and independently scale multiple applications per host on both ARM and Intel architectures, and works on any cloud provider (as well as bare metal) that can run Python, `nginx` and `uwsgi`.

### Core values

 * Must run on low end devices (but works fine on any hardware)
 * Accessible to hobbyists and K-12 schools (simple to understand, use and maintain)
 * ~1500 lines readable code.
 * Functional code style.
 * Few (single?) dependencies (just one, really)
 * Encourages the use of the [12 factor app](https://12factor.net) approach.
 * Simplify user experience.
 * Cover 80% of common use cases.
 * Sensible defaults for all features.
 * Leverage distro packages in Raspbian/Debian/Ubuntu 
 * Leverage standard OS packages and tooling (`git`, `ssh`, `uwsgi`, `nginx`).
 * Preserve backwards compatibility where possible

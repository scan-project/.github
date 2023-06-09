# The Scan Project

The (unnamed) **Scan Project** aka TSP is currently in Stealth mode.

* Try the free version of our scanner here: <https://docs.scanproject.io> ([DockerHub](https://hub.docker.com/r/scanproject/standalone))
* Sign-up for beta: <https://scanproject.io>

**Scan Project** is a solution that takes care of running multiple external
checks in a CI/CD pipeline, such as linters, quality tools, and security
scanners, including Static ([SAST](https://en.wikipedia.org/wiki/Static_application_security_testing)), Composition ([SCA](https://en.wikipedia.org/wiki/Software_composition_analysis)), Dynamic ([DAST](https://en.wikipedia.org/wiki/Dynamic_application_security_testing)), and even penetration testing by humans, and:

* Orchestrates and simplifies the execution of multiple linting, testing,
  quality and security tools.
* It knows and automatically configures the most well-known tools.
* It serves as a central point to collect, process, compare, join and prioritize
  issues identified by these tools.
* Allows breaking the pipeline when a specified issue threshold is reached.
* Differentiates between quick and long-running scans, allowing making specified
  decisions automatically. For example, the decision to proceed with a fix
  branch merge and deployment to dev if a security scanner was still running,
  but the change was small, and other tools have not detected any major issues.
  But depending on the set parameters, it will still track it and will block the
  promotion to Production when the security scanner catches up and reports
  something critical.

**Screenshots** are currently available in
[Michael's blog](https://blog.samoylenko.me/).

**Project Logo** by [sonictheprogrammer](https://github.com/sonictheprogrammer).

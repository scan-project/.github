# The Scan Project

**The Scan Project** is currently in Private mode. Meanwhile, please feel free
to use our vulnerable sample applications.

**The Scan Project** is a solution that takes care of running multiple external
checks in a CI/CD pipeline, such as linters, quality tools, and security
scanners (including SAST, DAST, and even penetration testing by humans) and:

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

Discord: <https://discord.gg/9QCCP3ze>  
Telegram: <https://t.me/thescanprojectchat>  

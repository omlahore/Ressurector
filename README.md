# Resurrector

**Resurrector** is a lightweight, self-healing application monitor for Linux and Unix systems. It actively monitors processes, system health, and application endpoints — taking automatic action when issues are detected to keep your critical services running smoothly.

---

## Features

- Monitor process states (Running, Sleeping, Zombie, etc.)
- Check disk space usage and alert on high utilization
- Analyze system memory usage (physical, swap, virtual)
- Validate application health via HTTP/HTTPS checks
- Automatic process recovery (kill and restart dead/zombie processes)
- Configurable memory and disk thresholds
- Detailed logging with adjustable verbosity
- Designed to run easily as a cron job or daemon
- CLI-based configuration options for flexibility

---

## Installation

```bash
gem install log4r
# Clone the repository and set up your environment

# Auto-Deploy to Pantheon or WP Engine

This repository contains GitHub workflows and actions that deploy repository code to a Pantheon development/multidev, or WP Engine environment. The Shell script that runs the actual deployment, where code is pushed to the remote repository, can be found in [push-to-remote-repo/run.sh](./push-to-remote-repo/run.sh).

The Pantheon workflow also includes creating/deleting a multidev environment, and promoting code from dev to test, or test to live.

## Auto-Deployment Setup 

- Pantheon → [PANTHEON_SETUP.md](./PANTHEON_SETUP.md)
- WP Engine → [WPENGINE_SETUP.md](./WPENGINE_SETUP.md)
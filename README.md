# Sample Python Application for `piku`

This is a simple Python app that demonstrates:

- HTTP port selection via the `PORT` variable (set in `ENV`)
* An independent worker process (that is auto-restarted upon exit)
* A daily scheduled worker that runs every day at 6PM
* Another independent worker with a built-in scheduler

To publish this app to `piku`, clone the repository and run the following commands:

```bash
git remote add piku piku@your_server:sample_python_app
git push piku master
```

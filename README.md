# DevOps Dashboard Exercise

A static dashboard and GitHub Actions trigger used for a DevOps coursework experiment.

Read dashboard.html for the interface and the trigger workflow for the automation definition. No Lambda handler is checked into this repository.

## Start reading

- [`dashboard.html`](dashboard.html)

## View locally

Serve the repository directory with a local static server, for example:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open [dashboard.html](http://127.0.0.1:8000/dashboard.html). Any CDN libraries, hosted APIs, or map providers referenced by the page still require network access.

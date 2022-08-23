# CareerMap

This is a fork of https://github.com/skamsie/berlin-ubahn-map and has been modified to show a CareerMap in Tube like format.

### Run locally

Even if the application only uses client side javascript, you still need to run a small web server to prevent *CORS* errors, because of loading *json* files from the local filesystem. A simple option would be Python's `SimpleHTTPServer` (or `http.server`, depending on the version of Python installed.). More about it [here](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/set_up_a_local_testing_server)

```bash
> python -m http.server
Serving HTTP on 0.0.0.0 port 8000 (http://0.0.0.0:8000/) ...
```

# Testing Varnish with Varnishtest 

This repository provides VTC examples (see `/tests`).

# Varnishtest with Docker

Using the official Varnish Docker image, a test can be run this way :

```sh
docker run --rm -v $(pwd):/etc/varnish varnish:6 varnishtest /etc/varnish/tests/clean_utm_parameters.vtc
```

# Contribute

Feel free to add your own test cases. Open an issue or submit PRs.

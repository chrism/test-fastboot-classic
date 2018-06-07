# test-fastboot-classic

This is to test that using the classic application with a combination of ember-cli-fastboot 1.1.4-beta.1 and the latest canary of Ember works fine with Fastboot rehydration.

Clone this repo, run `yarn` and then start the server with the experimental render flag.

```
EXPERIMENTAL_RENDER_MODE_SERIALIZE=true ember s
```

goto `http://localhost:4200/` in your browser.

You should see in the markup the `<!--%+b:0%-->` boundary tags denoting nodes.

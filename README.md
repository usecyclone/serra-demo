# Usage

Try running a sample pipeline! First, fork this repl!The demo.yml file in this directory contains an example of a data pipeline made for the serra framework. It can be run in the shell tab with the following commands:

```bash
pip install serra-cli
serra run demo
```

# Debug

Now let's run a broken pipeline!

```bash
serra run debug_example
```

We see that the pipeline is breaking at the JoinTransformer.

In a traditional SQL script, the error would be much harder to find based on their messages. With Serra, we locate exactly which step it's happening and why!

# Documentation

You can make modifications to the pipeline, or create additional jobs as well.

Check out the docs below!

https://serratech.gitbook.io/documentation/

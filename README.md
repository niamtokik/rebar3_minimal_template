# rebar3_minimal_template

A minimal template for rebar3.

## Usage

1. check if you don't already have any local templates

```sh
ls -l ${HOME}/.rebar3/templates
```

2. copy `rebar3/templates` in `${HOME}/.rebar3`

```sh
cp -rp rebar3/templates ${HOME}/.rebar3
```

3. create a new project

```sh
rebar3 new minimal name=my_minimal_app
```

4. hack around.

Note: one can also use directly the git repository instead.

# References and Resources

[Rebar3 Templates](https://www.rebar3.org/docs/tutorials/templates/)

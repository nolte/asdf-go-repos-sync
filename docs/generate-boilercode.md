# BoilerCode

```sh

asdf shell python 3.7.1

cookiecutter gh:nolte/cookiecutter-gh-project \
    module_slug="asdf-go-repos-sync" \
    topics="asdf-plugin, asdf" \
    description="asdf plugin for go-repos-sync" \
    template_issues="y" \
    template_pull_request="y" \
    workflow_deliver_docs_enabled="y" \
    dependabot_github_actions="y" \
    dependabot_pip="n" \
    dependabot_gitsubmodule="n" \
    dependabot_docker="n" \
    -f --no-input
```

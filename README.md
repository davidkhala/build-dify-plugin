# davidkhala/build-dify-plugin

Action to 
- Download latest cli of dify-plugin-daemon release
- Package plugin project into `*.difypkg` file under directory ${GITHUB_WORKSPACE}
```
- uses: davidkhala/build-dify-plugin@main
  with:
    pyproject-directory: . # the directory of pyproject.yaml
```

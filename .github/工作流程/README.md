name: CI

on: [push]#hello-world

你好
职位：我是
  建立：我是新来的，喜欢C语言和java语言

    runs-on: ubuntu-latest

    steps:
    - uses: actions/checkout@v1
    - name: Run a one-line script
      run: echo Hello, world!
    - name: Run a multi-line script
      run: |
        echo Add other actions to build,
        echo test, and deploy your project.

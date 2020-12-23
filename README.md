# github-actions-demo
Repo to test and demo Github actions

Github Action Struction for YAML

name: shell commands

on: push

jobs:
  job1name:
    runs-on: ubuntu-latest
    steps:
      - name: step1injob1
        run: echo "Hello World"
      - name: step2injob1
        run: |
          node -v
          npm -v
  job2name:
    runs-on: ubuntu-latest
    steps:
      - name: step1injob2
        run: echo "Hello World"
      - name: step2injob2
        run: |
          node -v
          npm -v

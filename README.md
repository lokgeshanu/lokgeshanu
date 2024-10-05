name: hello-world
on: push 
jobs:
  my-jobs:
     runs-on: ubuntu-latest
    steps:
       - name: my-step
         run: echo "hello world"
       - name: exam
         run: echo "writing on eaxam"
       - name: assignment
         run: echo " writing on assignment"

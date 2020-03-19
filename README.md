# Day_Night_Classifier
- Upload this jupyter file to your google colab.
- To train with your dataset call train(path) function
  - path is where your train files in
  - path folder structure should be like this:\
    path \
&nbsp;&nbsp;&nbsp;|-> day \
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|->filename.jpg \
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;... \
&nbsp;&nbsp;&nbsp;|-> night \
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-> filename.jpg \
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;...
- To test with your dataset call test(path) function
  - path is where your test files in
  - path folder structure should be like this:\
    path \
&nbsp;&nbsp;&nbsp;|-> filename.jpg \
&nbsp;&nbsp;&nbsp;...
- To test without train call train(learn=false) and then call test(path)
- After running test(path), results will be in result folder in current directory

- Example Usage: https://colab.research.google.com/drive/1yaNxBbf7pU-Q4mzj-VMOixWbvs4kmbkA

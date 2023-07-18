# Notes on Michelson and using jupyter

https://michelson.baking-bad.org/introduction.html#try-online

docker pull bakingbad/michelson-kernel
docker run --rm -it -p 127.0.0.1:8888:8888 -v $(pwd):/home/jupyter/notebooks bakingbad/michelson-kernel

Open http://127.0.0.1:8888 in your browser.

Note, that the notebooks folder is mounted to your local filesystem by default, so you won't loose any changes made.



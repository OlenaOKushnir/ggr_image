Download config files

`git clone https://github.com/OlenaOKushnir/ggr_image.git && cd ggr_image`

Launch ggr using command:

`docker run -d --name ggr -v $PWD:/etc/grid-router:ro --net host aerokube/ggr:latest-release`
 

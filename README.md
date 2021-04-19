# docker-spark-jupyter
docker images with Jupyter notebook and spark 

## Run 

docker run -d -p 8888:8888 -v "full_path_to_your_folder:/notebooks" sebkaz/docker-spark-jupyter

go to http://localhost:8888

## stop

docker ps 

get id from sebkaz/docker-spark-jupyter

docker stop id

docker rm -f sebkaz/docker-spark-jupyter

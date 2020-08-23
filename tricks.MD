To make changes inside docker and ensure that the changes are reflected we use the following method

* Instead of making a copy of the source code inside the container what we can do is, we can just let the container access the files from our host directly.
* To do that, Docker has an option called `-v` or `--volume` for the run command. Generic syntax for the volume option is as follows:


`
docker run -v <absolute path to host directory>:<absolute path to container working directory> <image id>
`

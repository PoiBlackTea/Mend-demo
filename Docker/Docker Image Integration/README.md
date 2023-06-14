# Docker Scan

The scanning results are displayed in a new Mend project.


## Example:
Scan [elasticsearch:7.1.1 docker container](https://hub.docker.com/layers/library/elasticsearch/7.1.1/images/sha256-1084c64eed7d9318d028361c9aee398afdeb70d1816ce81d590b9450ec542c08?context=explore)

Configuration File Parameter
- docker.scanImages=true
- docker.includes=\<Repository (image name)\> \<Tag\> \<Image ID\>
- docker.excludes=\<Repository (image name)\> \<Tag\> \<Image ID\>

## Ref:

- [Docker Image Integration](https://docs.mend.io/bundle/unified_agent/page/docker_image_integration.html)
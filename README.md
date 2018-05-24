# kerry-door-initiative

## Requirements
- Node 8

## Running Docker
### Host machine prep

Add `127.0.0.1 site.docker` to the host machines host file. Host file locations can be found [here](https://en.wikipedia.org/wiki/Hosts_(file)#Location_in_the_file_system).  

_**NOTE:**_ `site.docker` _is subject to change._

### Clone repo
```bash
git clone https://github.com/jdenoc/kerry-door-initiative.git --branch=develop
cd kerry-door-initiative/
```

### Bring "up" application container(s)
```bash
docker-compose up -d
```

### Tear-down 
```bash
docker-compose down
```

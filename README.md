# hase-nanban
A developer friendly UNVT Dockerfile based on Ubuntu/Intel.  
unvt/nanban was slightly modified so that it run hasekura

# use
```zsh
docker rmi hase-nanban  
git clone https://github.com/ubukawa/hase-nanban  
cd hase-nanban  
docker build -t hase-nanban .  
docker run -it --rm -v ${PWD}:/data hase-nanban  

```


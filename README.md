# Adding-PPAS

#export proxy in terminal using these:
export http_proxy="http://username:password@host:port/"
export https_proxy="https://username:password@host:port/"

#then add ' -E ' between sudo and the  ppa name
example: sudo -E apt-add-repository ppa:git-core/ppa

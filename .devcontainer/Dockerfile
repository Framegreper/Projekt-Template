FROM fedora:latest 
##as dev

# [Optional] Uncomment this section to install additional OS packages.
# update dnf
RUN dnf update -y  

#install packages
RUN dnf install -y \
    curl \
    git \
    gawk \
    unzip \
    python3 \
    python3-pip\
    x3270\
    zsh
    
##    texlive-scheme-full
## RUN useradd -ms $(which bash) developername

## USER developername

# ENV LANG DE.UTF-8

# [Optional] If your pip requirements rarely change, uncomment this section to add them to the image.
# COPY requirements.txt /tmp/pip-tmp/
# RUN pip3 --disable-pip-version-check --no-cache-dir install -r /tmp/pip-tmp/requirements.txt \
#    && rm -rf /tmp/pip-tmp

# [Optional] Uncomment this line to install global node packages.
# RUN su vscode -c "source /usr/local/share/nvm/nvm.sh && npm install -g <your-package-here>" 2>&1
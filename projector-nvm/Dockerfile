FROM projectorimages/projector-idea-u
USER root
RUN apt-get update \
    && apt-get install curl -y \
    && apt-get install git -y

USER projector-user
ENV NVM_DIR "$HOME/.nvm"
COPY ".bashrc" "$HOME/.bashrc"
RUN curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh >> $HOME/install.sh \
    && chmod +x $HOME/install.sh && /bin/sh $HOME/install.sh \
    && rm -rf $HOME/install.sh


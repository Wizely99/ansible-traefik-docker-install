# ansible-traefik-docker-install

Configure traefik as reverse proxy in a remote linux {ubuntu} machine with docker installed using ansible

## Usage 
Add the following public key as an authorized key in your ubuntu machine. 
> In /{{ SSH_HOME_DIR }}/.ssh/authorized_keys

Dispatch this workflow while passing your host IP as an input.

> got to Actions > Configure Traefik > run workflow

Pass your remote IP and watch it run.

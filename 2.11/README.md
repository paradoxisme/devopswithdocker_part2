clone material-applications on app folder :
   git clone https://github.com/docker-hy/material-applications.git
In dockerfile remove clone and build (only install needed)
Add build and execution in ENTRYPOINT
In docker-compose.yml, add volumes for caching modules -> faster building

## GIT (Version Control)

**Git commands**

```bash
git init                      # Initialize a new repository
git add <file>                # Add file(s) to staging area
git commit -m "message"       # Commit changes with a message
git status                    # Check status of the working directory
git log                       # view commit history
git branch                    # List all branch
git checkout -b <brach>       # Create and switch to new branch
git merge <branch>            # Merge changes from another branch
git push -u origin <branch>   # Push changes to the remote repository
git pull origin <branch>      # Pull chnages from the remote repository
git clone <url>               # Clone repository from remote
git config --global user.name "Your Name"
git config --global user.email "youremail@exmaple.com"
```

**Docker commands**

```bash
docker version                # Show the Docker version information
docker info                   # Display system-wide information
docker pull                   # Pull an image from the registry
docker images                 # List all the docker images
docker run <image_name>       # Run a container from the image
docker ps                     # List all running containers
docker ps -a                  # List all the containers running as well as the stopped ones
docker start <container_id>   # Start a stopped container
docker stop <container_id>    # Stop a running container
docker restart <container_id> # Restart a container
docker rm <container_id>      # Remove a container
docker rmi <image_id>         # Remove an image
```

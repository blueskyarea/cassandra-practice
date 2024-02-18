# Use the official Cassandra image as the base image
FROM cassandra:3.11.9

# Install vim
RUN apt-get update && apt-get install -y vim

# Set the default command to run when the container starts
CMD ["cassandra", "-f"]

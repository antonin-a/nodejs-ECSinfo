nodejs-ECSinfo
======================

A basic nodejs webpage to display Flexible Engine ECS information 
## Requirements

* Node 8
* Git

## Common setup

Clone the repo and install the dependencies.

```bash
git clone https://github.com/antonin-a/nodejs-ECSinfo.git
cd nodejs-ECSinfo
```

```bash
npm install
```

## Use Docker
You can also run this app as a Docker container:

Step 1: Clone the repo

```bash
git clone https://github.com/antonin-a/nodejs-ECSinfo.git
```

Step 2: Build the Docker image

```bash
docker build -t ECSinfo .
```

Step 3: Run the Docker container locally:

```bash
docker run -p 3000:3000 -d ECSinfo
```


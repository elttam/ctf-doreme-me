# Overview

**Title:** Doreme Me  
**Category:** Web  
**Flag:** libctf{0673974e-2d1b-4a2f-bd17-56269936af8e}  
**Difficulty:** Trivial  

# Usage

The following will pull the latest 'elttam/ctf-doreme-me' image from DockerHub, run a new container named 'libctfso-doreme-me', and publish the vulnerable service on port 80:

```sh
docker run --rm \
  --publish 80:80 \
  --name libctfso-doreme-me \
  elttam/ctf-doreme-me:latest
```

# Build (Optional)

If you prefer to build the 'elttam/ctf-doreme-me' image yourself you can do so first with:

```sh
docker build ${PWD} \
  --tag elttam/ctf-doreme-me:latest
```


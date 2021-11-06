# JoinLemmy-site

## Requirements

- Docker

## Running

**Clone and update via git:**

```
git clone https://github.com/ncorder/joinlemmy-site.git
git submodule update --init --recursive
git submodule update --recursive --remote

```

**Run with docker:**

```
docker build . -t joinlemmy-site
docker run -p 3000:1234 joinlemmy-site
```

and goto http://localhost:3000


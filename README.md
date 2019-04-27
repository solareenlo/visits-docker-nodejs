# visits-docker-nodejs
DockerでNode.jsとRedisのコンテナを立ち上げて, docker-compseで処理したプログラム.

# Usage
```bash
git clone URL
cd visits-docker-nodejs
docker-compose up -d
# 任意のブラウザでlobalhost:8082を訪れると訪問回数を表示するサイトが表示される
docker-compose down
```

# Reference
- [Docker and Kubernetes: The Complete Guide](https://www.udemy.com/docker-and-kubernetes-the-complete-guide/)

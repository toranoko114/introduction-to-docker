# introduction-to-docker

## 起動手順

```
docker-compose up -d
```

## 停止手順

```
docker-compose down
```

## コンテナのログの確認

```
docker logs <コンテナ ID>
```

※ <コンテナ ID> の箇所には、docker ps で確認した値を入れてください

## MySQL への接続

```
docker exec -it my-db bash
mysql -u root -p
```

## ホストのポートの確認

```
sudo ss -antup
```

## コンテナのポートの確認

```
docker exec -it <コンテナ ID> bash
apt install iproute2
ss -antup
```

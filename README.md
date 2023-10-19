# kubernetes-practice

### Kompose

```bash
cd data-hostpath
mkdir kompose
kompose convert --file docker-compose.yaml --out ./kompose

cd data
mkdir kompose
kompose convert --file docker-compose.yaml --out ./kompose
```

# MovieWebsite
一个十分简易的电影信息网站

*前端部分（v0.9——[dev: 20240223](https://github.com/PeerlessMonster/MovieWebsite-frontend/tree/3c658688d38a33a18f1a4e4206bc366babd111f7)）*  
*后端部分（v0.9——[dev: 20240219](https://github.com/PeerlessMonster/MovieWebsite-backend/tree/5043ecb2f022c9d01fcbf8dbf34f88dc66bbb919)）*



## 试试🤗
1. 克隆包括子模块的整个仓库
```bash
git clone --recurse-submodules https://github.com/PeerlessMonster/MovieWebsite
```

2. 在容器中启动应用的所有服务
```bash
docker-compose -f docker-compose.yml up -d
```

3. 浏览器访问 http://localhost:80 即可



## 大感谢🫡
### 数据
- MovieWebsite_db.sql中，所有电影信息来自[豆瓣](https://www.douban.com/)
- frontend/static/movies下，1_m.webp（中号竖版海报）、1_l.webp（大号横板海报）……  
  所有影片的海报来自[豆瓣](https://www.douban.com/)，此处不提供
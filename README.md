# hugo 博客
public 目录是远端 soul-coder-heap.github.io

## 测试

1. wls

```
IPADDRESS=$(ip addr show eth0 | grep "inet\b" | awk '{print $2}' | cut -d/ -f1)
hugo server -D --bind $IPADDRESS --baseURL=http://$IPADDRESS
```

2. mac

```
hugo server -D
```

3. 归档功能

[归档功能](https://huweim.github.io/post/blog_hugo_%E5%BD%92%E6%A1%A3%E9%A1%B5%E9%9D%A2%E5%88%B6%E4%BD%9C/)

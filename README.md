# ghi-chep---Command-linux
## Lệnh Find
- Thực hiện nén file trong thu mục log
Với file log có phần mở rộng là log
command: `find -type f -mtime +1 -name "*.log" -exec zip -m {}.zip {} \; >/dev/null &`

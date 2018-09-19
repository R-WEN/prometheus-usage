## Configuration
  - prometheus/config/prometheus.yml
    
    #### prometheus監控配置檔案
    
    `scrape_configs` 內容設置要監控的Application
    
  - alertmanager/config/config.yml
    
    prometheus提醒的配置檔案

## Docker
```
#啟動
docker-compose up -d
#停止並刪除
docker-compose down
```
# GAP-1
./victoria-metrics-prod -storageDataPath=/var/lib/victoria-metrics-data -retentionPeriod=2w -httpListenAddr=:8428 -promscrape.config=/path/to/promscrape.config


- -storageDataPath=/var/lib/victoria-metrics-data: Указывает директорию, где будут храниться данные.
- -retentionPeriod=2w: Задает период хранения данных в две недели.
- -httpListenAddr=:8428: Указывает адрес и порт, на котором VictoriaMetrics будет доступен.
- -promscrape.config=/path/to/promscrape.config: Указывает путь к файлу конфигурации для сбора метрик.

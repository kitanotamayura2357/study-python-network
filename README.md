# study-python-network


## 環境構築

#### redisのインストール
```
$ pip install redis
```
Macにインストールする場合
```
$ brew install redis 
```

Linuxの場合はapt-getを使う

#### redisの起動
```
redis-server
```
起動結果
```
(venv) O-12268-MAC:study_python_network takashi.a.imoto$ redis-server
14948:C 04 Jul 2020 15:58:53.041 # oO0OoO0OoO0Oo Redis is starting oO0OoO0OoO0Oo
14948:C 04 Jul 2020 15:58:53.041 # Redis version=6.0.5, bits=64, commit=00000000, modified=0, pid=14948, just started
14948:C 04 Jul 2020 15:58:53.041 # Warning: no config file specified, using the default config. In order to specify a config file use redis-server /path/to/redis.conf
                _._                                                  
           _.-``__ ''-._                                             
      _.-``    `.  `_.  ''-._           Redis 6.0.5 (00000000/0) 64 bit
  .-`` .-```.  ```\/    _.,_ ''-._                                   
 (    '      ,       .-`  | `,    )     Running in standalone mode
 |`-._`-...-` __...-.``-._|'` _.-'|     Port: 6379
 |    `-._   `._    /     _.-'    |     PID: 14948
  `-._    `-._  `-./  _.-'    _.-'                                   
 |`-._`-._    `-.__.-'    _.-'_.-'|                                  
 |    `-._`-._        _.-'_.-'    |           http://redis.io        
  `-._    `-._`-.__.-'_.-'    _.-'                                   
 |`-._`-._    `-.__.-'    _.-'_.-'|                                  
 |    `-._`-._        _.-'_.-'    |                                  
  `-._    `-._`-.__.-'_.-'    _.-'                                   
      `-._    `-.__.-'    _.-'                                       
          `-._        _.-'                                           
              `-.__.-'                                               

14948:M 04 Jul 2020 15:58:53.044 # Server initialized
14948:M 04 Jul 2020 15:58:53.044 * Ready to accept connections
^C14948:signal-handler (1593846001) Received SIGINT scheduling shutdown...
14948:M 04 Jul 2020 16:00:01.886 # User requested shutdown...
14948:M 04 Jul 2020 16:00:01.886 * Saving the final RDB snapshot before exiting.
14948:M 04 Jul 2020 16:00:01.887 * DB saved on disk
14948:M 04 Jul 2020 16:00:01.888 # Redis is now ready to exit, bye bye...

```

#### ZeroMQのインストール
```
$ pip install zmq
```

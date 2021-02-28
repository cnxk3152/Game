# Game
### UE  
UE4.23/Engine/Config/BaseEngine.ini  
[installedderiveddatabackendgraph]  
path="%GAMEDIR%DerivedDataCache"  
修改相应版本文件后，项目的缓存路径会在项目的根目录创建，不会在c盘创建  

### Unity  
增加系统环境变量  
UPM_NPM_CACHE_PATH覆盖npm文件夹路径。例如（macOS）：  
  
UPM_NPM_CACHE_PATH=/dev/ssd/shared/Unity/cache/npm  
  
  
UPM_CACHE_PATH覆盖软件包文件夹路径。例如（macOS）：  
    
UPM_CACHE_PATH=/dev/ssd/shared/Unity/cache/packages  
  
更改这些环境变量中的任何一个后，必须重新启动Unity Editor和Hub才能使它们生效。  

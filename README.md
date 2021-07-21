# slg_server
Hit The Road!!!

--------------------------------READ_ME FIRST!------------------------------------

服务端基本框架 skynet + google protobuf

config  --配置目录，游戏业务相关配置文件 通过python脚本生成相关格式（json,lua,erlang....）的文件
module  --模块位置，分模块，分文件
proto   --生成的proto文件
service --游戏服务相关
lua     --agent,负责交换消息
utils   --公共部分
XiHa    --游戏公共平台相关（便于之后整合成一个平台，出多款游戏）


--------------------------------END!-----------------------------------------------
# slg_server
Hit The Road!!! ^_^ 

--------------------------------READ_ME FIRST!------------------------------------

服务端基本框架 skynet + google protobuf

基本结构：
    config  --配置目录，游戏业务相关配置文件 通过python脚本生成相关格式（json,lua,erlang....）的文件
    module  --模块位置，分模块，分文件
    proto   --生成的proto文件
    service --游戏服务相关
    lua     --agent,负责交换消息
    utils   --公共部分
    XiHa    --游戏公共平台相关（便于之后整合成一个平台，出多款游戏）



XiHa结构相关：
    common  --基础库
    config  --基本配置
    dependencies --依赖库及第三方工具
    game    --逻辑服务相关

第三方工具及库说明：
    lua-protobuf  纯C的protobuf协议实现，和对应的Lua绑定，跨平台 编译看wiki or README.md ^_^
    传送门:https://github.com/starwing/lua-protobuf.git

    pbc  协议缓冲库
    传送门:https://github.com/cloudwu/pbc

    protobuf google protobuf协议
    传送门:https://github.com/protocolbuffers/protobuf.git

    skynet   云大大写的轻量级游戏服务器框架  编译看wiki or README.md ^_^
    传送门:https://github.com/cloudwu/skynet.git
--------------------------------END!-----------------------------------------------
This is for the final project of PHBS_m4_block_chain.

# 2021/07/04

## [preview](https://github.com/lethe-ye/PHBS_BlockChain_proj/blob/main/02%20code/version2/minePreview.htm)

## TODO

### p2pclient连接问题

miner1接收不到miner0的信息

miner0开始mine了之后，broadcast这个msg给miner1，但是miner1显示`create instance error`

### blockChain类型

block chain目前是在blockCache里面，以list的形式存储，要不要改成HashMap？？

把hwk2的关于这一块的code再搬过来


# 2021/07/04

## 孙博

### BlockService

有genesisBlock后不能再create

现在create genesisBlock后也会broadcast

### BlockCache

可以连接多个client address，再application中用逗号分隔

### BlockHandler

可以用/mining让节点连续挖矿（持续20秒）

### 正在加入selfish mining函数





### 存储技术分类
1. RAM：
  SRAM（高速缓存）：高稳定性
  DRAM（内存）：低稳定性，结构类似于矩阵，获取数据时先读取坐标所属的一整行（内部缓冲区），在读出指定的列
    Fast Page Mode 直接从缓冲区读取数据
    Extended Data Out 加快时钟信号的频率
    Double Data-rate Synchronous（DDR）使用两组时钟信号
  DRAM（flash）
2. 总线事务：
  cpu《－》系统总线《－》IO桥《－》存储总线《－》主存
                        《－》IO总线《－》IO设备
3. 机械硬盘：
  扇区、磁道、区、面、盘片
  柱面
4. 局部性：
  时间局部性
  空间局部性
5. 存储器层次结构
  每一层都是下一层的缓存（cache）
6. 高速缓存：
  由S组，每组有E行，每行有有效位、标记为、缓存块组成，实现和主存的映射
  直接映射高速缓存
  组相联高速缓存
7. 存储山：反映了时间局部性与空间局部性对程序性能的影响

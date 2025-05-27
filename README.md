两个模型的核心差异体现在什么机制上？ A. 字符编码方式不同 B. 是否考虑国家信息作为生成条件 C. RNN单元类型不同（GRU/LSTM） D. 损失函数计算方式不同 答案：B
在条件生成模型（Model2_Conditioned_Surname_Generation）中，国家信息通过什么方式影响生成过程？ A. 作为额外的输入特征拼接 B. 作为 GRU 的初始隐藏状态 C. 作为注意力机制的key D. 作为输出层的偏置项 答案：B
文件2中新增的nation_emb层的主要作用是： self.nation_emb = nn.Embedding（嵌入num_nationalities、rnn_hidden_size） A. 将字符索引映射为稠密向量 B. 将国家标签转换为隐藏状态初始化向量 C. 生成姓氏的长度控制参数 D. 计算交叉熵损失的辅助参数 答案：B 对比两个文件的sample_from_model函数，文件2新增了哪个关键参数？ A. 温度 B. 国籍 C. 设备 D. max_length [长度] 答案：B
![c07f7cef17592d4570ea41ea21af3dc](https://github.com/user-attachments/assets/281930ee-769a-422d-921a-67577f77bb75)
![0cce674033214ea8735909c8ee893c1](https://github.com/user-attachments/assets/417b4a0f-615f-4555-9bc5-c6fecb0bb403)
![4225a1d4f98ae08aaaec513155c10a5](https://github.com/user-attachments/assets/503ee79e-c53f-419b-b567-b7b9ff52c976)

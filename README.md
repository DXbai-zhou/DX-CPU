# DX-CPU
这是由DXbai_zhou自主研发的CPU。名字叫做DX-CPU。自创架构。指令集可以看文档([指令集]Instruction Set.txt)。
This is a CPU named DX-CPU invented by DXbai_zhou.It's self-created architecture.You can know the Instruction Set from the document([指令集]Instruction Set.txt).

DX0203更新内容:
    新增指令集:
        encd                           0100000
        muli                           0100001
        mov                            0100010
    encd和decd可以实现编码和解码。
    用mov可以让rs1直接接入BUS总线，实现寄存器值传输。

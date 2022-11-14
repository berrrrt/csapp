# gcc -E -o hello.i helloworld.c <!-- 预处理器：Generate the cpp output>

# gcc -S -o hello.s helloworld.c <!-- 编译器：Generate the ccl output>

# gcc -c -o hello.o helloworld.c <!-- 汇编器：Generate the as output>

# gcc -o hello helloworld.c <!-- 链接器: Generate the final program>

# gcc -og -S mstore.c <!--以最小优化方式生成>

# objdump -d mstor.o <!--反汇编>

# Imm(Rb,Ri,s) = Imm + R[Rb] + R[Ri] 乘以 s <!-- 寻址, Rb: Base register, Ri: Index register, s:scale factor, must be 1,2,4 or 8>

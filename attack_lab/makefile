# -q 是不向 CMU 的服务器提交数据
# test1~3 使用 ctarget
# test4~5 使用 rtarget

.PHONT:clean
clean:
	rm -rf bin/*

.PHONY: test1
test1:
	./hex2raw < ans/ans1.txt > bin/ans1.txt 
	./ctarget -q < bin/ans1.txt 

.PHONY: test2
test2:
	./hex2raw < ans/ans2.txt > bin/ans2.txt 
	./ctarget -q < bin/ans2.txt 

.PHONY: test3
test3:
	./hex2raw < ans/ans3.txt > bin/ans3.txt 
	./ctarget -q < bin/ans3.txt 

.PHONY: test4
test4:
	./hex2raw < ans/ans4.txt > bin/ans4.txt 
	./rtarget -q < bin/ans4.txt 

.PHONY: test5
test5:
	./hex2raw < ans/ans5.txt > bin/ans5.txt 
	./rtarget -q < bin/ans5.txt 

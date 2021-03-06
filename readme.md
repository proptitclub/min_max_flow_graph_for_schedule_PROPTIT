# Description

sử dụng thuật toán [lát cắt cực tiểu trên đồ thị có hướng ](https://en.wikipedia.org/wiki/Max-flow_min-cut_theorem) để xây dựng lịch học dựa trên lịch bận của thành viên.

Một khóa có rất đông sinh viên, các sinh viên được phân vào n nhóm, mỗi nhóm học 2 buổi trong tuần.

Với các yêu cầu : 

1. trong 1 nhóm phải có >=8 em.
2. 1 nhóm phải học cách nhau ít nhất là 1 ngày....
3. lịch học phải phù hợp lịch bận của giảng viên.
4. ....

# SETUP

1. python3 -m venv env

2. on windows - run cmd :env\Scripts\activate.bat

3. on Ubuntu - run  cmd :source env/bin/activate

4. pip3 install requirements.txt

5. python3 dev.py file_l.csv file_index.csv limit_selected file_ans

file_l.csv la file csv extract tu lich ban 

file_index.csv la file name extract tu lich ban

limit_selected : recommend <= 10^5, hoac <=10^4 va chay nhieu lan de tim ket qua thoa man rui dung.

multi_gpu: neu may co gpu thi se tang toc do x5 nguoc lai khong nen dung multi_gpu

# examples 

## file lich ban 

![](./statics/lich.png)

---

## file index 

![](./statics/index.png)

---

## file ket qua thuat toan voi limit = 100, run 2 lan \sum_time = 2s.

![](./statics/kq.png)
## Task 0
![Task_0](Task_0.png)

## Task 1
terminal: touch 'file_name.txt'  
	   ls ./ | grep zoola  
![Task_1_1](Task_1_1.png)
![Task_1_2](Task_1_2.png)

## Task 2
Code is in ./mcd.sh file.  
![Task_2_1](Task_2_1.png)
![Task_2_2](Task_2_2.png)
![Task_2_3](Task_2_3.png)

The directory is changed in the child process of script, not in the terminal process from which the script is called. After the child process dies, you are back in the terminal which is left where it was.

## Task 3
Code is in ./day.sh file.  
![Task_3](Task_3.png)

## Task 4
terminal: jq '.messages[].text' result.json  
![Task_4_1](Task_4_1.png)  
result:  
![Task_4_2](Task_4_2.png)

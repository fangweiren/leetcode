题意  
这道题给我们了一个Employee表，里面有员工的薪水信息和其经理的信息，经理也属于员工，其经理Id为空，让我们找出薪水比其经理高的员工，那么就是一个很简单的比较问题了，我们可以生成两个实例对象进行内交通过ManagerId和Id，然后限制条件是一个Salary大于另一个即可。
# acccode18
sql
'''
     EMPNO ENAME      JOB              MGR HIREDATE         SAL       COMM      
---------- ---------- --------- ---------- --------- ---------- ----------      
    DEPTNO                                                                      
----------                                                                      
      7788 SCOTT      ANALYST         7566 19-APR-87       3000                 
        20                                                                      
                                                                                
      7902 FORD       ANALYST         7566 03-DEC-81       3000                 
        20'''
        select emp.*
         from emp
        where job='ANALYST';

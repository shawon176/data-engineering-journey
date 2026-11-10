# Week 02 - Linux Commands Practice

1. grep "ERROR" app.log

2. grep -c "ERROR" app.log

3. grep -i "error" app.log

4. grep -v "INFO" app.log

5. grep -n "ERROR" app.log

6. grep "^2026-10-17" app.log

7. grep -r "TODO" .

8. cut -c1-10

9. cut -d',' -f3

10. cut -d'|' -f2

11. sort

12. sort -rn

13. uniq -c

14. tr -d ' '

15. grep "| ERROR |" app.log | cut -c1-10 | sort | uniq -c | sort -rn

16. grep "| ERROR |" app.log > errors.log

17. echo "আরেকটা লাইন" >> errors.log

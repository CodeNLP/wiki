# NLP wiki

## TIMEX

### TIMEX normalization for Polish

**In the command line**

```bash
wget https://github.com/CLARIN-PL/Liner2/releases/download/v2.7/g419-liner2-cli-2.7.jar
```

```bash
echo "t3_date:1 listopad 2021" | java -jar g419-liner2-cli-2.7.jar timex-norm
```

Output:
```json
{"input":"t3_date:1 listopad 2021","bases":"1 listopad 2021","type":"t3_date","lval":"2021-11-01"}
```

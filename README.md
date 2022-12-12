# NLP wiki

## TIMEX

### TIMEX normalization for Polish

**In the command line**

```bash
wget https://github.com/CLARIN-PL/Liner2/releases/download/v2.7/g419-liner2-cli-2.7.jar
```

**t3_date**

```bash
echo "t3_date:1 listopad 2021" | java -jar g419-liner2-cli-2.7.jar timex-norm
```

Output:
```json
{"input":"t3_date:1 listopad 2021","bases":"1 listopad 2021","type":"t3_date","lval":"2021-11-01"}
```

**t3_time**

```bash
echo "t3_time:12:05" | java -jar g419-liner2-cli-2.7.jar timex-norm
```

Output:
```json
{"input":"t3_time:12:05","bases":"12:05","type":"t3_time","lval":"xxxx-xx-xxt12:05"}
```

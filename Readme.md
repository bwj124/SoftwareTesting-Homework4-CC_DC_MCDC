Given the program listed below, please design three test sets according to the following coverage criterion :

1.  Condition Coverage

2. Decision Coverage

3.  Modified C/D Coverage

```java
public double Calc(int a, int b,double c) {
    double d = 0;
    if (a>0 && b>0) {c = c/a;}
    if (a>1 || c>1) {c = c +1;}
    d = b + c;
    return d;
}
```


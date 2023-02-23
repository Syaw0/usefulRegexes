# USEFUL REGEXes

#### Validate Email Addresses:

```regex

/(^[^\W])([\w]+|([\.-]?\w+)*)@[\w]+\.[\w]{2,4}/
```

#### Validate Password With :

**(At Least One UpperCase Character ,One Lower Case Character , One Digit ) And 8 Or More Character**

```regex

/(?=.*?[a-z])(?=.*?[A-Z])(?=.*?\d).{8,}/
```




#### Select Duplication Characters :


```regex

/(.)(?=.*\1)/
```


#### Select If Whole String is Uppercase :


```regex

/^[A-Z\s]+$/
```

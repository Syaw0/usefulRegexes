# USEFUL REGEXes



#### Select Spaces:

```regex

/\s/
```


#### Select Non Spaces:

```regex

/\S/
```


#### Select Digits:

```regex

/\d/
```


#### Select Non Digits:

```regex

/\D/
```

#### Select Letters[a-zA-z] and Digits[0-9]:

```regex

/\w/
```


#### Select Everything except Letters[a-zA-z] and Digits[0-9]:

```regex

/\W/
```



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

Some commands:

```
# fails initially, because Foo.java has no header
mvn license:check-file-header

# add a header - note the whitespace
mvn license:update-file-header

# compile, including formatting
mvn compile

# check the header again, fails because header is not identical/has been reformatted
mvn license:check-file-header
```

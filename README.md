# spring-security-oauth2-client-example

## Modules

### minimal-sample

TODO


### custom-userservice-sample

Same as minimal-sample, but it contains a custom OAuth2 UserService.


## Note

For Google, it's actually possible to just use the two following properties:

```properties
spring.security.oauth2.client.registration.google.client-id=
spring.security.oauth2.client.registration.google.client-secret=
```

But for the sake of the example, I'll be inserting all properties.

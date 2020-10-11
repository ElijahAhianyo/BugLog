### Error:
 ERROR: Version in "./docker-compose.yml" is unsupported. You might be seeing this error because you're using the wrong Compose file ver
sion. Either specify a supported version (e.g "2.2" or "3.3") and place your service definitions under the `services` key, or omit the `version` key and place your service definitions at the root of the file to use version 1.
For more on the Compose file format versions, see https://docs.docker.com/compose/compose-file/

### Produced:
Docker version was outdated
```Docker version 19.03.1, build 74b1e89
docker-compose version 1.21.0, build unknown```


### Fixed:
 updated docker version and docker-compose version to 
 ```Docker version 19.03.6, build 369ce74a3c
    docker-compose version 1.25.3, build d4d1b42b
  ```
by running this command:

```

```




                                --------------------
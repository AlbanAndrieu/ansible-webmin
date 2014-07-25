# ansible-webmin

A role for installing webmin.


## Actions

- Ensures that webmin is installed (using `apt`)


## Usage:
```
  # This playbook can be run using vagrant (on virtual box). 
  - name: Install webmin
    hosts: webmin
    user: root
  #  connection: local
    
    roles:
      - webmin      
```

## License

MIT

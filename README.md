# ansible-webmin

A role for creating webmin tasks.


## Actions

- Ensures that webmin is installed (using `apt`)


## Usage:
```
  # This playbook can be run using vagrant (on virtual box). 
  - name: apply webmin to all nodes
    hosts: webmin
    user: root
  #  connection: local
    
    roles:
      - webmin      
```

## License

MIT

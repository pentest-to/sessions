# Pentest-TO Sessions
Slides, notes, labs, and other materials for each of Pentest-TO's sessions.

Slides largely original work of @msarfati

## Presentations

Presentations are currently using the presentation tool [showoff](https://puppetlabs.github.io/showoff/).

### Viewing Presentations

Static versions of presentations are always available online at [tomeshnet.github.io/tomesh.101/](https://tomeshnet.github.io/tomesh.101/)

### Running Presentations

If you would like to run presentations locally or make changes you'll have to do the following:

1. Clone this repository to your computer.

2. Install [showoff](https://github.com/puppetlabs/showoff/), showoff is written in ruby and comes as a packaged gem

    ```
    $ gem install showoff
    ```

2. Run showoff from the repository `presentations/<presentation-name> ` directory

    ```
    $ showoff serve
    ```

3. To view, in your preferred browser navigate to:

    ```
    http://0.0.0.0:9090
    ```

### Serving it on LAN

1. Make sure your port is allowed incoming connections (ufw, iptables)

2. Run showoff with your IP address you discovered with `ifconfig` or `ip addr`
	```
	showoff serve -h 192.168.1.100
	```

### Special thanks


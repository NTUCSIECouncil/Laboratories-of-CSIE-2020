# Laboratories-of-CSIE-2020
專題訪談網站 (June, 2020)

## Usage
```
$ git clone https://github.com/NTUCSIECouncil/Laboratories-of-CSIE-2020.git
$ cd Laboratories-of-CSIE-2020
$ git submodule add -f https://github.com/marketempower/axiom.git themes/axiom
```

### Run the server
```
$ hugo server -D
```

### Bulid the website
```
$ hugo -d <directory tot place the output html files>
```

Example for deployment on apache server
```
$ hugo -d /var/www/html/
```

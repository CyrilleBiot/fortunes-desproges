# Fortunes Desproges

## Install 

Just download the debian package and install it.

```
wget https://github.com/CyrilleBiot/fortunes-desproges/raw/master/fortunes-desproges_0.0.1_all.deb
su -
dpkg -i fortunes-desproges_0.0.1_all.deb
apt-get install -f
```


## Usage

### In a term
```fortune desproges```

### Via .bashrc
Add in your ~/.bashrc and add a line like this : fortune  desproges


## More
You want to create your own fortunes file. Don't forget this command to create your .dat file

```
strfile -c % quotes quotes.dat

```

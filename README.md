# dokr

### create a package:

1. Create a folder with your `package_name`.
2. Create a __init__.py file in  `package_name`.
3. Create your desired python script in `package_name`.
4. Open terminal
5. Go to your package location. -> cd ..
6. run

```
python
import dokr.my_script`
dokr.my_script.commands()
```

similarly you can create a subpackage

7. repeat step 1,2,3 inside `package_name`.

#### to create a new package 

```
 python setup.py sdist
```

##### to Upload

```
 python -m twine upload dist/*
```

# Download the file and executable


For Ubunutu:

```
cd /usr/bin/
```

For Mac:

```
cd /usr/local/bin
```

then download this command

```
curl -o ./dokr https://raw.githubusercontent.com/javatechy/docker-tools/master/jenkins/dokr.py
chmod +x dokr
```


run :

```
dokr help
```
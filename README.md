# book-mastering-opencv4

## Init steps
```
$ virtualenv venv
$ source venv/bin/activate
$ pip3 install -r requirements.txt 
$ mkdir build 
$ conan install -if build .
```

## Development workflow
```
$ cmake -Bbuild
$ cmake --build build
```


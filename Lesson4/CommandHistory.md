```console
root@vladim-VB:~$ mkdir devopsrider
```
```console
root@vladim-VB:~$ cd devopsrider
```
```console
root@vladim-VB:~$ nano Test.java
```
```console
root@vladim-VB:~$ javac Test.java
```
```console
root@vladim-VB:~$ nano manifest.txt
```
```console
root@vladim-VB:~$ jar cvfm Test.jar manifest.txt Test.class
```
```console
root@vladim-VB:~$ nano Dockerfile
```
```console
root@vladim-VB:~$ 
docker build -f Dockerfile -t test-java-image .
```
```console
root@vladim-VB:~$ docker run test-java-image
```
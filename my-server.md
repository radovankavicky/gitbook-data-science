# My Server

```bash
218.250.221.14

ssh -f terry@192.168.1.110 -L 8888:localhost:8888 -N
ssh terry@192.168.1.110
jupyter notebook --no-browser --port=8888



ssh -N -f -L localhost:8888:localhost:8888 terry@113.254.109.120 
sshfs terry@113.254.109.120: server

rsync -av ~ terry@192.168.1.80::NetBackup/linux/
```

[The $1700 great Deep Learning box: Assembly, setup and benchmarks](https://blog.slavv.com/the-1700-great-deep-learning-box-assembly-setup-and-benchmarks-148c5ebe6415)

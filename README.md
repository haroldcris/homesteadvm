# homesteadvm


clone the repo by running.

Run the following Code:
```
    git clone https://github.com/haroldcris/homesteadvm.git [destinationFolder]

    cd [destinationfolder]

    cd server-vm

    vagrant up
```


> By default, VM box name is _homestead-vm_. You can change to virtual box name by modify the file _server-vm\homestead.yaml_ __


```
    name: homestead-vm    <-- change this to the name that you want to avoild collision in case you are running multiple vm
    hostname: homestead-vm

```

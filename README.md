## odroid-notes 

---  

<https://github.com/alexellis/docker-arm/tree/master/images/armhf>  
<https://hub.docker.com/u/arm32v7/>  
<https://hub.docker.com/r/hypriot/rpi-busybox-httpd/>  
<https://larry-price.com/blog/2015/01/18/managing-a-go-environment-in-ubuntu>  
<https://blog.alexellis.io/golang-json-api-client/>  
<https://github.com/dotnet/core-setup>  
<https://github.com/dotnet/core/blob/master/Documentation/prereqs.md>  
<https://github.com/dotnet/core/blob/master/samples/RaspberryPiInstructions.md>  
<https://jeremylindsayni.wordpress.com/2017/03/20/how-to-create-deploy-and-run-a-net-core-2-0-app-on-a-raspberry-pi-3-arm-processor/>  
<https://stackoverflow.com/questions/5343068/is-there-a-way-to-skip-password-typing-when-using-https-on-github>  
<https://medium.com/imont/self-updating-iot-apps-on-the-raspberry-pi-using-docker-a0b223fd4eeb>  
<https://github.com/v2tec/watchtower>  
<https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-ubuntu-16-04>  
<https://www.digitalocean.com/community/tutorials/how-to-write-your-first-python-3-program>
<http://ubuntuhandbook.org/index.php/2017/07/install-python-3-6-1-in-ubuntu-16-04-lts/>
<https://dzone.com/articles/arm-snippets-for-vs-code>  

---  

go `build` task: build package on current opened file path
```
{
"version": "0.1.0",
"isShellCommand": true,
"showOutput": "always",
"command": "go",
"echoCommand": true ,
"options": {
    "cwd": "${fileDirname}"
},
"tasks": [
    {
        "taskName": "build",
        "args": [
            "build",
            "-x"
        ],
        "isBuildCommand": true,
        "suppressTaskName": true
    }
]
}

```



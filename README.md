# dev-note
一些有用的笔记
# VSCode
1. 如何调试node 程序
```json
       {
            "type": "node",
            "request": "launch",
            "name": "Backen",
            "runtimeExecutable": "nodemon",
            "args": [
                "${workspaceFolder}/bin/www"
            ],
            "restart": true,
            "protocol": "inspector", 
            "sourceMaps": true,
            "console": "integratedTerminal",
            "internalConsoleOptions": "neverOpen",
            "runtimeArgs": [
                "--ignore",
                "www",
            ]
        }
```

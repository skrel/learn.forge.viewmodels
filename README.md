# edu.learn.forge.viewmodels

Added 5 buttons "Build of Material", "Start", "Pause", "Complete", "Delivered" for tracking purposes.

![assmbly2](https://user-images.githubusercontent.com/43278778/50455020-57992f00-0919-11e9-8250-eab80435522f.jpg)

# Description

Originaly this sample is a part of the [Learn Forge](http://learnforge.autodesk.io) tutorials.
The `master` branch contains the client-side UI: `html`, `js` and `css` files. To download the project for each language, please use:

- [Nodejs](//github.com/Autodesk-Forge/learn.forge.viewmodels/tree/nodejs)
- [.NET](//github.com/Autodesk-Forge/learn.forge.viewmodels/tree/net)
- [Go](//github.com/Autodesk-Forge/learn.forge.viewmodels/tree/go)
- [PHP](//github.com/Autodesk-Forge/learn.forge.viewmodels/tree/php)
- [Java](//github.com/Autodesk-Forge/learn.forge.viewmodels/tree/java)

# Modifications index.html

    <!-- Button Style -->
    <style>
        .header {
            padding: 20px;
            background: #1abc9c;
        }
        .btn {
            border: none;
            color: white;
            padding: 2px 22px;
            font-size: 16px;
            cursor: pointer;
            width: 200px;
        }
        .green {
            background-color: #4CAF50;
        }
            .green:hover {
                background-color: #46a049;
            }
        .blue {
            background-color: #2196F3;
        }
            .blue:hover {
                background: #0b7dda;
            }
        .orange {
            background-color: #ff9800;
        }
            .orange:hover {
                background: #e68a00;
            }
        .grey {
            background-color: #d9d9d9;
        }
        .grey:hover {
            background: white;
        }
        .red {
            background-color: #ff0066;
        }
            .red:hover {
                background: #e68a00;
            }
        body {
            background-color: black;
        }
    </style>
    
    AND
    
        <!-- New buttons -->>
    <center>
        <button class="btn grey" onclick="getElementById('demo1').innerHTML=Date()">Build Of Material</button>
        <button class="btn green" onclick="getElementById('demo1').innerHTML=Date()">Start</button>
        <button class="btn blue" onclick="getElementById('demo2').innerHTML=Date()">Pause</button>
        <button class="btn orange" onclick="getElementById('demo3').innerHTML=Date()">Complete</button>
        <button class="btn red" onclick="getElementById('demo1').innerHTML=Date()">Delivered</button>
     </center>

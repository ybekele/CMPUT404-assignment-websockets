CMPUT404-assignment-websockets
==============================

CMPUT404-assignment-websockets

See requirements.org (plain-text) for a description of the project.

Make a shared state Websockets drawing program

Prereqs
=======
Create a virtual environment and install the required dependencies.

```bash
virtualenv venv --python=python3
source venv/bin/activate
pip install -r requirements.txt
```

Resources
========================
I used Chat.py by Abram Hindle as a reference and used lines 42-57 specifically as well as the read_ws and subscribe_socket function format. https://github.com/abramhindle/WebSocketsExamples/blob/master/chat.py 

I used my own function in CMPUT404-Assignment 4 for the update function. Did not end up needing to use this however, I had tried implementing it and left it in the code therefore I am making a note of it. https://github.com/ybekele/CMPUT404-assignment-ajax

https://docs.python.org/2/library/json.html for more information on json.dumps 
https://www.w3schools.com/python/python_json.asp for more information on json.dumps

I used the class notes by Abram Hindle to better familiarize myself with Websockets.

Contributors / Licensing
========================

Generally everything is LICENSE'D under the Apache 2 license by Abram Hindle. Additions made by Yonael Bekele are also LICENSE'D under the Apache 2 license. 

freetests.py is LICENSE'D under a BSD-like license:

From ws4py

Copyright (c) 2011-2014, Sylvain Hellegouarch, Abram Hindle
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

 * Redistributions of source code must retain the above copyright notice,
   this list of conditions and the following disclaimer.
 * Redistributions in binary form must reproduce the above copyright
   notice, this list of conditions and the following disclaimer in the
   documentation and/or other materials provided with the distribution.
 * Neither the name of ws4py nor the names of its contributors may be used
   to endorse or promote products derived from this software without
   specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.

Contributors
============

* Mark Galloway
* Abram Hindle
* Cole Mackenzie

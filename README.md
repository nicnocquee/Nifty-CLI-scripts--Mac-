## What is?

Just some scripts to ease my life.

## List

1.  cutvideo

    Cut/trim video. Requirement: `ffmpeg`.

2.  togglehiddenfiles

    Show or hide hidden files in Mac OS X. Works on Lion.

3.  appendprefixtoeachline

    Append string to the beginning of each line in a file.
    
4.  rename

    Make a copy of file(s) with a new name. 
    
        rename -n cool image.jpg
    
    will make a copy of image.jpg under the name cool.jpg.
    
        rename -p cool image.jpg
        
    will make a copy image.jpg under the name coolimage.jpg
    
        rename -s cool image.jpg
            
    will make a copy image.jpg under the name imagecool.jpg
    
        rename -p very -s photo -n cool image.jpg
        
    will make a copy image.jpg under the name verycoolphoto.jpg
    
        rename -p very -s photo -n cool *.jpg
        
    will make copies of jpg files in the directory under the name verycoolphoto-#.jpg where `#` starts from `1`
    
        rename -f -n cool image.jpg
    
    will rename image.jpg to cool.jpg.


## Copyright and License

Copyright (c) 2011, Nico Prananta
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

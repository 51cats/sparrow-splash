This is a simple, Javascript, animated splash-screen experiment with clickable, bouncy parts.

I don't know jQuery, and I don't know why this animation doesn't work quite right on Chrome web browsers, yet it will work right on other browsers such a Firefox.

KNOWN CHROME ISSUES:

1. Welcome sign is not clickable (Macintoch Chrome, Windows Chrome)

2. Burn animation slides to incorrect position (Macintoch Chrome, Windows Chrome)

3. Distance from top incorrect after resize (Windows Chrome)

NOTE: The pollyfill for compatRequestAnimationFrame is courtesy of http://gist.github.com/paulirish/1579671 (MIT License)

NOTE: The spring physics-engine is courtesy of http://facebook.github.io/rebound/ (BSD License, See Below)

BSD License For Rebound software

Copyright (c) 2013, Facebook, Inc. All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

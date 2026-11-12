# Third-party notices

`trong_mcb.html` embeds, unmodified and minified, the browser build of **PeerJS 1.5.4**
(lines 177–185 of the file). That build bundles the packages listed below.
Each component remains under its own license; all of them are permissive and
compatible with the MIT License used by TRONG_MCB.

| Component | Role in TRONG_MCB | Copyright | License |
|---|---|---|---|
| [PeerJS](https://github.com/peers/peerjs) 1.5.4 | WebRTC peer-to-peer data channels | © 2015 Michelle Bu and Eric Zhang | MIT |
| [webrtc-adapter](https://github.com/webrtcHacks/adapter) | Cross-browser WebRTC shim (bundled by PeerJS) | © 2014 The WebRTC project authors | BSD-3-Clause |
| [sdp](https://github.com/fippo/sdp) | SDP parsing helpers (dependency of webrtc-adapter) | © 2017 Philipp Hancke | MIT |
| [eventemitter3](https://github.com/primus/eventemitter3) | Event emitter (bundled by PeerJS) | © 2014 Arnout Kazemier | MIT |
| [peerjs-js-binarypack](https://github.com/peers/js-binarypack) | Binary serialisation (bundled by PeerJS) | © 2012 Eric Zhang | MIT |

No fonts, images, sounds or other media from third parties are included.
Text uses the operating system's own fonts; sounds are synthesised at run time
with the Web Audio API; flags are drawn as inline SVG.

---

## MIT License (PeerJS, sdp, eventemitter3, peerjs-js-binarypack)

```
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

## BSD 3-Clause License (webrtc-adapter)

```
Copyright (c) 2014, The WebRTC project authors. All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are
met:

  * Redistributions of source code must retain the above copyright
    notice, this list of conditions and the following disclaimer.

  * Redistributions in binary form must reproduce the above copyright
    notice, this list of conditions and the following disclaimer in
    the documentation and/or other materials provided with the
    distribution.

  * Neither the name of Google nor the names of its contributors may
    be used to endorse or promote products derived from this software
    without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
"AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT
HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT
LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```

## Third-party services (not software included in this repository)

Online play contacts these services at run time. They are operated by third
parties, are not part of this project and are governed by their operators' terms:

| Service | Operator | Used for |
|---|---|---|
| `0.peerjs.com` | PeerJS project (free public PeerServer) | Signalling: exchanging connection offers |
| `stun.l.google.com:19302` | Google | STUN: discovering each device's public address |
| `eu-0.turn.peerjs.com`, `us-0.turn.peerjs.com` | PeerJS project | TURN: relaying traffic when a direct link fails |
| `t.me/share/url` | Telegram | Optional fallback for sharing a game code |

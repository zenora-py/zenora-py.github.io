# Zenora.py

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  


![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/ahnaf-zamil/zenora?include_prereleases)


A modern Discord REST API wrapper that allows you to access the data without running a bot.

## Installation

Use Git to clone Zenora's source code

```bash
git clone https://github.com/ahnaf-zamil/zenora
```

Or

Install from PyPi

```bash
python -m pip install zenora
```

## Usage

```python

import zenora

api = zenora.RESTAPI("Token", "Bot")

channel = api.get_text_channel(745224645057183824)

print(channel.name)
```

## Documentation

Check out the documentation at https://zenora-py.github.io

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/) License

Copyright (c) 2020 K.M Ahnaf Zamil

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is

furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

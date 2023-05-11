# assh
Dynamic ssh panes in iTerm2 based on Ansible group patterns

Installation

* `pip install -r requirements.txt`
* `chmod +x assh; sudo cp assh /usr/local/bin`

Setup iTerm2:

* iTerm2 Preferences > General > 'Magic' section > check 'Enable Python API'
* iTerm2 Profiles > Create new profile named 'assh' > Set start commmand to `/bin/bash`

Usage - `assh <ansible_group>`


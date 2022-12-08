# npm using https for git
git config --global url."https://github.com/".insteadOf git@github.com:
git config --global url."https://".insteadOf git://

# npm using git for https
git config --global url."git@github.com:".insteadOf https://github.com/
git config --global url."git://".insteadOf https://

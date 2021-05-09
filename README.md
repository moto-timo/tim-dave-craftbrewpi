# Tim & Daves Killer Electric Brewery

A new exploration into the world of single vessle electric homebrew.

## Getting started
As per instructions on [Craft Brew Pi](https://craftbeerpi.gitbook.io/craftbeerpi4/):

    git clone https://github.com/dcobbley/tim-dave-craftbrewpi.git
    cd tim-dave-craftbrewpi/
    python3 -m venv venv
    source venv/bin/activate
    pip3 install -r requirements.txt
    sudo pip3 install cbpi4-pt100x # Lame -_-
    sudo cbpi start # Need to troubleshoot why usermod -a -G kmem <user> didn't work

You can then access craft beer pi via [http://localhost:8000/](http://localhost:8000/)


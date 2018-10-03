# ffwsite
Buildout project for website of Freiwillige Feuerwehr Waldkirch

virtualenv venv
cd venv
./bin/pip install zc.buildout
cd ../
git clone https://github.com/thomasgraf/ffwsite
cd ffwsite
../venv/bin/buildout -c buildout.cfg

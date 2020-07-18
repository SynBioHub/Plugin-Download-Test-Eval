# Plugin-Download-Test-Eval
A very small test plugin to test the download interface is working for SynBioHub. Could be the basis for python based download plugins. Returns the evaluate manifest too.

# Install
## Using docker
Run `docker run --publish 8092:5000 --detach --name python-test-plug synbiohub/plugin-download-test-eval:snapshot`
Check it is up using localhost:8092.

## Using Python
Run `pip install -r requirements.txt` to install the requirements. Then run `FLASK_APP=app python -m flask run`. A flask module will run at localhost:5000/.

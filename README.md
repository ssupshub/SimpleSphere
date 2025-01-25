## Setup for local development

* Fork repo

  [Fork](https://github.com/Chennaipy/website/fork) the repository to your account
so that you have your copy of the website.

* Clone repo

        $ git clone --recursive git@github.com:<your-username>/website.git chennaipy-website

  This will clone the repository on to your system and clone the submodules inside
it as well recursively. Additionally, the folder to which it will be cloned to
is called `chennaipy-website`.

* Set up a virtual env in that folder and activate it

        $ cd <repo>
        $ virtualenv env
        $ source env/bin/activate

* Install the requirements using `pip` from inside the virtual environment

        (env)$ pip install -r requirements.txt

* Start the server

        make devserver

* Visit local site

  Open up your web browser and point it to [http://localhost:8000](http://localhost:8000) to see the site
running locally. Yay!

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md)

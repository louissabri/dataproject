# dataproject

try this:

1. You'll need Microsoft Visual C++. Get it with "Microsoft C++ Build Tools": https://visualstudio.microsoft.com/visual-cpp-build-tools/ Install that first
1. install an environment, paste this into your terminal:

    ```
    python -m venv --copies lou-env
    lou-env\Scripts\activate.bat
    echo "🚪"
    python -m pip install --upgrade pip
    python -m pip install pip-tools
    pip-compile requirements.in
    echo "🚀"
    pip install -r requirements.txt
    git init
    echo "🍟🍟🍟"
    #
    ```
Then you should be able to use the `sntwitter.py` file.

Both of those files are from here: https://www.freecodecamp.org/news/python-web-scraping-tutorial/

The tweepy one need an API key, so get on that, and try it
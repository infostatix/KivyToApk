# KivyToApk
Steps in Google Colab:  You can directly use my Colab notebook where you just need to run all the cells, that’s it!

a) !pip install buildozer

b) !pip install cython==0.29.19

c) !sudo apt-get install -y \
    python3-pip \
    build-essential \
    git \
    python3 \
    python3-dev \
    ffmpeg \
    libsdl2-dev \
    libsdl2-image-dev \
    libsdl2-mixer-dev \
    libsdl2-ttf-dev \
    libportmidi-dev \
    libswscale-dev \
    libavformat-dev \
    libavcodec-dev \
    zlib1g-dev

d) !sudo apt-get install -y \
    libgstreamer1.0 \
    gstreamer1.0-plugins-base \
    gstreamer1.0-plugins-good

e) !sudo apt-get install build-essential libsqlite3-dev sqlite3 bzip2 libbz2-dev zlib1g-dev libssl-dev openssl libgdbm-dev libgdbm-compat-dev liblzma-dev libreadline-dev libncursesw5-dev libffi-dev uuid-dev libffi6

f) !sudo apt-get install libffi-dev

g) !buildozer init

h) !buildozer -v android debug

i) !buildozer android clean

Before running the cells, make sure to upload your app code to the colab notebook and after running the bulldozer init command, make sure to edit the specs file generated and nothing else!
This is the easiest and most convenient way to build apps without the need for an actual system!


# A Demo Code: PingPong is attached Use it for application

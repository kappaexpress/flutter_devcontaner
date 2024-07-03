FROM cimg/android:2024.04

RUN wget https://storage.googleapis.com/flutter_infra_release/releases/stable/linux/flutter_linux_3.22.2-stable.tar.xz && \
    tar xf flutter_linux_3.22.2-stable.tar.xz -C ~/

ENV PATH="$PATH:/home/circleci/flutter/bin"

ARG BASE_IMAGE
FROM $BASE_IMAGE

RUN curl -L "https://dl.google.com/linux/direct/google-chrome-stable_current_x86_64.rpm" -o google-chrome-stable_current_x86_64.rpm \
  && dnf -y install ./google-chrome-stable_current_x86_64.rpm \
  && rm -rf ./google-chrome-stable_current_x86_64.rpm \
  && dnf clean all && rm -rf /var/cache/yum

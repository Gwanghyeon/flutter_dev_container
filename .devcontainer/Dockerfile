FROM cirrusci/flutter:latest
RUN apt-get update && apt-get install -y git curl unzip xz-utils zip libglu1-mesa
ENV PATH="/flutter/bin:$PATH"
WORKDIR /workspace
CMD [ "bash" ]

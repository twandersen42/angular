FROM filipesilva/node-bazel-windows:0.0.2
COPY . /angular
WORKDIR /angular
RUN yarn install --frozen-lockfile --non-interactive --network-timeout 100000

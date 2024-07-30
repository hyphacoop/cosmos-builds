ARG GAIA_VERSION
FROM ghcr.io/cosmos/gaia:${GAIA_VERSION} as base

USER root
RUN apk add --no-cache jq
USER nonroot

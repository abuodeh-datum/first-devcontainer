# Use a specific version for stability
ARG VARIANT="21-bullseye"
FROM mcr.microsoft.com/vscode/devcontainers/java:${VARIANT}

# Install additional OS-level tools (e.g., for data integrations)
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends vim postgresql-client

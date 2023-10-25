# Create Builder
FROM debian:bookworm@sha256:7d3e8810c96a6a278c218eb8e7f01efaec9d65f50c54aae37421dc3cbeba6535 as builder

# Github-releases
ENV ACT_VER v0.2.52
ENV ASCIINEMA_VER v2.3.0
ENV CMCTL_VER v1.13.1
ENV DIFF_SO_FANCY_VER v1.4.4
ENV DOCKER_BUILDX_PLUGIN_VER v0.11.2
ENV DOCKER_COMPOSE_PLUGIN_VER v2.23.0
ENV GHDASH_VER v3.11.0
ENV HELM_VER v3.13.1
ENV K3D_VER v5.6.0
ENV K9S_VER v0.27.4
ENV KUBECTL_VER v1.28.3
ENV KUBENT_VER 0.7.0
ENV LAZYDOCKER_VER v0.23.1
ENV LAZYGIT_VER v0.40.2
ENV LAZYVIM_VER v10.5.0
ENV NEOVIM_VER v0.9.4
ENV SHFMT_VER v3.7.0
ENV STARSHIP_VER v1.16.0
ENV TF_DOCS_VER v0.16.0
ENV WALK_VER v1.6.2

# Repology
# renovate: datasource=repology depName=debian_12/bat versioning=loose
ENV BAT_VER 0.22.1
# renovate: datasource=repology depName=debian_12/build-essential-mipsen versioning=loose
ENV BUILDESSENTIAL_VER 12.9
# renovate: datasource=repology depName=debian_12/ca-certificates versioning=loose
ENV CACERTIFICATES_VER 20230311
# renovate: datasource=repology depName=debian_12/cmake versioning=loose
ENV CMAKE_VER 3.25.1
# renovate: datasource=repology depName=debian_12/containerd versioning=loose
ENV CONTAINERD_VER 1.6.21
# renovate: datasource=repology depName=debian_12/curl versioning=loose
ENV CURL_VER 7.88.1-10+deb12u4
# renovate: datasource=repology depName=arch/docker versioning=loose
ENV DOCKER_CE_VER 24.0.2
# renovate: datasource=repology depName=arch/docker versioning=loose
ENV DOCKER_CE_CLI_VER 24.0.2
# renovate: datasource=repology depName=debian_12/dos2unix versioning=loose
ENV DOS2UNIX_VER 7.4.3
# renovate: datasource=repology depName=debian_12/exa versioning=loose
ENV EXA_VER 0.10.1
# renovate: datasource=repology depName=debian_12/file versioning=loose
ENV FILE_VER 5.44
# renovate: datasource=repology depName=debian_12/fzf versioning=loose
ENV FZF_VER 0.38.0
# renovate: datasource=repology depName=debian_12/gettext versioning=loose
ENV GETTEXT_VER 0.21
# renovate: datasource=repology depName=debian_12/git versioning=loose
ENV GIT_VER 1:2.39.2-1.1
# renovate: datasource=repology depName=debian_12/less versioning=loose
ENV LESS_VER 590
# renovate: datasource=repology depName=debian_12/glibc versioning=loose
ENV LIBC6_DEV_VER 2.36
# renovate: datasource=repology depName=debian_12/npm versioning=loose
ENV NPM_VER 9.2.0
# renovate: datasource=repology depName=debian_12/numpy versioning=loose
ENV NUMPY_VER 1.24.2
# renovate: datasource=repology depName=debian_12/openssl versioning=loose
ENV OPENSSL_VER 3.0.11-1~deb12u1
# renovate: datasource=repology depName=debian_12/python-pip versioning=loose
ENV PIP_VER 23.0.1
# renovate: datasource=repology depName=debian_12/python3-defaults versioning=loose
ENV PYTHON_VER 3.11.2
# renovate: datasource=repology depName=debian_12/rust-ripgrep versioning=loose
ENV RIPGREP_VER 13.0.0
# renovate: datasource=repology depName=debian_12/gcc-12 versioning=loose
ENV GCC_VER 12.2.0
# renovate: datasource=repology depName=scoop/gcloud versioning=loose
ENV GCLOUD_VER 451.0.1
# renovate: datasource=repology depName=debian_12/gh versioning=loose
ENV GH_VER 2.23.0
# renovate: datasource=repology depName=debian_12/git versioning=loose
ENV GIT_VER 1:2.39.2-1.1
# renovate: datasource=repology depName=debian_12/gnupg2 versioning=loose
ENV GNUPG_VER 2.2.40-1.1
# renovate: datasource=repology depName=homebrew/httpie versioning=loose
ENV HTTPIE_VER 3.2.2
# renovate: datasource=repology depName=debian_12/iptables versioning=loose
ENV IPTABLES_VER 1.8.9-2
# renovate: datasource=repology depName=debian_12/jq versioning=loose
ENV JQ_VER 1.6
# renovate: datasource=repology depName=pclinuxos/locales versioning=loose
ENV LOCALES_VER 2.36
# renovate: datasource=repology depName=debian_12/lsof versioning=loose
ENV LSOF_VER 4.95.0
# renovate: datasource=repology depName=debian_12/net-tools versioning=loose
ENV NET_TOOLS_VER 2.10
# renovate: datasource=repology depName=debian_12/pre-commit versioning=loose
ENV PRECOMMIT_VER 3.0.4
# renovate: datasource=repology depName=debian_12/rsync versioning=loose
ENV RSYNC_VER 3.2.7
# renovate: datasource=repology depName=debian_12/software-properties-common versioning=loose
ENV SOFTWARE_PROPERTIES_COMMON_VER 0.99.30-4
# renovate: datasource=repology depName=debian_12/openssh versioning=loose
ENV SSH_VER 9.2p1
# renovate: datasource=repology depName=debian_12/ssl-cert versioning=loose
ENV SSLCERT_VER 1.1.2
# renovate: datasource=repology depName=debian_12/sudo versioning=loose
ENV SUDO_VER 1.9.13p3-1+deb12u1
# renovate: datasource=repology depName=scoop/terraform versioning=loose
ENV TERRAFORM_VER 1.6.2
# renovate: datasource=repology depName=debian_12/thefuck versioning=loose
ENV THEFUCK_VER 3.29
# renovate: datasource=repology depName=debian_12/tldr versioning=loose
ENV TLDR_VER 0.9.2-2+b4
# renovate: datasource=repology depName=debian_12/unzip versioning=loose
ENV UNZIP_VER 6.0
# renovate: datasource=repology depName=debian_12/wget versioning=loose
ENV WGET_VER 1.21.3
# renovate: datasource=repology depName=debian_12/xclip versioning=loose
ENV XCLIP_VER 0.13
# renovate: datasource=repology depName=debian_12/yq versioning=loose
ENV YQ_VER 3.1.0
# renovate: datasource=repology depName=debian_12/zplug versioning=loose
ENV ZPLUG_VER 2.4.2-2
# renovate: datasource=repology depName=debian_12/zsh versioning=loose
ENV ZSH_VER 5.9-4+b2

...SNIPPED...
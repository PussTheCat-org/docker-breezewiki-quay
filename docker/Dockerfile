FROM racket/racket:8.6
WORKDIR /app
RUN apt update -y && apt upgrade -y \
    && apt install -y --no-install-recommends git \
    && apt autoclean -y \
    && apt autoremove -y \
    && rm -rf /var/lib/apt/lists/* \
    && git clone --depth=1 https://gitdab.com/cadence/breezewiki.git . \
    && raco pkg install --auto --skip-installed --batch --no-docs
EXPOSE 10416
CMD ["racket", "dist.rkt"]

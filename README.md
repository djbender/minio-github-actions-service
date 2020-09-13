# minio-github-actions-service

For helping with using minio as a service in Github Actions.

## Usage

    serivces:
      minio:
        env:
          MINIO_ACCESS_KEY: access_key
          MINIO SECRET_KEY: sekret
        image: djbender/minio-github-actions-service
        ports:
          - 9000:9000

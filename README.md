# Minima on Akash
Running a Minima node simply means that you will become a participant in the Minima network.

## How to Deploy
Use deploy.yaml file from this repository as template on Akash Console. Specify MDS password in `minima_mdspassword` environment.

## Usage

Access MDS using URI from your deployment under forwarded port 9003. Don't forget to use `https` instead of `http`.

Access RPC using URI from your deployment under forwarded port 9005. Example: `http://localhost:9005/status`

Enabled RPC means low security. You can find MDS password with URL `http://localhost:9005/mds`

More information about environments variables in [Minima Documentation](https://docs.minima.global/docs/runanode/selectplatform/linux_vps).

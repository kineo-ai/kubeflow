For more details sees the actual [README](./README.md)

# How to run locally

* `nvm use 12.22.8`
* `make build-local`
* `npm run dev`

> **Note**
> The connection with a running cluster works pretty limited for now as we are not authenticated as a actual user.

To run the dashboard connected with a running cluster: `kubectl proxy --port=8083`


# Troubleshoot

* Cleaning up local dependencies: `make clean`
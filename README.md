# ObsInt mock

Mock services used by Observability Intelligence processing team
to mock external services.

It contains:
- Mock AMS: a collection of endpoints from api.openshift.com.
  See details in the [docs](docs/ams-mock.md)
- Mock RHOBS: a mock version of the endpoints we leverage from RH
  Observatorioum. See details in the [docs](docs/rhobs-mock.md)

Those services can be run using `uvicorn` server and calling
the right file.
See the documentation in the [docs](docs) folder for details.

# kalElDB

Database of energy output of Large Scale PhotoVoltaic(PV) facilities in the US.

### Stack
- Python: Language of use for backend and frontend
- PrometheusDB: Time series DB storage and monitoring
- asyncio: Making asynchronous HTTP requests
- Rocketry: Scheduling ETL jobs to pull data from public DBs regularly
- Jupyter: Running experiments against kalElDB
- Numpy, pandas, PyTorch/Lightning: For productionizing ML models for predicting energy efficiency of PV facilities
- HuggingFace: For using pre-existing ML models for time series data on regression tasks
- Streamlit: Create web interface for viewing the database and sharing model predictions
Deployment? Public API for DB? 
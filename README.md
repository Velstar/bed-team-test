## Laravel BED Test

### Objective

Using the Laravel framework, you will process 2 CSV files from a "supplier" (src/dataset) that will need the following saved to a relational database:
- SKU (ManProdNr)
- Supplier Product ID (ProdNr)
- Cost Price (Trade Price)
- RRP (RRP)
- Stock Level (Found in Stock File)

The SKU and Supplier Product ID **MUST** be unique.

Once you have the code ready, please share the Github repo for review.

### What we are looking for
- Commands to start the processes.
- Jobs
    - Creating Jobs
    - Job Batching
      - Job Hydration (https://laravel.com/docs/10.x/queues#adding-jobs-to-batches)
- Eloquent Modelling
- Clean readable code
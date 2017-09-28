# Mangalib android application repository

This repository handles the modification request created on the mobile application.
Anyone with rights on this repository is able to accept a pull-request.

## Workflow
When a user submits a modification from the application, a request is sent to the mangalib server. 
This request is completed by the public API and a pull-request is created on this repository.

When a pull-request is accepted a webhook on the mangalib server will be triggered and therefore update the mangas in the database.

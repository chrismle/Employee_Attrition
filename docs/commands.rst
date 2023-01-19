Commands
========

The Makefile contains the central entry points for common tasks related to this project.

Syncing data to S3
^^^^^^^^^^^^^^^^^^

* `make sync_data_to_s3` will use `aws s3 sync` to recursively sync files in `data/` up to `s3://This project will help IBM’s HR Department and employers by providing an in-depth analysis as to identify what types of employees are choosing to leave, and determining which employees are at risk to leave next. Predicting employee attrition before it happens will allow organization employers and managers to develop strategies to minimize employee attrition rates and motivate employees to stay in their jobs. This project can also help determine the underlying factors and insights important for employee retention./data/`.
* `make sync_data_from_s3` will use `aws s3 sync` to recursively sync files from `s3://This project will help IBM’s HR Department and employers by providing an in-depth analysis as to identify what types of employees are choosing to leave, and determining which employees are at risk to leave next. Predicting employee attrition before it happens will allow organization employers and managers to develop strategies to minimize employee attrition rates and motivate employees to stay in their jobs. This project can also help determine the underlying factors and insights important for employee retention./data/` to `data/`.

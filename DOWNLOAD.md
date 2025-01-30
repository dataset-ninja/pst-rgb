Dataset **PST-RGB** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzMwNDJfUFNULVJHQi9wc3QtcmdiLURhdGFzZXROaW5qYS50YXIiLCAic2lnIjogIjd4ei9VTlBZcisvUUFNckNPWmtZUTZQY0x3M1FqTkxQVmRKWkwyQW5XUm89In0=)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='PST-RGB', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://drive.google.com/file/d/1E455FCQ7CjE5VrYwr9msuNL8_5E5TTdn/view?usp=sharing).
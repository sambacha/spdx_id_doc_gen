SPDXID spdx document generator
==============================

Specs
-----

-  Python 3

1. .. rubric:: Create virtualenv
      :name: create-virtualenv

``python3 -m venv spdx_id_env``

2. .. rubric:: Go to virtualenv
      :name: go-to-virtualenv

``cd spdx_id_env``

3. .. rubric:: Clone repo
      :name: clone-repo

``git clone https://github.com/ekongobie/spdx_id_doc_gen.git``

4. .. rubric:: Activate virtualenv
      :name: activate-virtualenv

``source bin/activate``

5. .. rubric:: go to package folder
      :name: go-to-package-folder

``cd spdx_id_doc_gen``

6. .. rubric:: Install requirements
      :name: install-requirements

``pip install -r requirements.txt``

7. .. rubric:: Install package
      :name: install-package

``pip install -e .``

7. .. rubric:: Generate spdx doc for packages
      :name: generate-spdx-doc-for-packages

``spdxgen ~/path/to/package/folder tv``

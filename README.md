Steps to run cBioPortal Validator:

Requirements:

1. Python 2.7
2. Python modules (requests, jinja2)


cd cbioportal_validator

python validateData.py --s test_data/study_es_0 --p portal_info/ --html output.html -v

Note: Open the output.html in a web browser to look at the errors and warnings.

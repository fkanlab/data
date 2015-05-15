# data
This project collects the open data resources of the [Fluoride Knowledge and Action Network](http://fluorideindia.org).

All data contributed here is made public. Do not add data here that has any privacy or security questions.

Each data set is contained in its own directory with the following structure

    [dir]data_set_name
        [dir]original_data_set
        [dir]csv
        [dir]geojson
        [dir]metadata
            contributors.md
            license.md
            colunmns.md
            file_list.md
            description.md

CSV files are derived from the original dataset and my contain a subset of the columns of the original data set. The geojson files are derived from the CSV.

``metadata/contributors.md`` has a list of contributors and funders for this data set.

``metadata/license.md`` has the license this data is released under.

``metadata/columns.md`` contains the columns in the original data set, csv and json sets.

``metadata/file_list.md`` contains file names of the contents of the data directories - original_data_set, csv and geojson.

``metadata/description.md`` contains credits, sources, and the context in which the data was collected.

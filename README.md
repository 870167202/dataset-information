# dataset-information
The downloaded data about 17 journals in the field of information science from WoS Core Collection
The first .zip files include the details of the 17 journals, such as DOI, publication date, and the references.
The .txt files without 'all_' prefix include the training and test datasets, both of which were extracted from the 17 journals' .zip files.
There are 7616 items in "citations_time_series_training.txt" and 3593 in "citations_time_series_test.txt".
all_LSTM_predict.zip includes the citation counts per paper per year predicted by the LSTM network that the time series given by all_citations_time_series_test.txt are fed into.
all_True_citation_yearly.zip includes the actual citations per paper per year extracted from all_citations_time_series_test.txt and all_citations_time_series_training.txt.
all_citations_time_series_test.txt includes the citation counts time series of papers published between 2004 and 2006, in which the citation counts refer to the number of times that the papers have been cited since publication by any of seventeen journals.
Similarly, all_citations_time_series_training.txt includes the citation counts time series of papers published before 2004.
all_model_predict.zip includes the citation counts per paper per year predicted by the proposed model of which the inputs are the time series given by all_citations_time_series_test.txt.
citations_time_series_test.txt includes the self-citation counts time series of papers published between 2004 and 2006, in which the self-citation counts refer to the number of times that the papers have been cited since publication by the same journal.
Similarly, all_citations_time_series_training.txt includes the self-citation counts time series of papers published before 2004.
self-citation prediction program.zip includes several python files for data processing, which can be run to extract the training and test datasets like the time series included in above .txt files.

##################################
Million Song Dataset - TOP 50 TAGS
##################################

`<http://millionsongdataset.com/>`_
`<https://github.com/keunwoochoi/MSD_split_for_tagging>`_

The **Million Song Dataset** is a freely-available collection of audio features
and metadata for a million contemporary popular music tracks.

Its purposes are:

-  To encourage research on algorithms that scale to commercial sizes
-  To provide a reference dataset for evaluating research
-  As a shortcut alternative to creating a large dataset with APIs (e.g. The
   Echo Nest's)
-  To help new researchers get started in the MIR field

The core of the dataset is the feature analysis and metadata for one million
songs, provided by `The Echo Nest <http://the.echonest.com/>`__. The dataset
does not include any audio, only the derived features. Note, however, that
sample audio can be fetched from services like `7digital
<http://www.7digital.com/>`__, using `code
<https://github.com/tb2332/MSongsDB/tree/master/Tasks_Demos/Preview7digital>`__
we provide.

The Million Song Dataset is also a cluster of complementary datasets
contributed by the community:

-  `SecondHandSongs dataset <http://millionsongdataset.com/secondhand>`__ ->
   cover songs
-  `musiXmatch dataset <http://millionsongdataset.com/musixmatch>`__ -> lyrics
-  `Last.fm dataset <http://millionsongdataset.com/lastfm>`__ -> song-level
   tags and similarity
-  `Taste Profile subset <http://millionsongdataset.com/tasteprofile>`__ ->
   user data
-  `thisismyjam-to-MSD mapping <http://millionsongdataset.com/thisismyjam>`__
   -> more user data
-  `tagtraum genre annotations
   <http://www.tagtraum.com/msd_genre_datasets.html>`__ -> genre labels
-  `Top MAGD dataset <http://www.ifs.tuwien.ac.at/mir/msd/>`__ -> more genre
   labels

The Million Song Dataset started as a collaborative project between `The Echo
Nest <http://the.echonest.com/>`__ and `LabROSA
<http://labrosa.ee.columbia.edu/>`__. It was supported in part by the NSF.

****
Data
****

This is a subset with 250k songs' that are annotated with at least one of the
top-50 tags in the original dataset which contains 1M songs.  The subset was
produced using the code from
`https://github.com/keunwoochoi/MSD_split_for_tagging`_.

******************
Using the dataset?
******************

Please cite the following paper [`pdf
<http://www.columbia.edu/~tb2332/Papers/ismir11.pdf>`__] [`bib
<http://millionsongdataset.com/sites/default/files/millionsong_ismir11_1.bib>`__]:

::

   Thierry Bertin-Mahieux, Daniel P.W. Ellis, Brian Whitman, and Paul Lamere.
   The Million Song Dataset. In Proceedings of the 12th International Society
   for Music Information Retrieval Conference (ISMIR 2011), 2011.

****************
Acknowledgements
****************

The Million Song Dataset was created under a grant from the National Science
Foundation, project IIS-0713334. The original data was contributed by The Echo
Nest, as part of an NSF-sponsored GOALI collaboration. Subsequent donations
from SecondHandSongs.com, musiXmatch.com, and last.fm, as well as further
donations from The Echo Nest, are gratefully acknowledged.

Any opinions, findings and conclusions or recommendations expressed in this
material are those of the authors and do not necessarily reflect the views of
the sponsors.

Usage
#####

Once installed, you can run it simply as:

.. code-block::

   typing_meter

You can also customize each run by specifying the following options as:

* | ``-f FILENAME, --file FILENAME``
  | Uses contents of file as sample text.
* | ``-d N, --difficulty N``
  | N can be in range [1, 5] with 1 being the easiest. This decides the length of the text.
* | ``-i ID, --id ID``
  | ID can be in range [1, 6000].

| typing_meter keeps record of each test in `.typing_meter_history.csv`.
| ``-H N, --history N`` displays last N records.
| N is optional, in the absence of which all records are printed.

You can quit typing_meter anytime by pressing the `ESC` key or `CTRL-C`.

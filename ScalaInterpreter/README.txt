#Explanation

  This is a Scala interpreter designed for use with JupyterNotebook/Anaconda, to keep all of the code in one place. The Scala interpreter is needed as most of PDFFigures2 is
written in Scala, and requires the use of it based off of the paper/github.

#Requirements

  Make **sure** you have Java and Spark downloaded, and know where they're stored on your computer!
  You must also make sure you have the Python packages findspark and pyspark downloaded.

#Usage

  First, before anything else, you **must** run the SparkContext file. Set up the file locations accordingly, and then run it-- if ran correctly, than the last block of code should not "complete", and you'll have an hour-glass symbol showing up in the tab for it. This means that the Spark Context is running accordingly, setting up a local server that allows you to run the Scala interpreter properly.

I have included a Scala Testing folder as well, so that you can run that to check that your Scala interpreter is set up correctly.

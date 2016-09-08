#####################
Contributing
#####################

Do you want to help contribute to mentoring.tech? Awesome! Here are the most common ways you can contribute:

* Open an `issue <https://github.com/mentoring-tech/mentoring-tech/issues/new>`_ 
* `Fork <https://github.com/mentoring-tech/mentoring-tech/fork>`_ the project and submit a PR
* Send an `email`_

Adding/Updating Content
-----------------------

If you are looking to add content, fix formatting, syntax, typos or other
wonderful things, please use the folowing process:

* Install Sphinx: ``easy_install Sphinx sphinx_rtd_theme`` or ``pip install -r requirements.txt``
* Fork the repository to your own account
* Check out a branch to make your changes on: ``git checkout --branch <my_topic>``
* Execute ``make html`` to build the docs in to ``_build/``
* Make your changes
* Execute ``make html`` again and verify your changes don't cause any
  warnings/errors
* Commit with a descriptive message, and submit a pull request from your branch
  to ``master``
* We'll review the change, and either merge it or provide some feedback. Community review is also encouraged.

A quick note if you're adding a new heading:  

Sphinx will error out if your title text is longer than the title underline. For example:
``/projects/mentoring.tech/resources.rst:12: WARNING: Title underline too short.``

And when you look at the title, you see:

.. code-block:: rst

    This title is quite long...
    -----

Which will cause the error. Corrected, the tite would be more like:

.. code-block:: rst

    This title is quite long...
    -----------------------------------

Which will correct the issue.  For any other issues you run into, hop into the Gitter channel and one of us will help out.

.. image:: https://badges.gitter.im/Join%20Chat.svg
   :target: https://gitter.im/mentoring-tech/mentoring-tech
   :alt: Gitter Channel

.. _email: mailto:aaron@aaronmsachs.com 

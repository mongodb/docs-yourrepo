.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">1</div></div>

   Create a directory for your code review toolchain.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      mkdir codereview
      

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 1: Create a directory for your code review toolchain.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      mkdir codereview
      

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">2</div></div>

   Download ``upload.py``.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   https://gist.github.com/i80and/2ae8361d455cc6c70d269a5131cd05f2
   

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 2: Download ``upload.py``.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   https://gist.github.com/i80and/2ae8361d455cc6c70d269a5131cd05f2
   

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">3</div></div>

   Create a wrapper for the code review tool in your preferred text editor.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   Save the following script template as ``codereview.sh``:
   
   .. cssclass:: copyable-code
   .. code-block:: sh
   
      #!/bin/bash
      set -e
   
      jiraUsername='<yourJiraName>'
      emailAddress='<first.last@mongodb.com>'
      codereviewdir='<pathToCodeReviewTool>'
   
      # get the commit message
      msg=`git log -1 --oneline | cut -d' ' -f2-`
      hash=`git rev-parse HEAD`
      hash=$hash~..$hash
   
      if [[ $# -eq 0 ]]; then
         # just last commit
         "$codereviewdir/codereview.sh" -y \
             --jira_user $jiraUsername --email $emailAddress -m "$msg" $hash
      else
         # issue given
         issue=$1
   
         "$codereviewdir/codereview.sh" -y \
             --jira_user $jiraUsername --email $emailAddress -m "$msg" -i $issue $hash
      fi
   

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 3: Create a wrapper for the code review tool in your preferred text editor.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   Save the following script template as ``codereview.sh``:
   
   .. cssclass:: copyable-code
   .. code-block:: sh
   
      #!/bin/bash
      set -e
   
      jiraUsername='<yourJiraName>'
      emailAddress='<first.last@mongodb.com>'
      codereviewdir='<pathToCodeReviewTool>'
   
      # get the commit message
      msg=`git log -1 --oneline | cut -d' ' -f2-`
      hash=`git rev-parse HEAD`
      hash=$hash~..$hash
   
      if [[ $# -eq 0 ]]; then
         # just last commit
         "$codereviewdir/codereview.sh" -y \
             --jira_user $jiraUsername --email $emailAddress -m "$msg" $hash
      else
         # issue given
         issue=$1
   
         "$codereviewdir/codereview.sh" -y \
             --jira_user $jiraUsername --email $emailAddress -m "$msg" -i $issue $hash
      fi
   

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">4</div></div>

   Personalize your wrapper script.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   Change these lines in the wrapper (removing the '<>'):
   

   .. code-block:: sh
   
      jiraUsername='<yourJiraName>'
      emailAddress='<first.last@mongodb.com>'
      codereviewdir='<pathToCodeReviewTool>'
      

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 4: Personalize your wrapper script.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   Change these lines in the wrapper (removing the '<>'):
   

   .. code-block:: sh
   
      jiraUsername='<yourJiraName>'
      emailAddress='<first.last@mongodb.com>'
      codereviewdir='<pathToCodeReviewTool>'
      

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">5</div></div>

   Save your wrapper script into your code review directory.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 5: Save your wrapper script into your code review directory.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">6</div></div>

   Install the code review toolchain.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      sudo install -m755 upload.py $codereviewdir/upload.py
      sudo install -m755 codereview.sh $codereviewdir/codereview.sh
      

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 6: Install the code review toolchain.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      sudo install -m755 upload.py $codereviewdir/upload.py
      sudo install -m755 codereview.sh $codereviewdir/codereview.sh
      

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">7</div></div>

   Add appropriate directory to your ``$PATH`` environment variable to run the ``codereview`` command.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   Add the ``codereview`` directory created above or your ``/Users/`` directory
   to your ``$PATH`` environment variable to run the ``codereview`` command.
   

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 7: Add appropriate directory to your ``$PATH`` environment variable to run the ``codereview`` command.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   Add the ``codereview`` directory created above or your ``/Users/`` directory
   to your ``$PATH`` environment variable to run the ``codereview`` command.
   


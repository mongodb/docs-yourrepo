.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">1</div></div>

   Generate the certificate and follow the prompts. 
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   When you are asked to name the file, you must provide the full path as well.
   Otherwise, press enter when asked to name the file or else the ``.ssh``
   directory may not be created.
   

   .. code-block:: sh
   
      ssh-keygen -t rsa -b 4096 -C "your.name@10gen.com"
      

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 1: Generate the certificate and follow the prompts. 
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   When you are asked to name the file, you must provide the full path as well.
   Otherwise, press enter when asked to name the file or else the ``.ssh``
   directory may not be created.
   

   .. code-block:: sh
   
      ssh-keygen -t rsa -b 4096 -C "your.name@10gen.com"
      

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">2</div></div>

   Set the certificate permissions.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   Change to the default user directory for SSH certificates. Change the
   permissions for the certificate to owner read/write only.
   

   .. code-block:: sh
   
      cd ~/.ssh/
      chmod 600 <name>.pub
      

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 2: Set the certificate permissions.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   Change to the default user directory for SSH certificates. Change the
   permissions for the certificate to owner read/write only.
   

   .. code-block:: sh
   
      cd ~/.ssh/
      chmod 600 <name>.pub
      

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">3</div></div>

   Enable SSH password management.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   This is supposed to be enabled by default on MacOS X systems.
   

   .. code-block:: sh
   
      eval ``ssh-agent``
      

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 3: Enable SSH password management.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   This is supposed to be enabled by default on MacOS X systems.
   

   .. code-block:: sh
   
      eval ``ssh-agent``
      

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">4</div></div>

   Add your certificate to the SSH password manager.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   

   .. code-block:: sh
   
      ssh-add
      

   Enter the password for the certificate.

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 4: Add your certificate to the SSH password manager.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   

   .. code-block:: sh
   
      ssh-add
      

   Enter the password for the certificate.

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">5</div></div>

   Add this certificate to your GitHub account.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   For specific instructions, see
   `GitHub <https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/>`_.
   

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 5: Add this certificate to your GitHub account.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   For specific instructions, see
   `GitHub <https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/>`_.
   


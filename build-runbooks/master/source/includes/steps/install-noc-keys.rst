.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">1</div></div>

   Create a giza AWS configuration file in your home config directory.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      mkdir -m 755 -p ~/.config
      vi ~/.config/giza-aws-authentication.conf
      

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 1: Create a giza AWS configuration file in your home config directory.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      mkdir -m 755 -p ~/.config
      vi ~/.config/giza-aws-authentication.conf
      

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">2</div></div>

   Add an ``[authentication]`` block in your configuration file.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: ini
   
      [authentication]
      accesskey=<AABBCCDDEEFFGGHHIIJJ>
      secretkey=<aBcD+eFgHiJkLmNoP+qRsTuVwXyZAbCdEfGhIjKl>
      

   ``accesskey`` and ``secretkey`` are the values from the AWS credentials
   that |automationperson| gave you for ``noc-prod``.
   

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 2: Add an ``[authentication]`` block in your configuration file.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: ini
   
      [authentication]
      accesskey=<AABBCCDDEEFFGGHHIIJJ>
      secretkey=<aBcD+eFgHiJkLmNoP+qRsTuVwXyZAbCdEfGhIjKl>
      

   ``accesskey`` and ``secretkey`` are the values from the AWS credentials
   that |automationperson| gave you for ``noc-prod``.
   

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">3</div></div>

   Save your configuration file.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 3: Save your configuration file.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">4</div></div>

   Set this file to be owner readable.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      chmod 600 ~/.config/giza-aws-authentication.conf
      

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 4: Set this file to be owner readable.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      chmod 600 ~/.config/giza-aws-authentication.conf
      


.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">1</div></div>

   Fork these repositories into your own GitHub account.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   `This guide from GitHub <https://guides.github.com/activities/forking/>`_ covers the specifics.
   
   - https://github.com/mongodb/docs
   - https://github.com/mongodb/docs-ecosystem
   - https://github.com/mongodb/docs-primer
   - https://github.com/mongodb/docs-assets
   - https://github.com/mongodb/docs-tools
   - https://github.com/10gen/mms-docs
   - https://github.com/10gen/cloud-docs
   - https://github.com/mongodb/docs-bi-connector
   

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 1: Fork these repositories into your own GitHub account.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   `This guide from GitHub <https://guides.github.com/activities/forking/>`_ covers the specifics.
   
   - https://github.com/mongodb/docs
   - https://github.com/mongodb/docs-ecosystem
   - https://github.com/mongodb/docs-primer
   - https://github.com/mongodb/docs-assets
   - https://github.com/mongodb/docs-tools
   - https://github.com/10gen/mms-docs
   - https://github.com/10gen/cloud-docs
   - https://github.com/mongodb/docs-bi-connector
   

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">2</div></div>

   Clone and prepare MongoDB Documentation Assets.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      git clone git@github.com:<yourid>/docs-assets.git
      cd docs-assets
      git remote add upstream git@github.com:mongodb/docs-assets.git
      

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 2: Clone and prepare MongoDB Documentation Assets.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      git clone git@github.com:<yourid>/docs-assets.git
      cd docs-assets
      git remote add upstream git@github.com:mongodb/docs-assets.git
      

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">3</div></div>

   Clone and prepare MongoDB Documentation Toolset.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      git clone git@github.com:<yourid>/docs-tools.git
      cd docs-tools
      git remote add upstream git@github.com:mongodb/docs-tools.git
      

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 3: Clone and prepare MongoDB Documentation Toolset.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      git clone git@github.com:<yourid>/docs-tools.git
      cd docs-tools
      git remote add upstream git@github.com:mongodb/docs-tools.git
      

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">4</div></div>

   Clone and prepare MongoDB Manual documentation.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      git clone git@github.com:<yourid>/docs.git
      cd docs
      giza generate assets
      git remote add upstream git@github.com:mongodb/docs.git
      

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 4: Clone and prepare MongoDB Manual documentation.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      git clone git@github.com:<yourid>/docs.git
      cd docs
      giza generate assets
      git remote add upstream git@github.com:mongodb/docs.git
      

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">5</div></div>

   Clone and prepare MongoDB Primer documentation.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      git clone git@github.com:<yourid>/docs-primer.git
      cd docs-primer
      git remote add upstream git@github.com:mongodb/docs-primer.git
      

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 5: Clone and prepare MongoDB Primer documentation.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      git clone git@github.com:<yourid>/docs-primer.git
      cd docs-primer
      git remote add upstream git@github.com:mongodb/docs-primer.git
      

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">6</div></div>

   Clone and prepare the Cloud/Ops Manager documentation.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      git clone git@github.com:<yourid>/mms-docs.git
      cd mms-docs
      git remote add upstream git@github.com:10gen/mms-docs.git
      

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 6: Clone and prepare the Cloud/Ops Manager documentation.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      git clone git@github.com:<yourid>/mms-docs.git
      cd mms-docs
      git remote add upstream git@github.com:10gen/mms-docs.git
      

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">7</div></div>

   Clone and prepare the Atlas documentation.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      git clone git@github.com:<yourid>/cloud-docs.git
      cd cloud-docs
      git remote add upstream git@github.com:10gen/cloud-docs.git
      

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 7: Clone and prepare the Atlas documentation.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      git clone git@github.com:<yourid>/cloud-docs.git
      cd cloud-docs
      git remote add upstream git@github.com:10gen/cloud-docs.git
      

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">8</div></div>

   Clone and prepare the BI Connector documentation.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      git clone git@github.com:<yourid>/docs-bi-connector.git
      cd docs-bi-connector
      git remote add upstream git@github.com:10gen/docs-bi-connector.git
      

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 8: Clone and prepare the BI Connector documentation.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      git clone git@github.com:<yourid>/docs-bi-connector.git
      cd docs-bi-connector
      git remote add upstream git@github.com:10gen/docs-bi-connector.git
      


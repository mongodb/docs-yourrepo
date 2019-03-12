.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">1</div></div>

   Login to your AWS Account.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   Login to `AWS for the Education department <https://idp.mongodb.com/simplesaml/saml2/idp/SSOService.php?spentityid=urn:amazon:webservices:univ-training-991734710418>`_.
   

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 1: Login to your AWS Account.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   Login to `AWS for the Education department <https://idp.mongodb.com/simplesaml/saml2/idp/SSOService.php?spentityid=urn:amazon:webservices:univ-training-991734710418>`_.
   

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">2</div></div>

   Connect to your AWS Instance.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   
   a. After you have `created an instance
      <https://gist.github.com/atsansone/52e63e3f22811adcc8b6#create-an-aws-instance>`_,
      click on radio button for your instance.
   
   b. Click :guilabel:`Connect`.
   

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 2: Connect to your AWS Instance.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   
   a. After you have `created an instance
      <https://gist.github.com/atsansone/52e63e3f22811adcc8b6#create-an-aws-instance>`_,
      click on radio button for your instance.
   
   b. Click :guilabel:`Connect`.
   

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">3</div></div>

   Choose or create an SSH Key (if needed).
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   
   If this is your first time connecting to this instance, EC2 asks if you want
   to use an existing key file or create a new one.
   
   If you need to create a new key file, click :guilabel:`Create New Key`. A
   new key downloads to your computer.
   

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 3: Choose or create an SSH Key (if needed).
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   
   If this is your first time connecting to this instance, EC2 asks if you want
   to use an existing key file or create a new one.
   
   If you need to create a new key file, click :guilabel:`Create New Key`. A
   new key downloads to your computer.
   

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">4</div></div>

   Copy this key file to your SSH certificate directory.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   

   .. code-block:: sh
   
      cp yourawscert.pem ~/.ssh/
      

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 4: Copy this key file to your SSH certificate directory.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   

   .. code-block:: sh
   
      cp yourawscert.pem ~/.ssh/
      

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">5</div></div>

   Change the ownership of this key file.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   The key file must only be readable by you.
   

   .. code-block:: sh
   
      chmod 600 ~/.ssh/yourawscert.pem
      

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 5: Change the ownership of this key file.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   The key file must only be readable by you.
   

   .. code-block:: sh
   
      chmod 600 ~/.ssh/yourawscert.pem
      


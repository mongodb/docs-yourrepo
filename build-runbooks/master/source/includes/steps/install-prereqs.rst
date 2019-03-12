.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">1</div></div>

   Download and Install XCode.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   This is required for some development capabilities on a Mac OS system.
   
   Find XCode on the `Apple Developer Site <https://developer.apple.com/xcode/download/>`_.
   

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 1: Download and Install XCode.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   This is required for some development capabilities on a Mac OS system.
   
   Find XCode on the `Apple Developer Site <https://developer.apple.com/xcode/download/>`_.
   

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">2</div></div>

   Download and Install Inkscape.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   
   - `Download and Install XQuartz <http://www.xquartz.org/>`_.
     This is required to install Inkscape.
   - `Download and Install Inkscape <https://inkscape.org/en/>`_.
     This is required for any image generation for staging.
   

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 2: Download and Install Inkscape.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   
   - `Download and Install XQuartz <http://www.xquartz.org/>`_.
     This is required to install Inkscape.
   - `Download and Install Inkscape <https://inkscape.org/en/>`_.
     This is required for any image generation for staging.
   

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">3</div></div>

   Download and Install Homebrew.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   This is required to install certain development tools including MongoDB itself.
   

   .. code-block:: sh
   
      /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
      brew update
      brew doctor
      

   .. note::
      ``brew`` will indicate if it needs root privileges and request the root password at that time.
      More information on `Homebrew <http://brew.sh/>`_ can be found online.
   

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 3: Download and Install Homebrew.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   This is required to install certain development tools including MongoDB itself.
   

   .. code-block:: sh
   
      /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
      brew update
      brew doctor
      

   .. note::
      ``brew`` will indicate if it needs root privileges and request the root password at that time.
      More information on `Homebrew <http://brew.sh/>`_ can be found online.
   

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">4</div></div>

   Install Python and Python 3.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      brew install python
      brew install python3
      

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 4: Install Python and Python 3.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   .. code-block:: sh
   
      brew install python
      brew install python3
      

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">5</div></div>

   Install MongoDB Version Manager.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   Install https://github.com/aheckmann/m[MongoDB Version Manager]
   This allows you to run different versions of MongoDB on one machine.
   

   Install MongoDB Version Manager.
   ````````````````````````````````

   .. code-block:: sh
   
      sudo npm install -g m
      

   .. note:: See https://github.com/aheckmann/m[MongoDB Version Manager] for more information on how to install versions of MongoDB.
   

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 5: Install MongoDB Version Manager.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   Install https://github.com/aheckmann/m[MongoDB Version Manager]
   This allows you to run different versions of MongoDB on one machine.
   

   Install MongoDB Version Manager.
   ````````````````````````````````

   .. code-block:: sh
   
      sudo npm install -g m
      

   .. note:: See https://github.com/aheckmann/m[MongoDB Version Manager] for more information on how to install versions of MongoDB.
   

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">6</div></div>

   Install a specific version, edition or platform.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   If you need a specific version, edition or platform of MongoDB, check the Private Build list for https://corp.10gen.com/dlBrowse?os=osx[OS X], https://corp.10gen.com/dlBrowse?os=linux[Linux] or https://corp.10gen.com/dlBrowse?os=win32[Windows].
   

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 6: Install a specific version, edition or platform.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   If you need a specific version, edition or platform of MongoDB, check the Private Build list for https://corp.10gen.com/dlBrowse?os=osx[OS X], https://corp.10gen.com/dlBrowse?os=linux[Linux] or https://corp.10gen.com/dlBrowse?os=win32[Windows].
   

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">7</div></div>

   Install Documentation Building Tools.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   Install Mut.
   ````````````

   .. code-block:: sh
   
      bash -c "$(curl -fsSL https://raw.githubusercontent.com/mongodb/mut/master/install.sh)"
      

   .. note:: More information on ``mut`` can be found on the https://docs-mongodbcom-staging.corp.mongodb.com/mut/tutorial/installation.html[mut guide].
   

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 7: Install Documentation Building Tools.
   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

   Install Mut.
   ````````````

   .. code-block:: sh
   
      bash -c "$(curl -fsSL https://raw.githubusercontent.com/mongodb/mut/master/install.sh)"
      

   .. note:: More information on ``mut`` can be found on the https://docs-mongodbcom-staging.corp.mongodb.com/mut/tutorial/installation.html[mut guide].
   


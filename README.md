# fullThrottleLabs

###REQUIREMENTS

[virtualenvwrapper](http://virtualenvwrapper.readthedocs.org/en/latest/install.html)


###DEVELOPMENT

    # Clone the respositiory 
    git clone https://github.com/vikashvishnu1508/fullThrottleLabs.git
    
    # Change into project directory
    cd <project_name>
    
    # Make virtual environment
    mkvirtualenv <project_name>
    
    # Activate virtual environment
    workon <project_name>
    
    # Install requirements
    pip install -r requirements.txt
    
    # Setup (if necessary)
    fab loc setup
    
    # Start the development server
    python manage.py runserver
    

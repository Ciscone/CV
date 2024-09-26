# CV systems

## Create env in your local OS

``conda env create -f hl_w_zeno.yml``

## Set up git repo
1. Go to your folder

    ``cd repo``

2. Initialize git repo

    ``git init -b main``

3. Configure username and email

    ``git config --global user.name "<YourUsername>"``
    ``git config --global user.email "<YourEmail>"``

4. Add remote link

    ``git remote add origin https://gitlab.icfo.net/gfranceschetto/hamiltonian_learning_zeno_effect.git``

## Git Development cycle

1. Check for origin updates

   ``git fetch origin``

2. Merge updates
  
    ``git merge origin/main``

3. Do work

4. Add changes

    ``git add <your changes>``

5. Commit changes

    ``git commit -m <what have you done?>``

6. Push changes

    ``git push origin main``


-Frontend template
-virtualenv:
  -create
  - activate [windows: source ./scripts/activate]
  - pip install
  - deactivate

upload project on github

-url : path
-view : logic
-models: db
templates: frontend



relations : 
  - one to many    [ user - posts ]   foreginkey
  - Many to many   [ users - groups ]
  - One to one     [ user - profile ]
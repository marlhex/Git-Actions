React + Github actions

It has 3 different workflows

type a) 

  job
    step 1
    step 2
    step 3


  Type b): jobs running sequentially, which listens by every push
    Job lint
      step 1

    Job test
      step 

    Job deploy
      Step

  type C) 
    another workflow to listen for new issues

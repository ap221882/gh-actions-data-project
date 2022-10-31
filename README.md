# gh-actions-data-project
A practise project to understand data usage in gh actions


Learnt Artifacts, Job Outputs, outputs sharing, caching during actions.



ENVIRONMENT VARIABLES IN GH ACTIONS

env:
    VARIABLE: AJAY
    
referenced by-

    ${{ env.VARIABLE }} 
          OR
     $VARIABLE (on ubuntu)


SECRETS: 
    can be referenced by
    ${{ secrets.SECRET_NAME }}

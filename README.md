# gh-actions-data-project
A practice project to understand data usage in gh actions


Learnt Artifacts, Job Outputs, outputs sharing, caching during actions.



ENVIRONMENT VARIABLES IN GH ACTIONS (can be step-level, job-level, global)

env:
    VARIABLE: AJAY
    
referenced by-

    ${{ env.VARIABLE }} 
          OR
     $VARIABLE (on ubuntu)


SECRETS: 
    can be referenced by
    ${{ secrets.SECRET_NAME }}



ENVIRONMENTS

-are for jobs
to activate a environment in a job
    jobs:
        jobname:
                environment: <environment_name>

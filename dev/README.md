


Migracion de Portal:
    Front end:
    - Account creation (migrated)
    - Update profile (same workfloe)
    - Change password (new workflow)
    - Change VolvoID (new workflow)
    - Delete VolvoID (new workflow)
    - Captcha (At Front Level)
    - L&F redesign

    Back End (migrate to Account API):
    - Account creation endpoint (done)
        -- Check monitoring
        -- Check code smells
        -- Check coverage
        -- Check logging and tracing
    - UpdateProfile endpoint (done)
    - Change Password (done)
    - Change VolvoID (done)
    - Delete VolvoID (done)


    ducs-user:
        - Log all clients per endpoint
        - Add metric for error with distributed lock.
        - Research warmup errors with lock in ducs-user.
        - Check activation logic (document sequence diagram).
        - Check cassandra usage.



    
# CI detection fixture

AC 5. azure-pipelines.yml with no steps:/jobs:/stages: - fails the readability gate. Must report UNREADABLE, not 'no CI'.

Expected verdict line in the Octiq chat:

    Tests not run - CI config found (azure-pipelines.yml) but this detector could not read it

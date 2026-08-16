# Deployment Health Checklist

Steps every service must pass before a production deploy:

1. Stage smoke tests green for 30 minutes
2. Database migrations applied and reversible
3. Error rate below 0.1% on stage
4. Rollback command documented in the runbook
5. On-call engineer acknowledged the deploy window
